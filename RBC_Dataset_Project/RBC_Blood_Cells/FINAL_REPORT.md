# RBC Blood Cells Dataset - Final Report

## Dataset Summary

Total images: 586
Train: 410 images (70%)
Validation: 117 images (20%)
Test: 59 images (10%)

## Classes

The final dataset contains 12 classes numbered 0 to 11.

0: Normal cell
1: Macrocyte
2: Microcyte
3: Spherocyte
4: Target cell
5: Stomatocyte
6: Ovalocyte
7: Teardrop
8: Burr cell
9: Schistocyte
10: uncategorised
11: Hypochromia

## Class Distribution

0 | Normal cell | Train=3772 | Val=1043 | Test=481 | Total=5296
1 | Macrocyte | Train=506 | Val=110 | Test=43 | Total=659
2 | Microcyte | Train=322 | Val=71 | Test=31 | Total=424
3 | Spherocyte | Train=2719 | Val=365 | Test=62 | Total=3146
4 | Target cell | Train=1758 | Val=409 | Test=162 | Total=2329
5 | Stomatocyte | Train=1252 | Val=374 | Test=173 | Total=1799
6 | Ovalocyte | Train=1353 | Val=387 | Test=185 | Total=1925
7 | Teardrop | Train=224 | Val=42 | Test=23 | Total=289
8 | Burr cell | Train=590 | Val=86 | Test=22 | Total=698
9 | Schistocyte | Train=601 | Val=163 | Test=75 | Total=839
10 | uncategorised | Train=79 | Val=13 | Test=5 | Total=97
11 | Hypochromia | Train=666 | Val=194 | Test=104 | Total=964

## Clean Images

The clean images are stored in RBC_Blood_Cells/images/.

They are numbered from 1.jpg to 586.jpg.

## Annotation Format

YOLO Object Detection format:

Class X_center Y_center Width Height

Coordinates are normalized between 0 and 1.

## Image / Label Pairing

Each image keeps the annotation file with the same number.

Example:

1.jpg <-> 1.txt
2.jpg <-> 2.txt
3.jpg <-> 3.txt

## Images With Boxes

The original Images_With_Boxes folder was kept as the annotation reference.

## Split Method

The 586 clean images were divided into Train, Validation, and Test using a class-aware image-level split.

The complete image and annotation pair always remains together.

## Class 12

Class 12 was removed from the final class configuration.

The final dataset contains classes 0 through 11.
