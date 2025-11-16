

```markdown
# Fuzzy C-Means Image Segmentation

This project contains a **custom implementation (not built-in)** of the **Fuzzy C-Means (FCM)** clustering algorithm, applied to both **grayscale and RGB image segmentation**.
The algorithm is implemented from scratch in Python and demonstrated in a Jupyter Notebook.

---

## 📁 Repository Structure

```

Fuzzy_C-Means/
│
├── FCM_Algorithm.pdf          # Explanation of the FCM algorithm and formulas
├── FCM_Implementation.ipynb   # Full implementation + segmentation results
├── FCM_Report.pdf             # Full report including visuals, results, and discussion
│
├── Images/                    # Original input images (grayscale & RGB)
│   ├── milky-way-nvg.png     
│   └── milky-way.png
│
└── Visuals/                   # Output visualizations (heatmaps, segmentations, 3D plots, etc.)
├── 3D_Cluster0.png, 3D_Cluster1.png, 3D_Cluster2.png
├── Greyscale_membership.png
├── Greyscale_output.png
└── RGB_Segmentation


```

---

## 🔍 Project Overview

* Implements the **Fuzzy C-Means** clustering algorithm from scratch
* Segments images into soft clusters (each pixel has partial membership)
* Provides **both fuzzy and hard segmentation outputs**
* Includes:

  * Membership heatmaps
  * Pixel intensity–membership curves
  * 3D color membership scatter plots (RGB)
  * Hard segmentation maps

---

## What is Fuzzy C-Means?

Fuzzy C-Means is a clustering algorithm where each data point (pixel) can belong to multiple clusters with varying degrees (values in [0,1]), unlike k-means which forces hard assignment.
It is especially useful for **soft boundaries** and **uncertain regions** in images.

---

## Implementation Details

* Written in **Python**
* Fully implemented in:
  **`FCM_Implementation.ipynb`**
* No external FCM libraries used
* Run time:

  * Grayscale image → converged in 51 iterations (~8 min)
  * RGB image → converged in 43 iterations (~44 min)

---

## Visual Results

All generated visualizations are stored in the **`Visuals`** folder, including:

* Fuzzy membership maps
* Hard segmentation results
* Membership vs intensity curves
* RGB 3D membership scatter plots

---

## Documentation

* **FCM_Algorithm.pdf** — Complete Algorithm Explanation
* **FCM_Report.pdf** — Implementation write-up + results + analysis

---

## How to Run

1. Open the notebook:

```

FCM_Implementation.ipynb

```
2. Run cells in order
3. Results and visualizations will be generated automatically

---

## ✨ Author

**Hadia Amjad**  
This project was developed as part of an assignment on fuzzy clustering and image segmentation.
```



