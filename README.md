# cnn-mel-audio-command-recognition

## The dataset
This repository does not contain the audio files or mel-spectograms. In order to use this project, collect your own dataset.  

Create folders with the following structure:  

```text
cnn-mel-audio-command-recognition/
└── data/
    ├── train/
    │   ├── finnish/
    │   │   ├── paalle/
    │   │   ├── pysahdy/
    │   │   ├── ylos/
    │   │   ├── alas/
    │   │   ├── oikea/
    │   │   └── vasen/
    │   └── english/
    │       ├── start/
    │       ├── stop/
    │       ├── up/
    │       ├── down/
    │       ├── right/
    │       └── left/
    ├── test/
    └── validation/
```

The test and validation folders must contain exactly the same internal folder structure as train, including both language folders and all corresponding command category folders.
