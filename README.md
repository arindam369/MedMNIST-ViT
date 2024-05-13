# Implementing Vision Transformer for Classifying 2D Biomedical Images
Arindam Halder, Sanghita Gharami, Priyangshu Sadhu, Pawan Kumar Singh<sup>[[0000-0002-9598-7981](https://orcid.org/0000-0002-9598-7981)]</sup>, Marcin Wozniak*<sup>[[0000-0002-9073-5347](https://orcid.org/0000-0002-9073-5347)]</sup>, Muhammad Fazal Ijaz*<sup>[[0000-0001-5206-272X](https://orcid.org/0000-0001-5206-272X)]</sup>

(* Correspondence Authors)


### Directory Structure


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
``` git clone https://github.com/arindam369/MedMNIST-ViT.git ``` ``` cd MedMNIST-ViT ```

*Run BloodMNIST.ipynb, BreastMNIST.ipynb, PathMNIST.ipynb, RetinaMNIST.ipynb files to view the result of our model on the respective datasets. ``gradcam`` directory contains the codes of visualising GradCAM Analysis on the respective datasets using our proposed model. Use the images of the ``images`` directory to perform GradCAM Analysis*



## Datasets
The datasets utilized in this study can be found at: [albertvillanova/medmnist-v2](https://huggingface.co/datasets/albertvillanova/medmnist-v2) | [MedMNIST](https://medmnist.com)