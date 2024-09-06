    Insightface with Face Analysis - Face detector and Recognizer Model:
        Architecture: Optimized ResNet or MobileFaceNet with ArcFace loss
        Accuracy: 100.00%
        Cross-Validation Mean Score: 0.9961
        Precision, Recall, F1-Score: 1.00 for all classes
        Confusion Matrix: Perfect classification with no misclassifications
        Strengths: Extremely high accuracy and perfect classification
        Limitations: May not generalize well to very different datasets without further tuning

    Face Recognition - Detector and Recognizer Model:
        Architecture: Combination of face detection and recognition techniques
        Accuracy: 99.00%
        Cross-Validation Mean Score: 0.9945
        Precision, Recall, F1-Score: Generally high but varies across classes (0.97 to 1.00)
        Strengths: High overall accuracy and performance
        Limitations: Slightly less robust compared to InsightFace

    FaceNet with MTCNN - Face Detector and Recognizer Model:
        Architecture: Uses MTCNN for face detection and FaceNet for face recognition
        Accuracy: 54.00%
        Cross-Validation Mean Score: 0.4690
        Precision, Recall, F1-Score: Vary significantly (0.00 to 1.00), with some classes performing poorly
        Strengths: Effective in detecting faces under challenging conditions
        Limitations: Lower overall accuracy and inconsistent performance across classes

    Arcface with MTCNN - Face Detector and Recognizer Model:
        Architecture: Uses MTCNN for face detection and Arcface for face recognition
        Accuracy: 97.55%
        Cross-Validation Mean Score: 0.9669908635425877
        Classification Report:
            Precision, Recall, F1-Score: Generally high, with precision and recall close to 97% for most classes
        Confusion Matrix: Shows good performance with some variations in individual classes
        Strengths: Balances face detection and recognition effectively, good performance metrics overall
        Limitations: Performance variations in specific classes

Comparative Summary:

    Accuracy: Highest with Face Analysis - InsightFace (100.00%), middle with Final Model (97.55%) and Face Recognition - Detector and Recognizer (99.00%), lowest with FaceNet with MTCNN (54.00%)
    Precision and Recall: Best with InsightFace (1.00 for all classes), high with Final Model and Detector and Recognizer, lowest with FaceNet with MTCNN
    Dataset Details: 9 classes, 200 images per class, 1,800 total images
