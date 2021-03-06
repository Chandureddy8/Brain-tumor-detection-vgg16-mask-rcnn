# Brain-tumor-detection-vgg16-mask-rcnn

# Brain tumor:

![Alt Text](https://github.com/Chandureddy8/Brain-tumor-detection-vgg16-mask-rcnn/blob/main/images/download.jfif)


In medical science, an anomalous and uncontrollable cell growth inside the brain is recognised as tumor. Human brain is the most receptive part of the body. It controls muscle movements and interpretation of sensory information like sight, sound, touch, taste, pain, etc.

The human brain consists of Grey Matter (GM), White Matter (WM) and Cerebrospinal Fluid (CSF) and on the basis of factors like quantification of tissues, location of abnormalities, malfunctions & pathologies and diagnostic radiology, a presence of tumor is identified. A tumor in the brain can affect such sensory information and muscle movements or even results in more dangerous situation which includes death. Depending upon the place of commencing, tumor can be categorised into primary tumors and secondary tumors. If the tumor is originated inside the skull, then the tumor is known as primary brain tumor otherwise if the tumor‘s initiation place is somewhere else in the body and moved towards the brain, then such tumors are called secondary tumors.

Brain tumor can be of the following types-glioblastoma, sarcoma, metastatic bronchogenic carcinoma on the basis of axial plane. While some tumours such as meningioma can be easily segmented, others like gliomas and glioblastomas are much more difficult to localise. World Health Organisation (WHO) categorised gliomas into - HGG/high grade glioma/glioblastoma/IV stage /malignant & LGG/low grade glioma/II and III stage /benign. Although most of the LGG tumors have slower growth rate compared to HGG and are responsive to treatment, there is a subgroup of LGG tumors which if not diagnosed earlier and left untreated could lead to GBM. In both cases a correct treatment planning (including surgery, radiotherapy, and chemotherapy separately or in combination) becomes necessary, considering that an early and proper detection of the tumor grade can lead to a good prognosis. Survival time for a GBM (Glioblastoma Multiform) or HGG patient is very low i.e. in the range of 12 to 15 months.

![Alt Text](https://github.com/Chandureddy8/Brain-tumor-detection-vgg16-mask-rcnn/blob/main/images/493ss_getty_rf_doctor_examining_mri_scan_of_brain.jpg)

Magnetic Resonance Imaging (MRI) has become the standard non-invasive technique for brain tumor diagnosis over the last few decades, due to its improved soft tissue contrast that does not use harmful radiations unlike other methods like CT(Computed Tomography), X-ray, PET (Position Emission Tomography) scans etc. The MRI image is basically a matrix of pixels having characteristic features.

Since glioblastomas are infiltrative tumours, their borders are often fuzzy and hard to distinguish from healthy tissues. As a solution, more than one MRI modality is often employed e.g. T1 (spin-lattice relaxation), T1-contrasted (T1C), T2 (spin-spin relaxation), proton density (PD) contrast imaging, diffusion MRI (dMRI), and fluid attenuation inversion recovery (FLAIR) pulse sequences. T1-weighted images with intravenous contrast highlight the most vascular regions of the tumor (T 1C gives much more accuracy than T1.), called ‗Enhancing tumor‘ (ET), along with the ‗tumor core' (TC) that does not involve peritumoral edema. T2-weighted (T2W) and T2W-Fluid Attenuation Inversion Recovery (FLAIR) images are used to evaluate the tumor and peritumoral edema together defined as the ‗whole tumor‘ (WT). Gliomas and glioblastomas are difficult to distinguish in T1, T1c, T2 and PD. They are better identified in FLAIR modalities.

# What is transfer learning?

“We don’t learn everything from scratch when we attempt to learn new aspects or topics. We transfer and leverage our knowledge from what we have learnt in the past!”

The first thing to remember here is that, transfer learning, is not a new concept which is very specific to deep learning. There is a stark difference between the traditional approach of building and training machine learning models, and using a methodology following transfer learning principles.

![alt text](![image](https://user-images.githubusercontent.com/70929571/109481762-27beb680-7aa3-11eb-9607-becd7eeb5822.png)

Transfer learning is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. For example, knowledge gained while learning to recognize cars could apply when trying to recognize trucks. This area of research bears some relation to the long history of psychological literature on transfer of learning.

![alt text](https://miro.medium.com/max/875/1*HXX-SJCo6g-wtGF3Zpg48w.png)

# vgg16
![alt text](https://github.com/Chandureddy8/Brain-tumor-detection-vgg16-mask-rcnn/blob/main/images/clf_model.jpg)

![alt text](https://miro.medium.com/max/875/1*7bBYGK8uYE9O8kPvvX_NLQ.png)
