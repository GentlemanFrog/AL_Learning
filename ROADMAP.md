# Data Science & Computer Vision Roadmap

**Focus:** Python, Machine Learning, Computer Vision, MLOps  
**Learning Style:** 30% structured learning, 70% hands-on building  

---

## Phase 1: Foundations & Portfolio Setup (Weeks 1-4)

### Goals
- Set up GitHub portfolio with professional structure
- Refresh Python data science stack (pandas, numpy, matplotlib)
- Learn minimum viable Git (command-line basics)
- Establish image standardization protocol for your plant project

### Key Tasks
1. **GitHub Portfolio Setup**
   - Create `AL_Learning` repository with professional README
   - Add project structure: `projects/`, `learning-notes/`, `resources/`
   - Commit existing code (even if messy) — this is a starting point.

2. **Python Refresher** (10 hours)
   - pandas: DataFrames, grouping, merging, time-series operations
   - NumPy: array operations, broadcasting, linear algebra basics
   - matplotlib/seaborn: publication-quality visualizations
   - Resource: "Python for Data Analysis" by Wes McKinney (selected chapters)

3. **Git Essentials** (5 hours)
   - `init`, `add`, `commit`, `push`, `pull`, `branch`, `merge`
   - Writing good commit messages
   - Resource: GitHub's "Hello World" tutorial + practice

4. **Image Standardization Protocol** (10 hours)
   - Document your image capture process (lighting, distance, background)
   - Create a simple checklist for consistent data collection
   - Organize existing images into a structured folder hierarchy

### Milestone
- [x] GitHub repo live with README and project structure
- [ ] Can perform basic data wrangling with pandas
- [x] Can use command-line Git for daily workflow
- [ ] Image standardization protocol documented

---

## Phase 2: Core Machine Learning & Computer Vision (Weeks 5-12)

### Goals
- Build strong foundation in ML algorithms and PyTorch
- Implement SAHI for small object detection
- Apply transfer learning to your limited dataset
- Start building your plant detection pipeline

### Key Tasks
1. **Machine Learning Fundamentals** (20 hours)
   - scikit-learn: classification, regression, clustering, cross-validation
   - Evaluation metrics: precision, recall, F1, ROC-AUC
   - Resource: "Hands-On Machine Learning" by Aurélien Géron (Ch. 1-9)

2. **PyTorch Deep Learning** (25 hours)
   - Tensors, autograd, building and training neural networks
   - CNNs: architecture, training, transfer learning
   - Resource: PyTorch official tutorials + "Deep Learning with PyTorch" by Eli Stevens

3. **Computer Vision Techniques** (20 hours)
   - OpenCV: image processing, feature detection
   - Data augmentation with Albumentations
   - SAHI implementation for slicing large images
   - Resource: OpenCV documentation + SAHI GitHub repo

4. **Plant Detection Pipeline v1** (15 hours)
   - Implement YOLO or RF-DETR with transfer learning
   - Apply SAHI to your microscopy images
   - Basic segmentation for size/growth measurements
   - Document everything in your GitHub repo

### Milestone
- [ ] Trained first object detection model on your plant images
- [ ] SAHI successfully detecting small fronds/leaflets
- [ ] Segmentation pipeline measuring object sizes
- [ ] Code documented and pushed to GitHub

---

## Phase 3: Advanced Techniques & Portfolio Projects (Weeks 13-20)

### Goals
- Master advanced CV techniques relevant to your project
- Build a Streamlit dashboard for visualization
- Implement colorimetric and time-series analysis
- Create 2-3 portfolio projects demonstrating end-to-end skills

### Key Tasks
1. **Advanced Computer Vision** (20 hours)
   - Advanced segmentation (U-Net, Mask R-CNN)
   - Model optimization: ONNX export, quantization
   - Experiment tracking with MLflow
   - Resource: Papers With Code + documentation

