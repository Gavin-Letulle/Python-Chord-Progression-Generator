# Python-Chord-Progression-Generator
This chord progression generator takes in any musical key in either major or minor mode, as well as the amount of chords desired, and generates a musically satisfying chord progression in the form of a midi file that can be loaded directly into any DAW such as Garage Band.

IN ORDER TO RUN THE SCRIPT YOU MUST FOLLOW THESE STEPS:

1. Clone the repository with: "git clone git@github.com:Gavin-Letulle/Python-Chord-Progression-Generator.git"
2. Create a virtual envirnoment using the command: "python -m venv venv"
3. Activate the virtual environment, if you're on Windows, use: "venv\Scripts\activate"
                                     if you're on macOS or Linux, then use: "source venv/bin/activate"                                   
4. Finally, install the required dependencies using: "pip install -r requirements.txt"


After all of that, you should be able to run the script using "python ConvertChordsToMidi"

Note: The script will automatically create a midi file named "chord_progression.mid", which you can then load into any DAW of choice.