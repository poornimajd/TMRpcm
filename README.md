# TMRpcm
Arduino library for asynchronous playback of PCM/WAV files direct from SD card. Arduino Uno,Nano,Mega etc supported http://tmrh20.blogspot.com






Utilizes standard Arduino SD library, SD card and output device (Speaker, Headphones, Amplifier, etc)

Documentation is available on the Wiki: https://github.com/TMRh20/TMRpcm/wiki

Recent Updates
Many new features have recently been added, and are in development. See the wiki: https://github.com/TMRh20/TMRpcm/wiki/Advanced-Features

Features  
  
    PCM/WAV playback direct from SD card  
    Main formats: WAV files, 8-bit, 8-32khz Sample Rate, mono. See the wiki for other options.  
    Asynchronous Playback: Allows code in main loop to run while audio playback occurs.  
    Single timer operation: TIMER1 (Uno,Mega) or TIMER3,4 or 5 (Mega)  
    Complimentary output or dual speakers  
    2x Oversampling  
    Supported devices: Arduino Uno, Nano, Mega, etc.  
    More! See the wiki https://github.com/TMRh20/TMRpcm/wiki/Advanced-Features  
