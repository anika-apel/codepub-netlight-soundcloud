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

This is a group workshop. Meet up in groups of three people with the same skill level and start with your workshop. Collaboration is key here to tackle the tasks and explore different ideas. 
At the end, we will collect key findings and results on this Miro board to share it with everyone. 

This is a safer space, you can ask any questions. We and all other participants are here to support each other ✨

### 🟢 **Beginner Level** 
**Focus**: Basic data exploration and visualization of listening behavior of artists
- **File**: `notebooks/beginner/beginner_dei_analysis.ipynb`
- **Duration**: 75 minutes

### 🟡 **Intermediate Level**
**Focus**: Data exploration and statistical analysis of comment behavior of artists
- **File**: `notebooks/intermediate/intermediate_dei_analysis.ipynb`
- **Duration**: 75 minutes
- **Prerequisites**: Basic knowledge of Pandas, numpy and plotting libraries

### 🔴 **Advanced Level**
**Focus**: Recommendations and Predictions for listeners and artists
- **File**: `notebooks/advanced/advanced_dei_analysis.ipynb`
- **Duration**: 75 minutes

## Dataset

The workshop uses an anonymized version of SoundClouds data containing data about listening & engagement behavior of artists. 
In total, it contains 5 different datasets.
The first 4 datasets describe the listening behavior of artists in 4 different genres.
The fifth dataset describes the engagement behavior of artists.

You can find a legend explaining all fields in [legends.csv](data/legend.csv).

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Basic familiarity with Python (for beginner level)

<details>
  <summary>Detailed setup guide:</summary>

1. Install Python 3.7+ and Jupyter Notebook
  - [See official python installer](https://www.python.org/downloads/)
  - Use a package manager: 
    - MacOS: `brew install python`
    - Linux: use your distribution's package manager (e.g. `apt` for Ubuntu/Debian) -`sudo apt update && sudo apt install python3 python3-pip`
    - Windows: Use Chocolately or Scoop - `choco install python` or `scoop install python`
2. Confirm installation worked as expected: `python --version` or `python3 --version`
</details>


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
<details>
  <summary>If you installed python through brew, you might get an error message.</summary>

If you get the error message `error: externally-managed-environment`, you can take these steps:
  ```bash
  python3 -m venv codepubenv
  source codepubenv/bin/activate
  python3 -m pip install -r requirements.txt
  python3 -m ipykernel install --user --name=codepubenv --display-name="codepub environment"
  jupyter notebook
  ```
Once you've opened a particular notebook, e.g. `beginner_dei_analysis.ipynb` in your browser, make sure to select the right kernel:
Go to Kernel > Change kernel and select "codepub environment". This links the notebook to your environment's isolated dependencies.
</details>

3. Launch Jupyter:
```bash
jupyter notebook
```

4. Choose your level and open the corresponding notebook:
   - Beginner: `notebooks/beginner/beginner_dei_analysis.ipynb`
   - Intermediate: `notebooks/intermediate/intermediate_dei_analysis.ipynb`
   - Advanced: `notebooks/advanced/advanced_dei_analysis.ipynb`

### Overview of Python Packages

- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `matplotlib` - Basic plotting
- `seaborn` - Statistical visualization
- `plotly` - Interactive visualizations
- `scipy` - Statistical functions
- `scikit-learn` - Machine learning (advanced level)
- `jupyter` - Notebook environment


## Ethical Considerations

This workshop aims to:
- **Promote awareness** of DEI issues in creative industries
- **Encourage data-driven** approaches to addressing inequity
- **Demonstrate responsible** use of demographic data
- **Foster inclusive** practices in data science

## Acknowledgments

- **SoundCloud** for collaboration and inspiration
- **Open source community** for the tools that make this analysis possible

---

*Ready to explore DEI in the music industry through data? Choose your level and start analyzing!* 🎵📊
