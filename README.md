# Speech-To-Text-Kannada
This is a Python application that allows users to convert speech in Kannada into text and save the transcribed text into a Microsoft Word document. The application uses the speech_recognition library for speech-to-text conversion and tkinter for the graphical user interface (GUI).

# Features
Continuous Speech-to-Text: Converts spoken Kannada into text in real-time.
Real-Time Display: Displays the transcribed text in a scrollable text box.
Save to Word: Saves the recognized Kannada text into a .docx file.
Excludes system messages and errors from the saved document.
Custom File Naming: Users can specify the filename for the saved document.
Error Handling: Handles errors like "Unable to recognize speech" or "API issues" gracefully without disrupting the application.

# Requirements
Required Python libraries:
speech_recognition
tkinter (included in standard Python installations)
python-docx

* Word Document Not Saving: Ensure you have permission to save files in the specified directory.
  
# Installation
~~~ Install Python Dependencies:
pip install speechrecognition python-docx

Execute the script using Python:
python kannada_speech_to_text.py
~~~

