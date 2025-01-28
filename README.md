# Football Match Analysis System 🎯⚽

A sophisticated computer vision system for analyzing football matches, providing detailed insights into team tactics, ball possession, and spatial dynamics. This project uses advanced AI techniques to track and analyze various aspects of football matches.

![Football Analysis Demo](images/demo.gif)

## 🌟 Key Features

### 1. Team Side Analysis 🏃‍♂️
- Automatic detection of team defending sides
- Team color and jersey identification
- Player position tracking and mapping
- Real-time spatial distribution analysis

### 2. Ball Possession Analysis ⚽
- Advanced ball tracking algorithms
- Team-specific possession statistics
- Possession visualization with custom graphics
- Frame-by-frame possession tracking

### 3. Attack Zone Analysis 📊
- Pitch division into strategic zones
- Team-specific attack pattern recognition
- Zone-based possession statistics
- Visual heat maps of attacking movements

### 4. Penalty Area Encounter Analysis 🎯
- Tracking of penalty area entries
- Ball movement analysis in dangerous areas
- Team-specific encounter statistics
- Offensive efficiency metrics

## 🛠️ Technology Stack

- **Python 3.9+**
- **OpenCV** for video processing and visualization
- **NumPy** for numerical computations
- **Supervision** for sports analytics tools
- **Jupyter Notebook** for interactive development

## 📋 Prerequisites

```bash
- Python 3.9 or higher
- OpenCV-Python
- NumPy
- Supervision
- Jupyter Notebook
```

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/Unal-The-Engineer/football-match-analysis-project.git
```

2. Create and activate virtual environment:
```bash
python -m venv futbol_env
source futbol_env/bin/activate  # On Windows: futbol_env\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Open the Jupyter Notebook:
```bash
jupyter notebook football_ai.ipynb
```

2. Update the video path in the configuration:
```python
video_path = "path/to/your/football/video.mp4"
```

3. Run the analysis cells sequentially to get:
- Team side detection
- Ball possession statistics
- Attack zone analysis
- Penalty area encounters

## 📊 Visualizations

### Possession Statistics
- Team-wise possession percentages
- Interactive possession bars
- Color-coded team statistics

### Zone Analysis
- Attack zone distribution
- Team-specific heat maps
- Horizontal zone divisions

## ⚙️ Configuration

Key parameters in the notebook:
```python
CONFIG = {
    'stride': 30,
    'debug': True,
    'possession_threshold': 3,
    'min_confidence': 0.3
}
```

## 📈 Sample Results

- **Ball Possession:**
  - Red Team: 60.5%
  - Yellow Team: 39.5%

- **Attack Zones:**
  - Left Wing: 35.3%
  - Center: 64.7%
  - Right Wing: 0.0%

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Author

- **Unal Buyukkoroglu** - *Initial work* - [GitHub Profile](https://github.com/Unal-The-Engineer)

## 🙏 Acknowledgments

- Thanks to the Roboflow for computer vision tools
- Special thanks to the open-source community



Unal Buyukkoroglu - [ubuyukkoroglu@outlook.com]

Project Link: [https://github.com/Unal-The-Engineer/football-match-analysis-project]