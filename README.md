# Bridging-Language-Barriers-in-Fact-Verification
This project addresses the challenge of cross-lingual fact verification, where claims in one language must be verified using evidence in another. 

We present a baseline system using the XFEVER dataset, fine-tuning three
transformer models: XLM-RoBERTa Base, XLM-RoBERTa Large, and mDeBERTa-v3 Base to classify claims as SUPPORTS, REFUTES, or NOT ENOUGH INFORMATION. We later incorporate an XNLI-based inference model for Wikipedia-supported fact verification. Our best model, mDeBERTa-v3 Base, achieves 63.49% accuracy and 0.621 weighted F1-score on the test set. The system demonstrates the potential of multilingual AI to reduce language barriers in fact-checking, particularly for global misinformation detection, while highlighting challenges in low-resource languages.
