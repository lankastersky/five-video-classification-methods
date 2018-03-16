# Detection of ads in video (classification of ads/non-ads)
Fork from https://github.com/harvitronix/five-video-classification-methods

## Data preparation
Create next folders:
- data/train/ads
- data/train/nonads
- data/test/ads
- data/test/nonads

Use UCF101 as nonads
- see [here](https://github.com/harvitronix/five-video-classification-methods) how to prepare data

Use Youtube-8M from vudoku as ads
- `2_extract_files.py`
- `extract_features.py`
- `train.py`
- `demo.py`

Results:
- loss: 0.4179 - acc: 0.8594 - val_loss: 0.3393 - val_acc: 0.9617
