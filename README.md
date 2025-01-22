# Handmate-MIDI-Offline
We recommend using Google Chrome, Firefox or Microsoft Edge as web MIDI is not supported by some other browsers including Safari. This version has been developed for desktop only. Windows users need to use loopMidi or VBAN-2-Midi as a bridge (driver) for the MIDI out device. Please make sure you have enabled MIDI in your browser security settings.

The MidiTest MaxMSP patch is included here as an example of how to get the MIDI information from the browser.

YouTube Demo: https://youtu.be/H97t17Q_BbM

For more information on MediaPipe and the machine-learning models, see https://google.github.io/mediapipe/.

Credits: We use the WebMidi API. Check it out here: https://webmidijs.org/

Thank you: Natalia Kotsani and Mirza Ceyzar for help in developing this.


# Installation Guide for Beginners
You must have Node installed on your computer. If you don't, download the latest stable version [here](https://nodejs.org/en/). Launch the installer and install Node.

Download the Handmate-MIDI-Offline code folder.

Open your terminal window on Mac (press CMD + spacebar simultaneously, in the search window, type in terminal and enter) or Command Prompt on Windows. Go to the folder where you downloaded Handmate-MIDI-Offline. You can do this by just dragging the folder into the terminal winwdow and press enter. Or type in 'cd' followed by the path name. For example, if you put the folder on your desktop:

```$ cd desktop/Handmate-MIDI-Offline/```

Install package dependencies (the files you will need to run the code) by typing in:

```$ npm install```

Mac users - If you get a permission error, try typing this instead and when terminal asks for a password, enter your administrator password:

```$ sudo npm install```

Go to http://127.0.0.1:5500/index.html on your browser. Start waving your hands around.
