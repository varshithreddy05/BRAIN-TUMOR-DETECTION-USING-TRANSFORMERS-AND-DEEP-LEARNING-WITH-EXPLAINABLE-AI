# 🧠 BRAIN-TUMOR-DETECTION-USING-TRANSFORMERS-AND-DEEP-LEARNING-WITH-EXPLAINABLE-AI


🔍 Project Overview

Detects brain tumors from MRI scans using cutting-edge deep learning models.
Compares performance of EfficientNetB0 and Vision Transformers (ViT).
Integrates Explainable AI (XAI) tools like Grad-CAM and LRP for interpretability.

🛠️ Key Features

High Accuracy: EfficientNetB0 achieved 97.86% accuracy and 0.9800 AUC-ROC.
Explainability: Heatmaps & attention maps show which regions influenced predictions.
Efficient Models: Uses fewer parameters than VGG16 but delivers better results.
ViT: Identifies complex and subtle features missed by traditional models.
XAI Boost: Interpretability added with no performance drop.

🧪 Dataset

3,274 MRI images of tumorous and non-tumorous brain scans.
Preprocessed with resizing and format normalization.

📊 Results Summary


Model	                Accuracy	   AUC-ROC	     Params
EfficientNetB0	      97.86%	     0.9800	        16.7M
ViT	                  87.16%	     0.9315	        10.9M
VGG16	                74.62%	     0.9060	        17.9M
Hybrid (Eff+ViT)	    74.62%       0.9292	        11.2M

✅ Key Takeaways

EfficientNetB0 is best for clinical deployment (high accuracy + low compute).
ViT and Hybrid models are promising but need further tuning.
Explainability does not reduce performance — it adds trust and transparency.
Larger models (e.g., VGG16) guarantees better performance with combining with xai due sequential architecture,
which makes it easier to trace and visualize feature activations and relevance propagation layer-by-layer.
🧠 Conclusion

This project proves that deep learning, paired with explainable AI, can improve brain tumor diagnosis by providing accurate, efficient, and trustworthy predictions from MRI scans.

