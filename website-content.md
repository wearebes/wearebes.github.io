# Jiacheng Yao

**Applied Mathematics · AI for Science · Scientific Machine Learning**

Final-year undergraduate at Beijing Normal–Hong Kong Baptist University, working at the intersection of applied mathematics, machine learning, and scientific computing.

## About

I am a final-year BSc (Hons) student in Applied Mathematics at Beijing Normal–Hong Kong Baptist University (BNBU), with expected graduation in June 2027. I was an exchange student at Hong Kong Baptist University in Spring 2026.

My research interests center on scientific machine learning and numerical methods, particularly the use of neural models in multiphase flow simulation. I also work on computer vision for archery analysis and have experience developing AI tools for education. Across these projects, I develop workflows that connect data collection, modeling, evaluation, and practical deployment.

## Research Interests

- **Scientific Machine Learning:** Learning-based methods for scientific computing and numerical simulation.
- **Numerical Methods and Multiphase Flow:** Interface-curvature estimation, level-set methods, and solver integration.
- **Computer Vision and Sports Analytics:** Arrow-impact localization, high-speed motion analysis, and quantitative equipment evaluation.

## Selected Research & Projects

### Neural Curvature Estimation for Two-Phase Flow Simulations

**January 2026–Present · Supervisor: Dr. Jiaqi Zhang**

I develop neural estimators of interface curvature for level-set-based two-phase flow simulations. My work spans data generation, model training, generalization tests, and integration into a numerical flow solver.

- Built a training pipeline using approximately 83.5 million labeled samples across five grid resolutions. In matched-resolution tests, the models reduced mean squared error by factors of 5.6–260 relative to second-order finite-difference curvature estimation.
- Evaluated transfer across resolutions, sensitivity to level-set reinitialization, and generalization to unseen flower-shaped interfaces.
- Converted trained networks into standalone C routines and integrated them into Basilisk’s CLSVOF solver without external machine-learning dependencies, with evaluation on stationary bubble, capillary wave, and rising bubble benchmarks.

**Output:** First-author manuscript in preparation.

**Methods & tools:** PyTorch, Python, C, Basilisk, level-set methods, CLSVOF.

### Automated Arrow-Impact Localization and Ring-Score Recognition

**June 2026–Present · Supervisors: Dr. Lidong Fang and Prof. Huaxiong Huang**

I am developing a computer-vision pipeline for arrow-impact localization and automatic scoring, extending earlier arrow-selection research toward automated training and assessment.

- Built the data curation, annotation, training, and evaluation workflow, using YOLO-based detection after exploring a ResNet-based formulation.
- Trained on annotated public data and evaluated on self-collected target images to study generalization to practical shooting conditions.
- Investigated image preprocessing and augmentation; the best preliminary configuration achieved precision and recall above 70% on self-collected target images.

**Methods & tools:** Python, PyTorch, YOLO, OpenCV.

### Data-Driven Archery Arrow Selection

**July 2025–May 2026 · Research Assistant, Faculty of Science and Technology, BNBU**

I contributed to a joint arrow-selection project with the 18th Institute of CASC and Beijing Institute of Technology for the Chinese National Archery Team.

- Conducted controlled shooting tests and multi-orientation shaft-deflection measurements using a standardized experimental workflow.
- Developed high-speed-video analysis to extract launch velocity, launch angle, and trajectory-deviation measures.
- Built and manually validated a dataset linking physical arrow measurements, shot-level kinematics, scores, and impact locations, and analyzed dispersion and scoring consistency to support arrow selection.

**Output:** Equal-contribution co-author of a manuscript submitted to *Sports Engineering*.

**Methods & tools:** Python, OpenCV, high-speed imaging, statistical analysis.

## Research Outputs

### Neural Curvature Estimation for Level-Set-Based Two-Phase Flow Simulations

First-author manuscript in preparation. Working title.

### Arrow Selection for Elite Series Arrows: Data-Driven Archery Arrow Selection

Equal-contribution co-author. Manuscript submitted to *Sports Engineering*.

## Industry Experience

### Wanhoo Technology (Shenzhen) Co., Ltd.

**Remote Research Intern · September 2025–March 2026**  
**Supervisor:** Dr. Jiaqi Zhang

Developed an AI teaching-support system built on a retrieval-augmented generation platform. My contributions included document ingestion with MinerU/OCR, integration of embedding, reranking, and chat models, and editable assessment generation with DOCX export. I also integrated tool execution for multi-step tasks and deployed the system internally with Docker.

## Education

### Beijing Normal–Hong Kong Baptist University

**BSc (Hons) in Applied Mathematics · September 2023–June 2027 (expected)**  
Zhuhai, China · English-medium instruction

### Hong Kong Baptist University

**Exchange Student · January–May 2026**  
Hong Kong SAR, China

## Honors & Awards

- **Second-Class Student Scholarship**, BNBU — Academic years 2023–2024 and 2024–2025.
- **Third Prize**, Guangdong Contemporary Undergraduate Mathematical Contest in Modeling — 2025.
- **Scholarship for the Extended Study Programme in the Greater Bay Area**, HKBU — January 2026.

## Technical Skills

**Programming:** Python, C, MATLAB, SQL.  
**Scientific computing & machine learning:** PyTorch, NumPy, SciPy, pandas, OpenCV, Basilisk.  
**Development:** Git, Linux, Docker, LaTeX, retrieval-augmented generation, document processing.

## Contact

Based in Zhuhai, China.

**Email:** [t330033042@mail.bnbu.edu.cn](mailto:t330033042@mail.bnbu.edu.cn)
