# Detection of ads in video (classification of ads/non-ads)
Fork from https://github.com/harvitronix/five-video-classification-methods

## Data preparation
Create next folders:
- data/train/ads
- data/train/nonads
- data/test/ads
- data/test/nonads

- see [here](https://github.com/harvitronix/five-video-classification-methods) how to prepare data

Use Youtube-8M as dataset with advertising videos
- `2_extract_files.py`
- `extract_features.py`
- `train.py`
- `demo.py`

Results:
- loss: 0.4834 - acc: 0.8125 - val_loss: 0.4486 - val_acc: 0.8891 (epoch: 30)