2. **Colorimetric & Geometry Analysis** (15 hours)
   - Color spaces: RGB, HSV, Lab for stress detection
   - Vegetation indices adapted for your use case
   - Geometric features: area, perimeter, shape descriptors
   - Statistical analysis of extracted features

3. **Streamlit Dashboard** (15 hours)
   - Build interactive dashboard for your project
   - Visualize detections, segmentations, and time-series trends
   - Deploy to Streamlit Cloud (free)
   - Resource: Streamlit documentation + examples

4. **Portfolio Project: End-to-End Pipeline** (20 hours)
   - Combine all components into a reproducible pipeline
   - Include: data loading → preprocessing → detection → segmentation → analysis → visualization
   - Write comprehensive README with results and insights
   - This becomes your flagship portfolio piece

### Milestone
- [ ] Streamlit dashboard live and accessible
- [ ] Colorimetric analysis showing stress indicators
- [ ] End-to-end pipeline documented on GitHub
- [ ] 2-3 additional smaller portfolio projects

---

## Phase 4: Production Skills & Job Readiness (Weeks 21-24)

### Goals
- Learn MLOps fundamentals (Docker, deployment)
- Prepare for applications

### Key Tasks
1. **MLOps & Deployment** (15 hours)
   - Docker: containerize your applications
   - Model serving: FastAPI or Flask for inference APIs
   - Cloud basics: AWS or GCP free tier deployment
   - Resource: "Introducing MLOps" by Mark Treveil et al.

2. **SQL for Data Science** (10 hours)
   - Complex queries, joins, window functions
   - Practice with PostgreSQL or SQLite
   - Resource: Mode Analytics SQL tutorial

3. **Portfolio Polish & Communication** (10 hours)
   - Refine READMEs with clear problem/solution/results structure
   - Record a demo video of your Streamlit dashboard
   - Practice explaining your project to non-technical audiences
   - Write one Medium blog post about your learning journey

4. **Job Market Preparation** (5 hours)
   - Research target companies and roles
   - Prepare for technical interviews: Python, ML concepts, your project

### Milestone
- [ ] Model deployed and accessible via API or web app
- [ ] SQL proficiency demonstrated

---

## Weekly Structure

| Day | Activity |
|-----|----------|
| 1 | Structured learning (course/book) |
| 2 | Hands-on coding (implement what you learned) |
| 3 | Project work (apply to your plant detection) |
| 4 | Review, documentation, GitHub commits |
| 5 | Community (forums, blog reading, networking) |

---

## Key Resources

### Books
- "Python for Data Analysis" — Wes McKinney
- "Hands-On Machine Learning" — Aurélien Géron
- "Deep Learning with PyTorch" — Eli Stevens et al.

### Courses
- PyTorch Official Tutorials (free)
- fast.ai "Practical Deep Learning for Coders" (free)
- Coursera: "Machine Learning" by Andrew Ng

### Tools & Platforms
- GitHub (portfolio + version control)
- Google Colab / Kaggle (free GPU training)
- Streamlit (dashboard deployment)
- MLflow (experiment tracking)
- Docker (containerization)

### Communities
- r/MachineLearning, r/datascience
- PyTorch Discord
- Kaggle competitions and notebooks

---

## Success Metrics

By the end of 6 months, you should have:
- [ ] 3-4 portfolio projects on GitHub with clear documentation
- [ ] At least one deployed model (Streamlit app or API)
- [ ] Proficiency in Python, SQL, PyTorch, and OpenCV
- [ ] Understanding of MLOps fundamentals (Docker, deployment)
- [ ] Ability to explain your work to technical and non-technical audiences
- [ ] Target companies identified and applications submitted

---

## Notes

- **Math on-demand:** Learn mathematical concepts as needed for projects rather than front-loading. When you encounter a concept (e.g., gradient descent, convolution), study it then.
- **Build in public:** Commit to GitHub regularly and share progress.
- **SAHI is crucial:** Small objects on large images require this technique.
- **Limited data strategy:** Use transfer learning, data augmentation, and SAHI to maximize what can be learned from small datasets.
