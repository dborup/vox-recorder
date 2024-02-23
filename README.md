# vox-recorder

Voice activated audio recorder intended for scanner radio use. Record starts when audio level is higher than threshold and records end after 5 seconds of silence.
Execution Flow: When executed, the script prompts the user to select an audio device for recording. It then continuously monitors for voice activity, recording each event as a separate file until the script is terminated.

## Depencies
python3
python3-pyaudio

## Usage

./vox-recorder.py

Audio recordings will be saved to ~/vox-records. Save file type is wav. Audio file names are timestamped eg,

    voxrecord-20180705222631-20180705222639.wav
    
Use another application to select recording soundcard you like to use, like pavucontrol.

## Licence

GPLv3
