# centerNet-3-classes

## New Dataset
A filtered dataset containing only person, car, truck, cat and dog was created using `createDataset.py`.

## Changing detector output
The detector output(CenterNet) was modified to remove all reduant classes other than the desired ones. The changes are in `base_detector.py`. The changes are in lines 134 - 140.

## Mix precision training
The file `base_trainer.py` has been modified to accommodate mix precision training.
