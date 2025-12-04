# Python Final Project: Old Yeller Text/Sentiment Analysis

## Project Overview
This project will be conducting text analysis on Old Yeller by Fred Gipson. I will be modeling the sentiment analysis by chapter, character, and plot point. There wll be a line graph of sentiment by chapter, showing how the sentiment changes throughout the course of the novel.

## Project Structure
```
python_final_project/
├── data_raw/                 # Raw, unprocessed data files
│   ├── Old Yeller.csv       # Raw book text file
├── notebook.ipynb          # Main analysis notebook
└── README.md               # This file
```

## Requirements
- Python 3.7+
- pandas
- matplotlib
- numpy
- jupyter (for local execution)

## Installation and Setup

### Local Execution
1. Clone this repository:
   ```bash
   git clone [https://github.com/aagrayFS/Math_120_Final_Project.git]
   cd python_final_project
   ```

2. Install required packages (if needed):
   ```bash
   pip install pandas matplotlib numpy jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

### Google Colab Execution
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `notebook.ipynb` file or connect to your GitHub repository
3. Run the first cell to automatically set up the environment

## Data Description
- **Old Yeller**: Contains text file of the book Old Yeller
- 
## Analysis Features
- Data loading and cleaning
- Sentiment calculatation based on chapter, character, and plot point
- Summary statistics calculation
- Data visualization with matplotlib
- Modular code organization

## Key Learning Objectives Demonstrated
- File I/O operations with pandas
- Data cleaning and preprocessing
- Statistical analysis
- Data visualization
- Function creation and modular programming
- Environment compatibility (local vs. cloud)
- Sentiment analysis

## Usage
Run all cells in `notebook.ipynb` sequentially. The notebook will:
1. Set up the environment automatically
2. Load and clean the raw data
3. Perform statistical analysis
4. Perform Sentiment Analysis
5. Generate visualizations

## Author
[Your Name]  
[Course Name] - [Semester/Year]
