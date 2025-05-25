# Apple Defect Detection
- Identifying the Apple defects using various Machine Learning Model initially we used MobileNetV2


### File Structure
```bash
/content/
├── train/
│   ├── good/
│   └── bad/
├── test/
│   ├── good/
│   └── bad/
```

# Alternative ML Models for Apple Defect Detection

| Model             | Type               | When to Use                                           | Accuracy Potential |
|------------------|--------------------|-------------------------------------------------------|--------------------|
| ResNet50          | CNN (Deep)         | Stronger than MobileNet for more complex patterns     | ★★★★☆              |
| EfficientNet      | CNN (Very Deep)    | State-of-the-art on ImageNet                          | ★★★★★              |
| XGBoost           | Traditional ML     | When using handcrafted features from images           | ★★★☆☆              |
| SVM + HOG         | Classical ML       | Lightweight, but requires feature engineering         | ★★☆☆☆              |
| YOLOv5/YOLOv8     | Object Detection   | If you want bounding boxes of apple defects           | ★★★★★              |




# Credits
- Kaggle Dataset [Apple Quality Analysis Dataset](https://www.kaggle.com/datasets/ankita20chaudhary/apple-quality-analysis-dataset/data)
