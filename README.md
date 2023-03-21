#Audio Processing Script

This script is a simple audio processing tool that allows you to load a WAV file, apply Mel-frequency cepstral coefficients (MFCCs) to the audio signal, and play the original audio signal and the processed audio (MFCC). It uses the following Python libraries:

tkinter: for the GUI interface.
librosa: for audio processing and feature extraction.
numpy: for numerical operations.
sounddevice: for audio playback.
Usage
To use this tool, run the audio_processing.py script in Python 3. The GUI window will appear with three buttons:

"Load Audio": to load a WAV file.
"Apply MFCC": to apply MFCC to the loaded audio file.
"Play Audio": to play the original audio signal.
"Play MFCC": to play the processed audio (MFCC).
Once the audio file is loaded, you can apply MFCC to the audio signal by clicking the "Apply MFCC" button. This will calculate the MFCCs using librosa and store them in the mfccs variable. You can then play the original audio signal and the processed audio (MFCC) by clicking the "Play Audio" and "Play MFCC" buttons respectively.

Requirements
This script requires the following Python libraries:

tkinter
librosa
numpy
sounddevice
You can install them using pip:

Copy code
pip install tkinter librosa numpy sounddevice
