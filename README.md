# AI-Driven-Emotional-Intelligence-Monitor-for-Mental-Health

An Artificial Intelligence and Deep Learning project designed to assist clinical professionals by providing objective, quantitative data on patient emotional states. The system uses computer vision to track facial micro-expressions over time.
1. Deep Learning Architecture: Engineered a custom Convolutional Neural Network (CNN) using PyTorch/Keras, featuring double-convolution blocks and Global Average Pooling (GAP) to classify seven universal emotions.

2. Real-Time Processing: Developed a clinical dashboard using Streamlit and OpenCV, incorporating CLAHE (Contrast Limited Adaptive Histogram Equalization) to ensure robust facial detection across diverse lighting environments.

3. Data Strategy: Addressed class imbalance within the FER-2013 dataset using a WeightedRandomSampler, achieving a test accuracy of 65.9%, which significantly outperformed the baseline for "in-the-wild" facial expression recognition.
