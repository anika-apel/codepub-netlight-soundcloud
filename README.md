# DEI in Music Industry - Data Analysis Workshop

Hands-on Workshop on Diversity, Equity, and Inclusion (DEI) in the music industry as part of a CodePub in collaboration with SoundCloud.

## Overview

This workshop provides a comprehensive exploration of DEI challenges in the music industry through data analysis. 
Using real-world inspired data from streaming platforms, we'll examine representation patterns, identify biases, and develop data-driven solutions for promoting equity.

## Workshop Structure

The workshop is designed with three different levels to accommodate different skill levels. 
The beginner workshop gives more instructions and uses less known concepts whereas the intermediate and advanced level leave you more freedom to explore the data on your own and come up with ideas.
Imagine this like a small-scale hackathon. 

As part of this workshop, you can look into:
- **Representation gaps** across demographics
- **Success pattern differences** between groups
- **Label type distribution** and access to resources
- **Algorithmic bias** in predictive models
- **Fairness metrics** and their interpretation


### 🟢 **Beginner Level** 
**Focus**: Basic data exploration and visualization of listening behavior of artists
- **File**: `notebooks/beginner/beginner_dei_analysis.ipynb`
- **Skills**: Pandas basics, simple visualizations, descriptive statistics
- **Duration**: 75 minutes
- **Topics**:
  - Loading and exploring datasets
  - Gender and ethnic representation analysis
  - Creating basic charts (pie charts, bar charts)
  - Calculating summary statistics

### 🟡 **Intermediate Level**
**Focus**: Data exploration and statistical analysis of comment behavior of artists
- **File**: `notebooks/intermediate/intermediate_dei_analysis.ipynb`
- **Skills**: correlation analysis, interactive visualizations
- **Duration**: 75 minutes
- **Prerequisites**: Basic knowledge of Pandas, numpy and plotting libraries
- **Topics**:
  - Combining datasets
  - Correlation analysis and heatmaps
  - Interactive visualizations with Plotly
  - Cross-tabulation and demographic breakdowns
  - Identifying patterns in metrics

### 🔴 **Advanced Level**
**Focus**: Recommendations and Predictions for listeners and artists
- **File**: `notebooks/advanced/advanced_dei_analysis.ipynb`
- **Skills**: Machine learning, fairness metrics
- **Duration**: 75 minutes
- **Prerequisites**: Intermediate Python, basic ML concepts, statistics background
- **Topics**:
  - Predictive modeling for artist success
  - Feature engineering and importance analysis
  - Clustering analysis (artist archetypes)
  - Building recommendation systems
  - Optional: Bias detection in ML models
  - Optional: Fairness metrics and equity scoring

## Dataset

The workshop uses an anonymized version of SoundClouds data containing data about listening & commenting behavior of artists. 
In total, it contains 5 different datasets. 

The data includes:
- **Demographics**: Gender, ethnicity, country of artists and listeners
- **Career Info**: Genre (anonymized)
- **Success Metrics**: Monthly plays, comments

## Getting Started

### Prerequisites

- Python 3.7+ 
- Jupyter Notebook or JupyterLab
- Basic familiarity with Python (for beginner level)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/anika-apel/codepub-netlight-soundcloud.git
cd codepub-netlight-soundcloud
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter:
```bash
jupyter notebook
```

4. Choose your level and open the corresponding notebook:
   - Beginner: `notebooks/beginner/beginner_dei_analysis.ipynb`
   - Intermediate: `notebooks/intermediate/intermediate_dei_analysis.ipynb`
   - Advanced: `notebooks/advanced/advanced_dei_analysis.ipynb`

## Key Learning Outcomes

By completing this workshop, participants will:

- **Understand DEI challenges** in the music industry through data
- **Develop analytical skills** for identifying bias and inequity
- **Gain practical experience** with real-world datasets
- **Build awareness** of algorithmic bias and fairness
- **Create actionable insights** for promoting equity

## Workshop Flow

This is a group workshop. Meet up in groups of three people with the same skill level and start with your workshop. Collaboration is key here to tackle the tasks and explore different ideas. 
At the end, we will collect key findings and results on this Miro board to share it with everyone. 

This is a safer space, you can ask any questions. We and all other participants are here to support each other ✨

## Technical Requirements

1. Install Python 3.7+ and Jupyter Notebook
  - [See official python installer](https://www.python.org/downloads/)
  - Use a package manager: 
    - MacOS: `brew install python`
    - Linux: use your distribution's package manager (e.g. `apt` for Ubuntu/Debian) -`sudo apt update && sudo apt instsall python3 python3-pip`
    - Windows: Use Chocolately or Scoop - `choco install python` or `scoop install python`
2. Install all requirements: `pip install -r requirements.txt`

### Required Python Packages:
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `matplotlib` - Basic plotting
- `seaborn` - Statistical visualization
- `plotly` - Interactive visualizations
- `scipy` - Statistical functions
- `scikit-learn` - Machine learning (advanced level)
- `jupyter` - Notebook environment

### System Requirements:
- **RAM**: 4GB minimum (8GB recommended for advanced level)
- **Storage**: 100MB free space
- **OS**: Any (Windows, macOS, Linux)

## Contributing

This workshop is designed for educational purposes. To contribute:

1. Fork the repository
2. Create a feature branch
3. Make improvements (additional analyses, bug fixes, better explanations)
4. Submit a pull request

## Ethical Considerations

This workshop aims to:
- **Promote awareness** of DEI issues in creative industries
- **Encourage data-driven** approaches to addressing inequity
- **Demonstrate responsible** use of demographic data
- **Foster inclusive** practices in data science

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- **SoundCloud** for collaboration and inspiration
- **Music industry data sources** (anonymized and synthesized for educational use)
- **Open source community** for the tools that make this analysis possible

---

*Ready to explore DEI in the music industry through data? Choose your level and start analyzing!* 🎵📊
