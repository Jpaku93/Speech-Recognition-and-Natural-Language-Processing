# Speech Recognition and Natural Language Processing
 This is a basic voice Trancribing application that macthes terms leading to programmed applications, in this case txt files, screen shots and a scruffy Dutch translation.

## prerequisites == voice recognition
* SpeechRecognition
* os
* pyautogui
* datetime
* subprocess
* pickle
* keras
* numpy

## Function overview
* Take command - transcribe input audio using english speech recognizer
* There exists - Match transcription with terms
* Note Class - Make, update, get or delete note
* Screenshot - Take screen shots
* TranslateToDutch - Load model and tokenizer to predict Dutch trancription 
* LogitsToText - Convert encoded model output to text 
* Mainframe - Contains Command function and terms leading to actions in if statements


## prerequisites == NM Translator
* keras
* numpy
* string
* os
* pickle

> The training data seems quite hideous believe it or not the test results look quite good, in any case the live prediction results are super scruffy, compared to overfitting, the data definately needs more variety of sentences as alot of duplicate sentences return different meanings from the training data.

