I am a Data Science Master student at Ecole Polytechnique and HEC Paris graduating in 2021, passionate about solving business problems using data.

My master’s program in Data Science allowed me to gain a strong theoretical background in Machine Learning, Deep Learning, Analytics and Statistics. I had the chance to apply this background through various data projects and through a 5-month internship at Untienots last spring. Interning at Untienots confirmed my interest in data science and allowed me to enhance my technical skills and to work in a big data environment with the constraints related to real-life datasets and computing resources. Through all these experiences, I learned to quickly adapt myself to new situations and to continuously update my technical skills.



## PORTFOLIO

---

### Identify the mood of a music track using Deep Learning

<details><summary> Project description </summary><p>

**Goal**: classify the mood of a given song into 4 classes (happy/angry/sad/relaxed)

**Data:** 30s-previews in mp3 downloaded from the API of Spotify, mood annotations from [last.fm dataset](http://millionsongdataset.com/lastfm/) 

**Methodology:** 
- **Data collection**: download last.fm dataset and filter songs with mood of interest, download 30s-previews of the songs from Spotify
- **Data Preparation**: convert mp3 into JPG spectrograms
- **Modeling**: Resnet18 CNN model (not pretrained) on the generated spectograms
- **Web application**: web application where you can enter the name of a song and get the mood predicted by the model

</p></details>



[Github repository](https://github.com/aichabokbot/music_mood_classification)
| [Slides](/pdf/Music.pdf)

---
### Improve productivity on construction sites using Computer Vision

<details><summary> Project description </summary><p>
  
**Data:** data of a construction player in France, which consists of 2,000 pictures taken by 10 cameras deployed in 6 construction sites. The pictures have the following annotations: workers (Bounding box), vertical formworks (Polygon), concrete pump (Polygon)

**Goal:** develop an automatic monitoring solution to improve productivity on construction sites

**Methodology:** 
- **Object detection**: build a model that detects workers, formworks and pumps on images using Mask R-CNN architecture with weights pretrained on COCO dataset
- **Analytics**: use output of detection model to identify construction tasks, measure time spent and workers involved in them and compute productivity KPIs
- **Optimization**: provide recommendations to avoid unproductive scheduling of tasks

</p></details>

[Github repository](https://github.com/aichabokbot/construction_site_optimization)
| [Slides](/pdf/Chronsite.pdf)

---
###  Diagnose rare diseases 
<details><summary> Project description </summary><p>
  
**Data:** data of Amedes, German group of medical centers. There are four types of: patient data (age and sex of the patient), lab test results, doctor's handwritten notes, diagnostic data (intermediary and final diagnosis of the patient)

**Goal**: extract patterns from the data and use it to build a machine learning model that can detect four specific rare diseases among patients (diseases with <1% of prevalence)

**Methodology:** 
- **Data Cleaning**: clean and homogenize doctors' notes, impute missing values in diagnostic data
- **Pattern recognition**: research common symptoms and test results used to diagnose the diseases with the most frequent symptoms, test results and co-morbidities among patients with the disease. Create features accordingly
- **Modeling**: build classification model to predict patient who are likely to have the disease

</p></details>

[Github repository](https://github.com/aichabokbot/rare_disease_detection)
| [Slides](/pdf/Amedes.pdf)



