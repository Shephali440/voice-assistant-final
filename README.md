Voice Assistant using Python


Shephali Voice Assistant 
A simple Python-based voice assistant that listens to your voice commands and performs tasks such as searching on Wikipedia, opening websites, launching WhatsApp, and accessing local drives.

1. Features:
Speech Recognition using speech_recognition
Text-to-Speech using pyttsx3
Search any topic on Wikipedia
Open websites like YouTube, Google, GitHub, StackOverflow, Spotify
Responds to queries like "Who are you"
Open Local Disks (C, D, E drives)
Launch WhatsApp Desktop from your PC
Play music (opens Spotify)
Stop the assistant by saying "out"

2. Requirements
Install the required Python libraries:
pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia
pip install pyaudio
▶️ How to Run
Save the code as assistant.py

3. Run the program:
python assistant.py
Speak into your microphone and try commands.

Available Voice Commands
Command	Action Performed
wikipedia <topic>	Searches the topic on Wikipedia (2 sentences)
are you	Introduces the assistant
open youtube	Opens YouTube in browser
open google	Opens Google in browser
open github	Opens GitHub in browser
open stackoverflow	Opens StackOverflow in browser
open spotify	Opens Spotify in browser
open whatsapp	Launches WhatsApp Desktop app
play music	Opens Spotify (for music)
local disk d	Opens Local Disk D
local disk c	Opens Local Disk C
local disk e	Opens Local Disk E
out	Exits the assistant

👩‍💻 Author
Developed by Shephali Anand
