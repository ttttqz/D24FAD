# D²4FAD: Dual Distillation for Few-Shot Anomaly Detection

Implementation (Official Code)

## Environment

```
pytorch == 1.9.1
torchvision == 0.10.1
numpy == 1.20.3
scipy == 1.7.1
sklearn == 1.0
PIL == 8.3.2
```

## Dataset

We compile a comprehensive benchmark dataset spanning diverse anatomical regions, lesion types, and imaging modalities. The dataset includes:

- **HIS**: Derived from Camelyon16 (breast cancer pathology)
- **LAG**: Retinal fundus images for glaucoma detection
- **APTOS**: Retinal images from diabetic retinopathy patients
- **RSNA**: Chest X-ray images with lung opacity
- **Brain Tumor**: MRI slices with gliomas and meningiomas

**Note**: Download dataset [Link coming soon]. Please organize the dataset structure as follows:

```
data/
├── HIS/
│   ├── train/
│   │   └── good/
│   └── test/
│       ├── good/
│       └── bad/
├── LAG/
├── APTOS/
├── RSNA/
└── Brain_Tumor/
```

## Train and Test the Model

Train and Test the Model We have write both training and evaluation function in the main.py, execute the following command to see the training and evaluation results.

```bash
python main.py
```

## Reference

```bibtex
@misc{dong2026dualdistillationfewshotanomaly,
      title={Dual Distillation for Few-Shot Anomaly Detection}, 
      author={Le Dong and Qinzhong Tan and Chunlei Li and Jingliang Hu and Yilei Shi and Weisheng Dong and Xiao Xiang Zhu and Lichao Mou},
      year={2026},
      eprint={2603.01713},
      archivePrefix={arXiv}
}
```
