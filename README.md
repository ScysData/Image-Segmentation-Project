# Image Segmentation Project: A Comprehensive Study of Modern Segmentation Architectures on Satellite Waterbodies image

A comprehensive deep learning project showcasing the different image segmentation architectures from classic U-Net to Nested Unet (Unet++) to state-of-the-art vision transformer models, implemented for water body detection in satellite images.

## Project Overview

This project demonstrates advanced computer vision and deep learning expertise through the implementation and comparison of three cutting-edge image segmentation architectures. The progression from traditional CNN-based approaches to modern transformer architectures showcases a deep understanding of the evolution in computer vision methodologies.

### Three-Part Study

#### **Part 1: U-Net from Scratch** 
Built Classic encoder-decoder architecture from scratch, demonstrating foundational understanding of semantic segmentation

#### **Part 2: U-Net++ with EfficientNet**
Advanced nested U-Net architecture with state-of-the-art encoder and transfer learning for improved performance

#### **Part 3: SegFormer (Transformer-based)**
Cutting-edge vision transformer approach to explore the latest advancement in image segmentation

### General Highlights
- **Progressive Complexity**: From basic CNN to advanced transformer architectures
- **Custom Implementations**: Built from scratch to demonstrate architectural understanding
- **Modern Techniques**: Integration of latest research in computer vision

## Architectures Applied

### Part 1: Custom U-Net Implementation
![image](https://github.com/user-attachments/assets/3b3fb5b6-1a9a-4d89-bc48-838b9c567bb2)

reference : [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)

**Features:**
- PyTorch implementation without using pre-built API framework for U-Net
- Custom convolutional blocks with batch normalization
- Skip connections for feature preservation


### Part 2: U-Net++ with EfficientNet Encoder

Reference:[UNet++: A Nested U-Net Architecture for Medical Image Segmentation](https://arxiv.org/abs/1807.10165)
![image](https://github.com/user-attachments/assets/76ba7c7d-0ad4-47f1-a9ba-9b4cfb09e59f)


**Features:**
- Nested U-Net architecture with dense skip pathways
- EfficientNet backbone for improved feature extraction
- Transfer learning from ImageNet pre-trained weights
- Enhanced gradient flow through nested connections

### Part 3: SegFormer (Vision Transformer)

![image](https://github.com/user-attachments/assets/5d1ec429-30b8-417b-910f-17c1d810accc)
reference: [SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers](https://arxiv.org/abs/1807.10165)

**Features:**
- Transformer-based encoder without positional encoding
- light-weight decoder for simplicity and efficiency


<!---## 📊 Comparative Analysis

### Architecture Comparison

| Model | Parameters | FLOPs | IoU Score | Training Time | Key Advantage |
|-------|------------|-------|-----------|---------------|---------------|
| U-Net | ~31M | 124G | 0.85 | Baseline | Simple, interpretable |
| U-Net++ | ~44M | 152G | 0.89 | +25% | Dense connections |
| SegFormer | ~64M | 180G | 0.92 | +40% | Global context |
-->

### Performance Metrics
- **Dice Coefficient**: Overlap similarity measurement  
- **Pixel Accuracy**: Per-pixel classification accuracy


##  Technical Implementation

### Technologies Stack

#### Core Frameworks
- **Computer Vision Modules**: PyTorch, SegmentationModels, Transformers (Hugging Face), OpenCV, Albumentations


##  Project Structure

```
Image-Segmentation-Project/
├── part1_unet_scratch/          # U-Net from scratch implementation
│   ├── models/                  # Trained U-Net Model
│   ├── logs/                    # Training Logs
│   └── notebooks/              # Analysis notebooks
│
├── part2_unet_plus/             # U-Net++ with EfficientNet
│   ├── models/                  # Trained U-Net++ Model
│   ├── logs/                    # Training Logs
│   └── notebooks/              # Analysis notebooks
│
├── part3_segformer/             # SegFormer transformer implementation
│   ├── models/                  # Trained SegFormer Model
│   ├── logs/                    # Training Logs
│   └── notebooks/               # Analysis notebooks
│
├── requirements.txt             # Project dependencies
└── README.md                    # Project documentation
```

<!---##  Key Results and Demonstrations-->


##  Citations & References

```bibtex
@article{ronneberger2015unet,
  title={U-net: Convolutional networks for biomedical image segmentation},
  author={Ronneberger, Olaf and Fischer, Philipp and Brox, Thomas},
  journal={MICCAI},
  year={2015}
}

@article{zhou2018unet++,
  title={Unet++: A nested u-net architecture for medical image segmentation},
  author={Zhou, Zongwei and Rahman Siddiquee, Md Mahfuzur and Tajbakhsh, Nima and Liang, Jianming},
  journal={Deep learning in medical image analysis and multimodal learning for clinical decision support},
  year={2018}
}

@article{xie2021segformer,
  title={SegFormer: Simple and efficient design for semantic segmentation with transformers},
  author={Xie, Enze and Wang, Wenhai and Yu, Zhiding and Anandkumar, Anima and Alvarez, Jose M and Luo, Ping},
  journal={Advances in Neural Information Processing Systems},
  year={2021}
}
```

## 📧 Contact

**[Samson Chan]** - Data Scientist 
📧 Email: samsonc9211@gmail.com
💼 LinkedIn: [Samson Chan](www.linkedin.com/in/samson-chan-data-science)
🐱 GitHub: [@ScysData](https://github.com/ScysData)  


