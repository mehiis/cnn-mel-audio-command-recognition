# cnn-mel-audio-command-recognition

## The dataset
This repository does not contain the audio files or mel-spectograms. In order to use this project, collect your own dataset.  

Create folders with the following structure:  

```text
data/
│
├── audio-samples/
│   ├── train/
│   │   ├── finnish/
│   │   │   ├── train/
│   │   │   │   ├── ylos/
│   │   │   │   ├── alas/
│   │   │   │   ├── vasen/
│   │   │   │   ├── oikea/
│   │   │   │   ├── paalle/
│   │   │   │   └── pysahdy/
│   │   │   ├── test/
│   │   │   └── validation/
│   │   │
│   │   └── english/
│   │       ├── train/
│   │       │   ├── up/
│   │       │   ├── down/
│   │       │   ├── left/
│   │       │   ├── right/
│   │       │   ├── stop/
│   │       │   └── start/
│   │       ├── test/
│   │       └── validation/
│   │
│   ├── test/
│   │   ├── finnish/
│   │   │   ├── train/
│   │   │   ├── test/
│   │   │   └── validation/
│   │   └── english/
│   │       ├── train/
│   │       ├── test/
│   │       └── validation/
│   │
│   └── validation/
│       ├── finnish/
│       │   ├── train/
│       │   ├── test/
│       │   └── validation/
│       └── english/
│           ├── train/
│           ├── test/
│           └── validation/
│
├── audio-wav/
│   └── (SAME BRANCHING AS "audio-samples/")
│
└── image-samples/
    └── (SAME BRANCHING AS "audio-samples/")
```
The test and validation folders must contain exactly the same internal folder structure as train, including both language folders and all corresponding command category folders.
