# DEI in Music Industry - Data Analysis Workshop

Hands-on Workshop on Diversity, Equity, and Inclusion (DEI) in the music industry as part of a CodePub in collaboration with SoundCloud.

## Overview

This workshop provides a comprehensive exploration of DEI challenges in the music industry through data analysis. Using real-world inspired data from streaming platforms, we'll examine representation patterns, identify biases, and develop data-driven solutions for promoting equity.

## Workshop Structure

The workshop is designed with three progressive levels to accommodate different skill levels:

### 🟢 **Beginner Level** 
**Focus**: Basic data exploration and visualization
- **File**: `notebooks/beginner/beginner_dei_analysis.ipynb`
- **Skills**: Pandas basics, simple visualizations, descriptive statistics
- **Duration**: 60-90 minutes
- **Topics**:
  - Loading and exploring datasets
  - Gender and ethnic representation analysis
  - Creating basic charts (pie charts, bar charts)
  - Calculating summary statistics
  - Identifying patterns in success metrics

### 🟡 **Intermediate Level**
**Focus**: Statistical analysis and advanced visualizations
- **File**: `notebooks/intermediate/intermediate_dei_analysis.ipynb`
- **Skills**: Statistical testing, correlation analysis, interactive plots
- **Duration**: 90-120 minutes
- **Prerequisites**: Completed beginner level or equivalent pandas/matplotlib experience
- **Topics**:
  - Statistical hypothesis testing (t-tests, ANOVA)
  - Correlation analysis and heatmaps
  - Interactive visualizations with Plotly
  - Cross-tabulation and demographic breakdowns
  - Confidence intervals and significance testing

### 🔴 **Advanced Level**
**Focus**: Machine learning and algorithmic fairness
- **File**: `notebooks/advanced/advanced_dei_analysis.ipynb`
- **Skills**: Machine learning, bias detection, fairness metrics
- **Duration**: 2-3 hours
- **Prerequisites**: Intermediate Python, basic ML concepts, statistics background
- **Topics**:
  - Predictive modeling for artist success
  - Feature engineering and importance analysis
  - Bias detection in ML models
  - Clustering analysis (artist archetypes)
  - Fairness metrics and equity scoring
  - Building recommendation systems

## Dataset

The workshop uses a synthetic dataset (`data/music_industry_dei_data.csv`) containing information about 40 diverse artists including:

- **Demographics**: Gender, ethnicity, country
- **Career Info**: Genre, years active, label type, album count
- **Success Metrics**: Monthly listeners, total streams, followers, awards
- **Platform Data**: Spotify and SoundCloud follower counts

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
- **Learn progressive data science techniques** from basic stats to ML
- **Gain practical experience** with real-world datasets
- **Build awareness** of algorithmic bias and fairness
- **Create actionable insights** for promoting equity

## Workshop Flow Recommendations

### For Individual Learning:
1. Start with the beginner notebook regardless of skill level
2. Progress through levels sequentially
3. Take breaks between levels to reflect on insights
4. Experiment with the code and try variations

### For Group Workshops:
1. **Mixed Groups**: Assign levels based on experience
2. **Same Level**: All participants work on the same level
3. **Progressive Sessions**: Run multiple sessions covering different levels
4. **Collaborative**: Advanced participants mentor beginners

## Key Insights to Explore

Participants will discover and analyze:
- **Representation gaps** across demographics
- **Success pattern differences** between groups
- **Genre segregation** and its implications
- **Label type distribution** and access to resources
- **Algorithmic bias** in predictive models
- **Fairness metrics** and their interpretation

## Technical Requirements

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

## Support

If you encounter issues:
1. Check that all required packages are installed
2. Ensure you're using Python 3.7+
3. Try restarting your Jupyter kernel
4. Open an issue on GitHub with error details

## Acknowledgments

- **SoundCloud** for collaboration and inspiration
- **Music industry data sources** (anonymized and synthesized for educational use)
- **Open source community** for the tools that make this analysis possible

---

*Ready to explore DEI in the music industry through data? Choose your level and start analyzing!* 🎵📊
