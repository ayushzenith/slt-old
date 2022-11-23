# SLT - Continuous Sign Language Translation for German
Sign Language Translation - German


## Dataset - [RWTH-PHOENIX-Weather 2014 T: Parallel Corpus of Sign Language Video, Gloss and Translation](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/)


Download the zip [here](https://www-i6.informatik.rwth-aachen.de/ftp/pub/rwth-phoenix/2016/phoenix-2014-T.v3.tar.gz) (39 GB)

```
PHOENIX-2014-T
├── annotations
│   │
│   └─ manual -> this contains the corpus files. Note that phoenix2016.train-complex-annotation.corpus.csv contains a more complex annotation. The evaluation scripts map this annotation back to the test protocoll
│
├── evaluation -> this contains evaluation scripts for recognition and translation. WER is calculated with the Sclite tools. ROUGE & BLEU Scores are calculated by help of scripts from google.
│
├── features
│   │
│   └─── fullFrame-210x260px -> resolution of 210x260 pixels, but they are distorted due to transmission channel particularities, to undistort stretch images to 210x300
│      ├── dev
│      ├── test
│      └── train
│ 
└── models
    │
    └─── languageModels
```
