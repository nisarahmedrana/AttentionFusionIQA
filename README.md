# AttentionFusionIQA: Two-Stream Attention-based Image Quality Assessment Model
AttentionFusionIQA is an innovative and state-of-the-art image quality assessment (IQA) model designed to objectively evaluate the quality of images. This model leverages the power of attention mechanisms to focus on the most important regions within an image, enabling more accurate and human-perceptually aligned quality predictions.

##Key Features:

1. **Two-Stream Architecture:** AttentionFusionIQA employs a unique two-stream architecture that combines features extracted from two distinct backbones, enhancing the model's ability to capture meaningful image details effectively.

2. **Spatial and Channel Attention:** The model incorporates spatial and channel attention mechanisms to provide higher weights to the region of interest in the image. This attention-driven approach ensures more precise and relevant quality predictions.

3. **Quality-Aware Loss Function:** AttentionFusionIQA utilizes a quality-aware loss function that combines prediction error and correlation-based loss to optimize image quality predictions, leading to superior performance.

4. **Evaluation Metrics:** The model is rigorously evaluated using standard correlation metrics such as Pearson correlation coefficient (PLCC), Spearman rank-order correlation coefficient (SROCC), and Kendall's rank-order correlation coefficient (KROCC) to ensure reliable and meaningful results.

##Benefits:

- Enhanced Image Quality Assessment: AttentionFusionIQA offers more accurate and robust image quality predictions, aligning closely with human perceptual judgment.
- Generalizability: The model demonstrates excellent generalization capabilities by effectively handling authentic and synthetic distortion datasets.
- Visual Attention Visualization: AttentionFusionIQA provides attention maps through GradCAM, allowing users to visualize the regions of interest that influence the predictions.

##Usage:

The code repository contains the implementation of AttentionFusionIQA in Python, along with necessary instructions and datasets for training and evaluation. Researchers and developers can utilize this model for various image quality assessment tasks, including image processing, content-aware algorithms, and image enhancement applications.

**Dependencies:**

AttentionFusionIQA requires Python 3.x and the following libraries: TensorFlow, Keras, NumPy, Matplotlib, and scikit-learn.

**License:**

This project is open-source under the [MIT License]([link-to-license-file](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)).

**Contributions:**

We welcome contributions from the community to enhance and improve AttentionFusionIQA.

**Citation:**

If you use AttentionFusionIQA in your research or work, kindly cite our paper [Blind Image Quality Assessment Using Multi-Stream Architecture with Spatial and Channel Attention](https://arxiv.org/abs/2307.09857) in your publications.

**Disclaimer:**

AttentionFusionIQA is a research project and should be used for academic and non-commercial purposes only. We are not responsible for any misuse or any damages that may arise from the use of this model.

For any queries or support, please feel free to reach out to us at [nisarahmedrana@yahoo.com](nisarahmedrana@yahoo.com).

**Let's improve image quality assessment with AttentionFusionIQA!**
