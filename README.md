# NewIdea Playground

## Running
You need to [download](https://figshare.com/articles/dataset/TIMIT_zip/5802597) and unzip the TIMIT dataset into the root folder of this repo.

Some additional pip dependencies such as `whisper`, `audiomentations`, `soundfile` are also required.

## Contents
### blankout_test
**blankout_test.ipynb**: The actual blankout test which offers two augmentations currently: 1 setting audio signal to zero; 2 applying a composed audio augmentation from `audiomentations`.
**aug_test.ipynb**: Initial tests to choose the right audio augmentations combi.

### transcripts_comparison
Initial rendering tests to compare 2 rows of transcripts: ground truth and whisper generated. Can also be used to generate and compare transcripts between all available whisper models.