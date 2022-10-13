# Thorax-Disease-Detection-using-X-ray-Images

Chest X-ray exams are one of the most frequent and cost-effective medical imaging examinations available. However, clinical diagnosis of a chest X-ray can be challenging and sometimes more difficult than diagnosis via chest CT imaging. The lack of large publicly available datasets with annotations means it is still very difficult, if not impossible, to achieve clinically relevant computer-aided detection and diagnosis (CAD) in real world medical sites with chest X-rays. One major hurdle in creating large X-ray image datasets is the lack resources for labeling so many images. This NIH Chest X-ray Dataset is comprised of X-ray images with disease labels from unique patients. To create these labels, the authors used Natural Language Processing to text-mine disease classifications from the associated radiological reports.

The 14 diseases labeled in this dataset include atelectasis, consolidation, infiltration, pneumothorax, edema, emphysema, fibrosis, effusion, pneumonia, pleural thickening, cardiomegaly, nodule, mass and hernia and 'No finding'

This project uses deep convolutional neural networks (CNN) to: (1) detect and (2) localize the 14 thoracic pathologies present in the NIH Chest X-ray dataset. Our approach is to develop a multi-label CNN using the network architectures from previous works as baselines, to detect and visualize the selected diseases. We also use simpler feed forward network to incorporate patient information and compare results against the CNN.

We have a csv file (sample.csv) which consists of the following column -  <br>
● Image Index: File name <br>
● Finding Labels: Disease type (Class label)  <br>
● Follow-up #  <br>
● Patient ID  <br>
● Patient Age  <br>
● Patient Gender  <br>
● View Position: X-ray orientation <br> 
● OriginalImageWidth  <br>
● OriginalImageHeight  <br>
● OriginalImagePixelSpacing_x <br> 
● Original Image Pixel Spacing y <br>

Dataset available here : https://www.kaggle.com/datasets/nih-chest-xrays/data


