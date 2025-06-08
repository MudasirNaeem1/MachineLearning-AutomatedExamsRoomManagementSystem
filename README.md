# 🎓 Automated Exam Management System

<div align="center">

![Programming Language](https://img.shields.io/badge/Programming%20Language-Python-blue?style=for-the-badge)
![GUI](https://img.shields.io/badge/GUI-CustomTkinter-green?style=for-the-badge)
![KMeans](https://img.shields.io/badge/KMeans-Scikit--Learn-orange?style=for-the-badge)
![Statistics](https://img.shields.io/badge/Statistics-NumPy-red?style=for-the-badge)

**📦 Developed by using K-Means Clustering Algorithm (Machine Learning)**

*An intelligent solution for optimal student seating arrangements in examination halls with invegilators allocations*

</div>

---

## 🌟 Overview

The **Automated Exam Management System** is a sophisticated desktop application that leverages machine learning algorithms to create optimal seating arrangements for examinations. Using the **K-Means Clustering** algorithm, it intelligently distributes students across multiple rooms while maintaining balance and diversity.

![Code-Screenshot](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Code%20Screenshot.JPG)

### ✨ Key Highlights

- 💬 **AI-Powered**: Uses K-Means clustering for intelligent room allocation
- 🎨 **Modern UI**: Beautiful dark/light theme with CustomTkinter
- 📊 **Analytics Dashboard**: Comprehensive performance metrics and statistics
- 📋 **Export Ready**: Generate detailed seating plans and faculty assignments
- ⚡ **Real-time Processing**: Multi-threaded generation for smooth performance
- 🔧 **Customizable**: Flexible settings for different examination scenarios

---

## 🚀 Features

### 🎯 Core Functionality

| Feature | Description |
|---------|-------------|
| **Smart Distribution** | K-Means algorithm ensures balanced student allocation across rooms |
| **Domain Mixing** | Optional cross-domain student distribution for diverse examination environment |
| **Capacity Management** | Intelligent room capacity handling and optimization |
| **Faculty Allocation** | Automatic supervisor assignment to examination rooms |

### 📊 Analytics & Reporting

- **📈 Performance Metrics**: Clustering quality scores and statistical analysis
- **📋 Detailed Reports**: Room-wise seating arrangements with student information
- **👥 Faculty Assignments**: Complete supervision schedules and responsibilities
- **📄 Export Options**: Print-ready formats for examination day logistics

### 🛠️ User Interface

- **🎨 Modern Design**: Clean, intuitive interface with professional styling
- **🌓 Theme Support**: Dark/Light mode switching
- **📱 Responsive Layout**: Adaptive design for different screen sizes
- **⚡ Quick Actions**: One-click access to common operations

---

## 📋 Requirements

### System Requirements
- **Operating System**: Windows 10+, macOS 10.14+, or Linux
- **Python Version**: 3.8 or higher
- **RAM**: Minimum 4GB (8GB recommended)
- **Storage**: 100MB free space

### Python Dependencies

```bash
customtkinter>=5.2.0
scikit-learn>=1.3.0
numpy>=1.21.0
threading
tkinter
time
random
```

---

## 🔧 Installation to use 

### Method 1: Clone Repository

```bash
# Clone the repository
git clone https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System.git
cd exam-management-system

# Install dependencies
pip install -r requirements.txt

# Run the application
Automated-Exam-Rooms-Management-System.ipynb (in Jupyter Notebook or Google Colab)
```

### Method 2: Direct Download

1. Download the source code as ZIP
2. Extract to your desired location
3. Install dependencies: `pip install customtkinter scikit-learn numpy`
4. Run: `Automated-Exam-Rooms-Management-System.ipynb`

---

## 🚀 Getting Started

1. **Open File in Jupyter Notebook/ Google Colab**
   ```bash
   Automated-Exam-Rooms-Management-System.ipynb
   ```

2. **Input Parameters**
   - Enter total number of students
   - Specify available examination rooms
   - Set room capacity (optional)
   - Choose domain mixing preference

![Home-GUI](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Home%20Page.JPG)

3. **Generate Seating Plan**
   - Click "Generate Seating Plan"
   - Wait for AI processing to complete
   - Access results through action buttons

### 📊 Understanding the Output

#### Seating Plan Tab
```
ROOM 1 (25 students)
Row 1: S001(CS)  S015(AI)  S032(BA)  S045(ME)  S067(MA)
Row 2: S089(EE)  S112(CS)  S134(AI)  S156(BA)  S178(ME)
...
```

Attached Screenshot Showing the complete Generated Seating Plan using K-Means Ckustering

![Seating-Plan](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Seating%20Plane.JPG)

#### Analytics Dashboard
- **Clustering Quality**: Inertia scores and convergence metrics
- **Distribution Balance**: Statistical measures of room allocation
- **Domain Diversity**: Cross-room subject distribution analysis
- **Performance Recommendations**: Optimization suggestions

![Analytics-Dashboard](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Cluster%20Analytics%20%26%20Performance%20Matrics.JPG)

#### Faculty Allocation
- Room-wise supervisor assignments
- Capacity utilization statistics
- Break schedule recommendations
- Quality assurance checklist

![Faculty-Allocation](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Faculty%20Allocation.JPG)

---

## 🎯 Algorithm Explanation

### K-Means Clustering Implementation

The system uses **K-Means Clustering** to optimize student distribution:

```python
# Core algorithm workflow
1. Student Data Generation → Domain-based feature vectors
2. K-Means Initialization → Random cluster centers
3. Iterative Optimization → Minimize within-cluster variance
4. Convergence Check → Stable cluster assignments
5. Result Validation → Balance and quality assessment
```

### Why K-Means for Exam Seating?

| Advantage | Benefit |
|-----------|---------|
| **Balanced Distribution** | Ensures similar number of students per room |
| **Minimize Variance** | Creates homogeneous room compositions |
| **Scalable Performance** | Handles large student populations efficiently |
| **Reproducible Results** | Consistent outcomes with seed control |

---

## 🎨 Screenshots Attached

1. Final seating arrangement filled in system records, showing student-wise domain and room allocation data.

![Filled-Code](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Filled%20Recored.JPG)

2. This screenshot shows the application interface in Light Mode.
   It demonstrates user-friendly design and readability across themes.
   Theme switching is accessible via the settings for flexible UI preferences.

![Home Light Mode](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Home_Light_Mode.JPG)

3. The Summary screen displays the final output after successful clustering.
   It summarizes total students, domains, room distribution, and generation time.
   Helpful for reviewing the process results at a glance.

![Summary](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Summary.JPG)

4. This window allows users to switch between Light, Dark, or System themes.
   Improves usability by offering personalized UI appearance preferences.
   Designed for clean layout and fast theme switching without restarting.

![Settings](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Settings.JPG)

5. The Help screen offers guidance on how to use the app.
   Explains input fields, feature functions, and generation steps. 
   Useful for first-time users to understand how clustering is applied.

![Help](https://github.com/MudasirNaeem1/MachineLearning-Exam-Management-System/blob/main/Output%20Screenshots/Help.JPG)


### Analytics Dashboard
- 📊 Real-time clustering metrics
- 📈 Distribution visualization
- 🎯 Quality assessment scores
- 💡 Optimization recommendations

---

## ⚙️ Configuration Options

### Application Settings

| Setting | Description | Default |
|---------|-------------|---------|
| **Appearance Mode** | Light/Dark/System theme | Dark |
| **Random Seed** | Reproducibility control | Auto |
| **Max Iterations** | Algorithm convergence limit | 300 |
| **Domain Mixing** | Cross-subject distribution | Enabled |
---


### Advanced Parameters

```python
# Customizable clustering parameters
kmeans = KMeans(
    n_clusters=num_rooms,      # Number of examination rooms
    random_state=42,           # Seed for reproducibility
    n_init=10,                 # Multiple initializations
    max_iter=300              # Convergence iterations
)
```

---

### Areas for Contribution

- 🎨 **UI/UX Improvements**: Enhanced visual design and user experience
- 📈 **Algorithm Optimization**: Alternative clustering methods
- 📊 **Data Visualization**: Graphical analytics and charts
- 🔧 **Feature Extensions**: Additional export formats and integrations
- 🐛 **Bug Fixes**: Issue resolution and code optimization

---

## 👨‍💻 Author & Credits

**Developed by**: Mudasir Naeem

**Contact**: mudasirnaeem000@gmail.com

**GitHub**: [MudasirNaeem1](https://github.com/MudasirNaeem1)

---

## 👤 Contributing

We welcome contributions! 

  Interested in educational AI research? ⭐ **Star this repository!**
  
  Have questions about the implementation? 💭 **Let's discuss!**
  
</div>
<div align="center">  
  
  Found this project interesting? ⭐ **Star the repository!**
  
  Have suggestions? 💭 **Reach out!**
  
  ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=MudasirNaeem1.MachineLearning-Exam-Management-System)
</div>

