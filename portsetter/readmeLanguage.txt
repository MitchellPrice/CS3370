To set a custom language – make sure that the language files are in the same folder as the program and make sure one of the following environment variables are set with the language:
LANGUAGE             LC_ALL         LC_MESSAGES        LANG

The language variables must be set within one of the following formats:
es         es.UTF-8         es_MX             es_MX.UTF-8

*In these examples the language is set to Spanish because of “es”
*In these examples the local “MX” defines that the Spanish is Mexican Spanish
*The two letter language code must be lower case

If a custom language is not in the library or the files are not there the program will default to English and print an error
