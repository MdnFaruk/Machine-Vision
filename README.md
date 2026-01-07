# Machine Vision 521466S-3008

> Course page and workspace for exercises, assignments and course materials.

---

## 📘 Course
**Machine Vision**

Welcome to the Machine Vision course workspace. This repository will contain course notes, Jupyter notebooks, exercises and assignment solutions. I will add all exercises and assignments here.

---

## 🎯 Learning outcomes
Upon completion of the course the student:
1. Understands fundamentals of image acquisition, representation and modeling
2. Can use 2D transformations in model fitting and image registration
3. Can use basic methods of 3D imaging and reconstruction
4. Can utilize classical and deep learning methods for elementary image recognition problems

---

## 🧭 Course Contents (11 lessons)
1. Introduction
2. Imaging
3. Light and color
4. Feature extraction
5. Motion from 2D image sequences
6. 2D models and transformations
7. Perceiving depth from 2D images
8. 3D transformations and reconstruction
9. Recognition
10. Deep learning fundamentals
11. Dense prediction and object detection


---

## ✅ Assessment methods & criteria
- Quizzes (10 quizzes; Q in [0,10]) — multiple choice, in-class or remote.
- Homework assignments (8 assignments, 2 points each; A in [0,16], acceptance threshold **8** points).
- Midterms: two midterms (M1, M2 in [0,15], threshold **7** each).
- Finals: final exams (E in [0,30], threshold **14**).

### Course completion tracks (P = course points)
- **Track 1:** P = Q + A (max P = 26)
- **Track 2:** P = Q + M + A (M is M1 or M2) (max P = 41)
- **Track 3:** P = Q/2 + M1 + M2 + A (max P = 51)
- **Track 4:** P = Q/2 + E + A (max P = 51)

> Minimum requirement to complete the course: **P = 22** points. The system automatically chooses the best track for the student.

### Final grade mapping
| P (points) | Grade |
|---:|---:|
| 22–26 | 1 |
| 27–31 | 2 |
| 32–36 | 3 |
| 37–41 | 4 |
| 42–51 | 5 |

---

> I will add assignment notebooks and solutions under `assignments/` and exercise materials under `exercises/`.

---

## 💻 Jupyter notebooks & OpenCV (setup)
Recommended: Python 3.11+ and OpenCV. Options:

- **Anaconda**
  - Install Anaconda
  - Install OpenCV: `pip install opencv-python opencv-contrib-python`
  - Start Jupyter: `jupyter notebook`

- **Noppe (CSC)**
  - Use Jupyter Machine Learning environment, then install headless packages in terminal:
    - `pip install opencv-python-headless opencv-contrib-python-headless`

- **Visual Studio Code**
  - Install Python & VS Code + Jupyter extension
  - Open `.ipynb` files and select interpreter
  - Install OpenCV: `pip install opencv-python opencv-contrib-python`

Tips:
- Use the provided pre-tutorials if you need a refresher on NumPy / Jupyter.
- If you want to run notebooks locally, download `data.zip` from the course page and extract the files next to notebooks.

---

## 📚 Study material & references
- Video lectures and slides (linked on course page)
- Jupyter notebook guides and tutorials
- OpenCV docs
- Textbooks (freely available):
  - R. Szeliski — Computer Vision: Algorithms and Applications (2nd ed., 2022)
  - D.A. Forsyth & J. Ponce — Computer Vision: A Modern Approach (2002)
  - A. Zhang et al — Dive into Deep Learning (2023)

---

## 🔧 Repo structure (suggested)
- `assignments/` — assignment notebooks and student solutions
- `exercises/` — exercise notebooks and solutions
- `data/` — shared data for notebooks (unzip course `data.zip` here)
- `notebooks/` — supporting demos and examples

---
