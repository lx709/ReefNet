# ReefNet

# 1. Images and Labelset
```
./data/
|
├── sources.txt <!-- List of sources -->
├── CoralNet
│   ├── README.md <!-- Description about the dataset -->
│   ├── Labelmapping.csv <!-- Store class code, full class name, matched worm class name -->
│   ├── source_1  <!-- Per-source folder -->
│       ├── Images/
│       ├── labels.csv
│   ...
├── SeaView XL
│   ├── README.md <!-- Description about the dataset -->
│   ├── Images/
│   ├── labels.csv
```

# 2. Coral Labeling


# 3. Coral Classification Model
Useful deep learning libraries:

Timm: https://timm.fast.ai/

Reference project: https://github.com/faixan-khan/FishNet

# 3. Segment Labeling

# 4. Segmentation model training
Finetuning SAM on our sele-collected labels.

SAM: https://github.com/facebookresearch/segment-anything
