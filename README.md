# ArcticIce-Segmentation
Mapping Arctic Sea Ice from Satellite Radar. A CNN (U-Net) vs a Simple Baseline 

Planned Worflow:
Downloads radar images and their matching human charts.
Splits the scenes into train, validation and test sets.
Builds a baseline that classifies each pixel with a simple heuristic, and score it on the test scenes.
Trains a U-Net CNN (kernel/filter & pooling layers) on the training scenes and score it on the same test scenes, so the comparison is fair.
Analyses where it fails, then build the frontend and Dockerise.
