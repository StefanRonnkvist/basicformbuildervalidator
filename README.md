# Basic Form Builder Validators


### The following FormBuilder Validators: 

### Validators 
#### Bool  
* FormBuilderValidators.hasLowercaseChars() - requires the field's to contain a specified number of lowercase characters.  
* FormBuilderValidators.hasNumericChars() - requires the field's to contain a specified number of numeric characters.  
* FormBuilderValidators.hasSpecialChars() - requires the field's to contain a specified number of special characters.  
* FormBuilderValidators.hasUppercaseChars() - requires the field's to contain a specified number of uppercase characters.  
* FormBuilderValidators.isFalse() - requires the field's to be false.  
* FormBuilderValidators.isTrue() - requires the field's to be true.

#### Collection  
* FormBuilderValidators.containsElement() - requires the field's to be in the provided list.  
* FormBuilderValidators.equalLength() - requires the length of the field's value to be equal to the provided minimum length.  
* FormBuilderValidators.maxLength() - requires the length of the field's value to be less than or equal to the provided maximum size.  
* FormBuilderValidators.minLength() - requires the length of the field's value to be greater than or equal to the provided minimum length.  
* FormBuilderValidators.range() - requires the field's to be within a range.  
* FormBuilderValidators.unique() - requires the field's to be unique in the provided list.

#### Core  
* FormBuilderValidators.aggregate() - runs the validators in parallel, collecting all errors.  
* FormBuilderValidators.compose() - runs each validator against the value provided.  
* FormBuilderValidators.conditional() - conditionally runs a validator against the value provided.  
* FormBuilderValidators.defaultValue() - runs the validator using the default value when the provided value is null.  
* FormBuilderValidators.equal() - requires the field's value to be equal to the provided object.  
* FormBuilderValidators.log() - runs the validator and logs the value at a specific point in the validation chain.  
* FormBuilderValidators.notEqual() - requires the field's value to be not equal to the provided object.  
* FormBuilderValidators.or() - runs each validator against the value provided and passes when any works.  
* FormBuilderValidators.required() - requires the field to have a non-empty value.  
* FormBuilderValidators.skipWhen() - runs the validator and skips the validation when a certain condition is met.  
* FormBuilderValidators.transform() - transforms the value before running the validator.

#### Datetime  
* FormBuilderValidators.dateFuture() - requires the field's value to be in the future.  
* FormBuilderValidators.datePast() - requires the field's value to be a in the past.  
* FormBuilderValidators.dateRange() - requires the field's value to be a within a date range.  
* FormBuilderValidators.dateTime() - requires the field's value to be a valid date time.  
* FormBuilderValidators.date() - requires the field's value to be a valid date string.  
* FormBuilderValidators.time() - requires the field's value to be a valid time string.  
* FormBuilderValidators.timeZone() - requires the field's value to be a valid time zone.

#### File  
* FormBuilderValidators.fileExtension() - requires the field's value to a valid file extension.  
* FormBuilderValidators.fileName() - requires the field's to be a valid file name.  
* FormBuilderValidators.fileSize() - requires the field's to be less than the max size.  
* FormBuilderValidators.mimeType() - requires the field's value to a valid MIME type.  
* FormBuilderValidators.path() - requires the field's to be a valid file or folder path.

#### Finance  
* FormBuilderValidators.bic() - requires the field's to be a valid BIC.  
* FormBuilderValidators.creditCardCVC() - requires the field's value to be a valid credit card CVC number.  
* FormBuilderValidators.creditCardExpirationDate() - requires the field's value to be a valid credit card expiration date and can check if not expired yet.  
* FormBuilderValidators.creditCard() - requires the field's value to be a valid credit card number.  
* FormBuilderValidators.iban() - requires the field's to be a valid IBAN.

#### Identity  
* FormBuilderValidators.city() - requires the field's value to be a valid city name.  
* FormBuilderValidators.country() - requires the field's value to be a valid country name.  
* FormBuilderValidators.firstName() - requires the field's value to be a valid first name.  
* FormBuilderValidators.lastName() - requires the field's value to be a valid last name.  
* FormBuilderValidators.passportNumber() - requires the field's value to be a valid passport number.  
* FormBuilderValidators.password() - requires the field's to be a valid password that matched required conditions.  
* FormBuilderValidators.ssn() - requires the field's to be a valid SSN (Social Security Number).  
* FormBuilderValidators.state() - requires the field's value to be a valid state name.  
* FormBuilderValidators.street() - requires the field's value to be a valid street name.  
* FormBuilderValidators.username() - requires the field's to be a valid username that matched required conditions.  
* FormBuilderValidators.zipCode() - requires the field's to be a valid zip code.

