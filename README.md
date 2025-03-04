# Effects-of-Augmentation


| Model       | Precision (B) | Recall (B) | mAP50 (B) | mAP50-95 (B) |
|------------|-------------|-----------|-----------|-------------|
| YOLOv11     | 0.9799      | 0.2054    | 0.2153    | 0.1889      |
| YOLO v11 Augmented | 0.9999909083279813       | 0.99999       | 0.995       | 0.9949999999999999         |


# Size Comparison of Each Class

| Data       | 0 | 1 | 2 | 3 |  4 |
|------------|-------------|-----------|-----------|-------------|-------------|
| Original     | 25813      | 2443    | 5292    | 873      | 708      |
| Augmented     | 25813      | 12215    | 9314    | 4851      | 3936      |


# Methods use for Augmentation

1) Flip: Horizontal and Vertical
2) Rotation: Between -15 to +15 Degrees
3) Blur: Upto 2.5px
4) Noise: Upto 0.1% of pixels
5) Brightness: -15 to +15%
