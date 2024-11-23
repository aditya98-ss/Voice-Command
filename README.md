# Voice command
This software is made in Python. This is voice command which give you output according to your predefined codes.

## Installation
$	Install python3.x in your system
$	Type this command in your terminal

```
pip3 install -r requirements.txt
```


### Note :-
*	If your are not able download pyaudio then download pyaudio file from [here](https://www.lfd.uci.edu/%7Egohlke/pythonlibs/)
*	Make sure device is connected to internet while executing this code

## Execution

$	Run main.py file
```
python3 main.py
```

## Setup

For addding new commands add commands to data.ar file in this format
```
new command:response to this command
```
### Example
```
name:My name is xyz
```

If user execute the file and speak = "What is your name", then this program will identify keyword "name" in sentance and respond - "My name is xyz"

### Note:-
Date and time are set by default, you cannot add this command in "data.ar" file

## Programming languages used Python

