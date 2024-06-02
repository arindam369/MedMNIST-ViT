[![DOI](https://zenodo.org/badge/DOI/10.1038/s41598-024-63094-9.svg)](https://doi.org/10.1038/s41598-024-63094-9)

# Implementing Vision Transformer for Classifying 2D Biomedical Images
Arindam Halder, Sanghita Gharami, Priyangshu Sadhu, Pawan Kumar Singh<sup>[[0000-0002-9598-7981](https://orcid.org/0000-0002-9598-7981)]</sup>, Marcin Wozniak*<sup>[[0000-0002-9073-5347](https://orcid.org/0000-0002-9073-5347)]</sup>, Muhammad Fazal Ijaz*<sup>[[0000-0001-5206-272X](https://orcid.org/0000-0001-5206-272X)]</sup>

(* Corresponding Authors)

This is the official implementation of the paper, "[Implementing vision transformer for classifying 2D biomedical images](https://www.nature.com/articles/s41598-024-63094-9)" published in "Scientific Reports (Nature)"


## Directory Structure


```

+-- gradcam
|   +-- .
|   +-- GradCam_BloodMNIST.ipynb
|   +-- GradCam_BreastMNIST.ipynb
|   +-- GradCam_PathMNIST.ipynb
|   +-- GradCam_RetinaMNIST.ipynb
+-- images
+-- BloodMNIST.ipynb
+-- BreastMNIST.ipynb
+-- PathMNIST.ipynb
+-- RetinaMNIST.ipynb

```
**Note:** ``images`` folder contains images of various classes of all the four datasets (BloodMNIST, BreastMNIST, PathMNIST, RetinaMNIST) used

## Running Codes

**Clone the project repository:**
``` git clone https://github.com/arindam369/MedMNIST-ViT.git ``` &nbsp; ``` cd MedMNIST-ViT ```

*Run BloodMNIST.ipynb, BreastMNIST.ipynb, PathMNIST.ipynb, RetinaMNIST.ipynb files to view the result of our model on the respective datasets. ``gradcam`` directory contains the codes of visualising GradCAM Analysis on the respective datasets using our proposed model. Use the images of the ``images`` directory to perform GradCAM Analysis.*



## Datasets
The datasets utilized in this study can be found at: [albertvillanova/medmnist-v2](https://huggingface.co/datasets/albertvillanova/medmnist-v2) | [MedMNIST](https://medmnist.com)


## Citation
If you find this work helpful, consider citing our study:
```
@article{Halder2024,
   title={Implementing vision transformer for classifying 2D biomedical images},
   author={Halder, Arindam and Gharami, Sanghita and Sadhu, Priyangshu and Singh, Pawan Kumar and Woźniak, Marcin and Ijaz, Muhammad Fazal},
   journal={Scientific Reports},
   volume={14},
   number={1},
   pages={12567},
   year={2024},
   month={may},
   day={31},
   issn={2045-2322},
   doi={10.1038/s41598-024-63094-9},
   url={https://doi.org/10.1038/s41598-024-63094-9}
}
```