#### Network  
* FormBuilderValidators.email() - requires the field's value to be a valid email address.  
* FormBuilderValidators.ip() - requires the field's value to be a valid IP address.  
* FormBuilderValidators.latitude() - requires the field's to be a valid latitude.  
* FormBuilderValidators.longitude() - requires the field's to be a valid longitude.  
* FormBuilderValidators.macAddress() - requires the field's to be a valid MAC address.  
* FormBuilderValidators.phoneNumber() - requires the field's value to be a valid phone number.  
* FormBuilderValidators.portNumber() - requires the field's to be a valid port number.  
* FormBuilderValidators.url() - requires the field's value to be a valid URL.

#### Numeric  
* FormBuilderValidators.between() - requires the field's to be between two numbers.  
* FormBuilderValidators.evenNumber() - requires the field's to be an even number.  
* FormBuilderValidators.integer() - requires the field's value to be an integer.  
* FormBuilderValidators.max() - requires the field's value to be less than or equal to the provided number.  
* FormBuilderValidators.min() - requires the field's value to be greater than or equal to the provided number.  
* FormBuilderValidators.negativeNumber() - requires the field's to be a negative number.  
* FormBuilderValidators.notZeroNumber() - requires the field's to be not a number zero.  
* FormBuilderValidators.numeric() - requires the field's value to be a valid number.  
* FormBuilderValidators.oddNumber() - requires the field's to be an odd number.  
* FormBuilderValidators.positiveNumber() - requires the field's to be a positive number.  
* FormBuilderValidators.prime() - requires the field's to be a prime number.

#### String  
* FormBuilderValidators.alphabetical() - requires the field's to contain only alphabetical characters.  
* FormBuilderValidators.contains() - requires the substring to be in the field's value.  
* FormBuilderValidators.endsWith() - requires the substring to be the end of the field's value.  
* FormBuilderValidators.lowercase() - requires the field's value to be lowercase.  
* FormBuilderValidators.matchNot() - requires the field's value to not match the provided regex pattern.  
* FormBuilderValidators.match() - requires the field's value to match the provided regex pattern.  
* FormBuilderValidators.maxWordsCount() - requires the word count of the field's value to be less than or equal to the provided maximum count.  
* FormBuilderValidators.minWordsCount() - requires the word count of the field's value to be greater than or equal to the provided minimum count.  
* FormBuilderValidators.singleLine() - requires the field's string to be a single line of text.  
* FormBuilderValidators.startsWith() - requires the substring to be the start of the field's value.  
* FormBuilderValidators.uppercase() - requires the field's value to be uppercase.

#### Use-case  
* FormBuilderValidators.base64() - requires the field's to be a valid base64 string.  
* FormBuilderValidators.colorCode() - requires the field's value to be a valid color code.  
* FormBuilderValidators.duns() - requires the field's value to be a valid DUNS.  
* FormBuilderValidators.isbn() - requires the field's to be a valid ISBN.  
* FormBuilderValidators.json() - requires the field's to be a valid json string.  
* FormBuilderValidators.languageCode() - requires the field's to be a valid language code.  
* FormBuilderValidators.licensePlate() - requires the field's to be a valid license plate.  
* FormBuilderValidators.uuid() - requires the field's to be a valid uuid.  
* FormBuilderValidators.vin() - requires the field's to be a valid VIN number.

#### Extension method  
* FormBuilderValidator.and() - Combines the current validator with another validator using logical AND.  
* FormBuilderValidator.or() - Combines the current validator with another validator using logical OR.  
* FormBuilderValidator.when() - Adds a condition to apply the validator only if the condition is met.  
* FormBuilderValidator.unless() - Adds a condition to apply the validator only if the condition is not met.  
* FormBuilderValidator.transform() - Transforms the value before applying the validator.  
* FormBuilderValidator.skipWhen() - Skips the validator if the condition is met.  
* FormBuilderValidator.log() - Logs the value during the validation process.  
* FormBuilderValidator.withErrorMessage() - Overrides the error message of the current validator.  