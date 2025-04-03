# Effects-of-Augmentation

# 100 epochs and SGD

| Model       | Precision (B) | Recall (B) | mAP50 (B) | mAP50-95 (B) |
|------------|-------------|-----------|-----------|-------------|
| YOLOv11     | 0.548      | 0.61    | 0.574    | 0.573      |
| YOLO v11 Augmented | 0.692      | 0.759       | 0.771       | 0.769         |

# 200 Epochs and SGD

| Model       | Precision (B) | Recall (B) | mAP50 (B) | mAP50-95 (B) |
|------------|-------------|-----------|-----------|-------------|
| YOLOv11     | 0.547     | 0.61    | 0.594   | 0.593      |
| YOLO v11 Augmented | 0.736      | 0.786      | 0.815       | 0.815         |

# 200 Epochs and Adam

| Model       | Precision (B) | Recall (B) | mAP50 (B) | mAP50-95 (B) |
|------------|-------------|-----------|-----------|-------------|
| YOLOv11     | 0.2      |  1   | 0.208  |  0.208    |
| YOLO v11 Augmented | 0.587     | 0.723      | 0.698        | 0.691         |

                     
                 
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
