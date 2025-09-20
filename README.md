# emotion_supplement

---

## 🤝 Collaboration Invitation

If you're interested in collaborating on the analysis of **facial emotion expressions** or other **psychophysiological variables** (e.g., EEG, SCR), feel free to get in touch. I'm open to interdisciplinary partnerships and exploratory analysis projects.

📧 Contact: **liina.juuse@ut.ee**


# 📘 Supplementary Information

## Comparing Human and Machine Emotion Recognition in Mimicked and Suppressed Facial Expression Conditions  
**Liina Juuse, Kristian Pentus, Kairi Kreegipuu, Jüri Allik**

---

## 🔍 Extended Summary

This project investigates how well **human observers** and a **machine learning-based emotion recognition system (FaceReader)** perform under conditions where emotional expressions are **mimicked** or **suppressed** — i.e., not spontaneously expressed. These cases represent more **ambiguous, strategically modulated facial cues**, which are common in real-world interactions but rarely tested in ML contexts.

We compare recognition accuracy across six basic emotions:  
**Anger, Disgust, Fear, Happiness, Sadness, and Surprise.**

---

## 📊 Key Results

- Human observers achieved an overall accuracy of **54.4%**, performing best on **happiness (82.7%)** and worst on **fear (19.2%)**.
- FaceReader reached **37.4%** overall accuracy, with high performance for **happiness (96.9%)** but poor detection of **fear (4%)** and **disgust (11.3%)**.

**Significant differences were found:**
- **Fear**: *t*(3492) = 9.32, *p* < .001, *d* = 1.33  
- **Disgust**: *t*(3492) = 19.94, *p* < .001, *d* = 2.86

> Both systems struggled to distinguish **fear** from **surprise**, suggesting potential limitations in expressive clarity or model sensitivity for these categories.

---

## ⚙️ Methods Overview

- **Sample 1**: Facial expression data recorded under instructed mimic/suppression tasks. Multimodal data includes video, EEG, SCR, and self-reports.
- **Sample 2**: Independent observers (**N = 223**) rated the expressions on 7-label categorical scales.
- **Sample 3**: FaceReader and DeepFace were used for automated emotion estimation (*analysis ongoing for DeepFace*).

---

## 💡 Future Directions

- Extend comparisons to **deep learning models** (e.g., DeepFace, AffectNet-based CNNs) to test whether they can better handle **subtle or ambiguous expressions**.
- Analyze **individual differences** in emotion recognition (e.g., personality, empathy) and their alignment with ML outputs.
- Examine **temporal dynamics** in recognition using **multimodal biosignal data** (EEG, SCR).

---

## 📎 Downloads & Resources

- 📄 [Full Poster PDF](#)
- 📁 [Example Stimuli & Task Description](#)
- 📊 [Cleaned Dataset Snapshot (.csv)](#)
- 📚 [Full Reference List (APA)](#)

---

## 📧 Contact

**Liina Juuse**  
📧 liina.juuse@ut.ee  
🏫 Institute of Psychology, University of Tartu
