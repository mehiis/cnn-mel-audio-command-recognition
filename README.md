# cnn-mel-audio-command-recognition

## The dataset
This repository does not contain the audio files or mel-spectograms. In order to use this project, collect your own dataset.  

Create folders with the following structure:  

```text
data/
├── audio-samples/          
│   ├── finnish/
│   │   └── {train,test,validation}/<command>/
│   └── english/
│       └── {train,test,validation}/<command>/
│
├── audio-wav/             
│   ├── finnish/
│   │   └── {train,test,validation}/<command>/
│   └── english/
│       └── {train,test,validation}/<command>/
│
└── image-samples/ 
    ├── finnish/
    │   └── {train,test,validation}/<command>/
    └── english/
        └── {train,test,validation}/<command>/
```

The test and validation folders must contain exactly the same internal folder structure as train, including both language folders and all corresponding command category folders.
