# Okra Thermal Image Dataset

[![DOI](https://zenodo.org/badge/DOI/10.17632/zrddng9xpr.1.svg)](https://doi.org/10.17632/zrddng9xpr.1)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Data in Brief](https://img.shields.io/badge/Journal-Data%20in%20Brief-orange)](https://doi.org/10.1016/j.dib.2024.110645)

---

### 🧩 Overview

The **Okra Thermal Image Dataset** is a publicly available **agricultural imaging dataset** developed at  
the *Centre for Advanced Data Science, VIT Chennai, India*.  
It contains **501 thermal images of okra (Abelmoschus esculentus)** captured using a **FLIR E75 infrared camera**  
for **non-invasive maturity classification** and **food-quality assessment** research.  

This dataset supports **machine learning**, **deep learning**, and **computer vision** studies in  
agriculture, post-harvest quality monitoring, and sustainability.

---

### 📊 Dataset Summary

| Attribute | Description |
|------------|-------------|
| **Total Images** | 501 (JPG format) |
| **Categories** | `adequate_matured_okra` (248) and `over_matured_okra` (253) |
| **Camera** | FLIR E75 (320 × 240 thermal res.; 640 × 480 output) |
| **Spectral Range** | 7.5–14 µm |
| **Ambient Temperature** | 30 °C (controlled) |
| **Location** | VIT Chennai, India (12.8406 °N, 80.1534 °E) |
| **Publication** | *Data in Brief 55 (2024) 110645* |
| **DOI** | [10.17632/zrddng9xpr.1](https://doi.org/10.17632/zrddng9xpr.1) |

---

### 📁 Repository Structure

```
Okra-Thermal-Image-Dataset/
├── adequate_matured_okra/
│   ├── IMG_001.jpg
│   ├── IMG_002.jpg
│   └── ...
└── over_matured_okra/
    ├── IMG_251.jpg
    ├── IMG_252.jpg
    └── ...
```

---

### 💾 How to Download Using Command Line

You can directly download the dataset ZIP from **Mendeley Data** using either `wget` or `curl`.

#### Using wget
```bash
wget "https://prod-dcd-datasets-cache-zipfiles.s3.eu-west-1.amazonaws.com/zrddng9xpr-1.zip" -O okra_dataset.zip
unzip okra_dataset.zip -d data/
```

#### Using curl
```bash
curl -L "https://prod-dcd-datasets-cache-zipfiles.s3.eu-west-1.amazonaws.com/zrddng9xpr-1.zip" -o okra_dataset.zip
unzip okra_dataset.zip -d data/
```

This will create a `data/` folder containing:  
`adequate_matured_okra/` and `over_matured_okra/`

---

### 🌱 Value of the Data

- Enables **non-destructive evaluation** of okra maturity for **agriculture and food technology**.  
- Provides benchmark data for **computer-vision and machine-learning** model development.  
- Facilitates **infrared-based quality inspection** and **temperature-pattern analysis**.  
- Promotes **open-science and reproducible research** in sustainable agriculture.  
- Serves as a foundation for **FLIR thermal-imaging datasets** in food-quality studies.

---

### 🧾 Citation

If you use this dataset, please cite:

> **Sasithradevi A., Shoba S., Persiya J., Prakash P., Adeline Sneha A.**  
> *Thermal image dataset for okra maturity analysis.*  
> *Data in Brief,* 55 (2024) 110645.  
> DOI: [10.1016/j.dib.2024.110645](https://doi.org/10.1016/j.dib.2024.110645)

---

### 🪪 License

This dataset is licensed under the  
**Creative Commons Attribution – NonCommercial 4.0 International (CC BY-NC 4.0)**.  
You may share and adapt the material for **non-commercial purposes** with proper attribution.

[View Full License](https://creativecommons.org/licenses/by-nc/4.0/)

---

### 🧠 Acknowledgements

Developed by the **Centre for Advanced Data Science**,  
**Vellore Institute of Technology, Chennai, India**.  

Special thanks to all contributors involved in dataset curation, annotation, and validation.

---

### 🔗 Dataset Access

The complete dataset is available on **Mendeley Data**:  
➡️ [https://data.mendeley.com/datasets/zrddng9xpr/1](https://data.mendeley.com/datasets/zrddng9xpr/1)

---

### 🔍 SEO Keywords

`Okra Thermal Image Dataset`, `FLIR E75`, `thermal imaging dataset`, `agricultural imaging dataset`,   
`non-invasive maturity classification`, `food quality assessment`, `machine learning`,   
`deep learning`, `computer vision`, `infrared imaging`, `VIT Chennai`, `Data in Brief`.

---

<!-- Structured Data for Google Dataset Search -->
<script type="application/ld+json">
{
  "@context": "https://schema.org/",
  "@type": "Dataset",
  "name": "Okra Thermal Image Dataset",
  "description": "Thermal image dataset of okra captured using a FLIR E75 camera for non-invasive maturity classification and food quality research.",
  "url": "https://github.com/<your-username>/Okra-Thermal-Image-Dataset",
  "sameAs": "https://doi.org/10.17632/zrddng9xpr.1",
  "creator": {
    "@type": "Organization",
    "name": "Vellore Institute of Technology, Chennai, India"
  },
  "license": "https://creativecommons.org/licenses/by-nc/4.0/",
  "keywords": ["okra", "thermal imaging", "agriculture", "FLIR E75", "food quality", "computer vision", "non-invasive classification", "dataset"],
  "datePublished": "2024-06-18"
}
</script>
