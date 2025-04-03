# Art Generation with Neural Style Transfer

## Overview
This project implements the Neural Style Transfer (NST) method proposed by **Gatys et al. (2015)** using a Jupyter Notebook. NST is a deep learning technique that applies the artistic style of one image (style image) to another image (content image) to generate an artwork that retains the content but adopts the style of the reference painting.

## Methodology
The implementation follows the original **Gatys et al. (2015)** approach:
- Uses a **pre-trained convolutional neural network (CNN)** (such as VGG19) to extract image features.
- Defines a **content loss** to preserve the structure of the content image.
- Defines a **style loss** using Gram matrices to transfer the artistic style.
- Optimizes a generated image using gradient descent to minimize the total loss.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install tensorflow numpy matplotlib pillow scipy PIL 
```

## How to Use
1. Clone this repository:

   ```bash
   git clone https://github.com/talebsidelmoktar/Art_Generation_with_Neural_Style_Transfer.git
   cd Art_Generation_with_Neural_Style_Transfer
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Load your content and style images in the notebook.
4. Run the cells to process the images and generate an artistic image.

## Results
The final generated image combines the content from the **content image** and the artistic style from the **style image**, creating a visually appealing artwork.

## References
- **Gatys, L. A., Ecker, A. S., & Bethge, M. (2015).** *A Neural Algorithm of Artistic Style.* arXiv:1508.06576. [(Paper)](https://arxiv.org/abs/1508.06576)
- **Harish Narayanan.** *Convolutional Neural Networks for Artistic Style Transfer.* [(Article)](https://harishnarayanan.org/writing/artistic-style-transfer/)
- **Log0.** *TensorFlow Implementation of "A Neural Algorithm of Artistic Style".* [(Blog)](https://www.chioka.in/tensorflow-implementation-neural-algorithm-of-artistic-style)
- **Karen Simonyan & Andrew Zisserman (2015).** *Very Deep Convolutional Networks for Large-Scale Image Recognition.* [(Paper)](https://arxiv.org/pdf/1409.1556)
- **MatConvNet.** *A MATLAB toolbox for deep learning.* [(Pretrained Models)](https://www.vlfeat.org/matconvnet/pretrained/)

## License
This project is open-source under the MIT License.

