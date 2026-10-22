# 🌱 Smart Agro — AI-Powered Crop Recommendation System

**Intelligent agriculture through machine learning, soil image analysis, and data-driven crop recommendations.**

An AI-based crop recommendation project designed to help identify suitable crops using soil-related information and environmental conditions. The system combines image classification and machine learning with a web interface to make agricultural insights more accessible.

<p align="center">
  <a href="https://github.com/venkat24-dev/Smart-Agro-Crop-Recommendation-System">
    <strong>💻 View Source Code</strong>
  </a>
  &nbsp; • &nbsp;
  <a href="smart%20crop%20agro%20system%20assests/IEEE_Conference_Smart%20Agro%20System%20for%20Crop%20Recommendation.pdf">
    <strong>📄 Read Conference Paper</strong>
  </a>
  &nbsp; • &nbsp;
  <a href="smart%20crop%20agro%20system%20assests/ISAA2026_Presentation.pptx">
    <strong>🎤 View ISAA 2026 Presentation</strong>
  </a>
</p>

---

## 📸 Application Preview

The following screenshots illustrate the project's user interface, system architecture, and output presentation.

<table>
  <tr>
    <td align="center" width="50%">
      <strong>🖼️ Soil Image Input</strong><br><br>
      <a href="smart%20crop%20agro%20system%20assests/agro%20system%20image%20input%20ui.png">
        <img src="smart%20crop%20agro%20system%20assests/agro%20system%20image%20input%20ui.png" alt="Soil image input interface" width="100%">
      </a><br>
      <sub>Upload a soil image for the image-classification workflow.</sub>
    </td>
<td align="center" width="50%">
  <strong>🌾 Soil Parameter Input</strong><br><br>
  <a href="https://github.com/venkat24-dev/Smart-Agro-Crop-Recommendation-System/blob/main/smart%20crop%20agro%20system%20assests/agro%20system%20value%20sinput%20ui.png">
    <img
      src="https://raw.githubusercontent.com/venkat24-dev/Smart-Agro-Crop-Recommendation-System/main/smart%20crop%20agro%20system%20assests/agro%20system%20value%20sinput%20ui.png"
      alt="Smart Agro soil parameter input interface"
      width="100%"
    >
  </a><br>
  <sub>Enter soil-related values used by the crop recommendation workflow.</sub>
</td>
</tr>
<tr>
    <td align="center" width="50%">
      <strong>🏗️ System Architecture</strong><br><br>
      <a href="smart%20crop%20agro%20system%20assests/architecture%20image.png">
        <img src="smart%20crop%20agro%20system%20assests/architecture%20image.png" alt="Smart Agro system architecture" width="100%">
      </a><br>
      <sub>High-level view of the system's processing workflow.</sub>
    </td>
    <td align="center" width="50%">
      <strong>📊 Recommendation Output</strong><br><br>
      <a href="smart%20crop%20agro%20system%20assests/output%20stock%20image.png">
        <img src="smart%20crop%20agro%20system%20assests/output%20stock%20image.png" alt="Crop recommendation output visual" width="100%">
      </a><br>
      <sub>Output visual associated with the recommendation workflow.</sub>
    </td>
  </tr>
</table>

## 🔗 Project Links

- **GitHub Repository:** https://github.com/venkat24-dev/Smart-Agro-Crop-Recommendation-System
- **Conference Paper:** [Open PDF](smart%20crop%20agro%20system%20assests/IEEE_Conference_Smart%20Agro%20System%20for%20Crop%20Recommendation.pdf)
- **ISAA 2026 Presentation:** [Open PowerPoint](smart%20crop%20agro%20system%20assests/ISAA2026_Presentation.pptx)

  
## ✨ Key Highlights

- **Soil Image Classification:** CNN-based soil image classification, with 98% accuracy reported for the project.
- **Crop Recommendation:** Machine learning-based crop prediction using Random Forest and Gradient Boosting, with 96% accuracy reported for the project.
- **Top-3 Recommendations:** Presents multiple crop suggestions to support comparison and decision-making.
- **Web Application:** Provides an interface for entering soil information and viewing recommendations.
- **Data-Driven Approach:** Combines soil-related information and environmental inputs to support agricultural decision-making.
- **Research Presentation:** Project work presented at ISAA 2026, University of Nizwa, Oman.

*Reported model accuracy reflects the project's evaluation results; actual performance depends on the evaluation data and real-world conditions.*


## ⚙️ How It Works

1. **Input:** Provide a soil image and/or the soil-related values supported by the application.
2. **Image Classification:** The CNN-based component classifies the soil image.
3. **Prediction:** The crop prediction model processes the supported input features.
4. **Recommendation:** The application presents crop suggestions.
5. **Decision Support:** Users can review the recommendations as inputs to agricultural planning.

## 🧠 Machine Learning Approach

| Component | Method | Reported Accuracy |
|---|---|---:|
| Soil image classification | Convolutional Neural Network (CNN) | 98% |
| Crop prediction | Random Forest + Gradient Boosting | 96% |

These figures are the reported project metrics. For a rigorous comparison, consult the evaluation methodology, dataset, and results documented in the research materials.

## 🛠️ Technology Stack

- **Language:** Python
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Deep Learning:** CNN-based image classification
- **Web Application:** Flask
- **Research and Evaluation:** Model performance analysis and agricultural data processing

## 📄 Research & Presentation

The research paper and presentation are available directly in the repository.

- **[📘 IEEE Conference Paper — PDF](smart%20crop%20agro%20system%20assests/IEEE_Conference_Smart%20Agro%20System%20for%20Crop%20Recommendation.pdf)**
- **[📊 ISAA 2026 Presentation — PPTX](smart%20crop%20agro%20system%20assests/ISAA2026_Presentation.pptx)**

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/venkat24-dev/Smart-Agro-Crop-Recommendation-System.git
cd Smart-Agro-Crop-Recommendation-System
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run the application using the appropriate entry-point script and setup instructions in the repository.

> **Note:** Confirm the actual entry-point filename and dependency file location in your repository before running the commands. The assets folder shown above contains research and presentation files, not necessarily the application code.

## 🎯 Project Objective

The objective is to explore how machine learning and image classification can support agricultural decisions by translating soil-related information into understandable crop recommendations.

The system is intended as a decision-support tool, not a replacement for soil laboratory testing or expert agricultural advice.

---



