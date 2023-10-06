# Prediction of Mortality Rate in Liver Cirrhosis

## Description
- This project investigates the features that are associated with liver cirrhosis mortality rate.
- ML models selection, evalution and tuning were implemented to assess prediction of highest accuracy.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Collection](#data-collection)
- [Methodology](#methodology)
- [Results](#results)
- [Discussion](#discussion)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact Information](#contact-information)

## Installation
1. Clone the repository: `git clone https://github.com/josefroslan/livercirrhosis.git`
2. Navigate to the project folder: `cd livercirrhosis`
3. Install required packages: `pip install -r requirements.txt`

## Usage
- Use Jupyter notebook to read `cirrhosis.ipynb`
- Load `cirrhosis.csv` to your dataframe by importing pandas library
- Example: `df = df.read_csv('cirrhosis.csv')`

## Data Collection
- The liver cirrhosis dataset was obtained from [UCI Machine Learning Repository]([https://www.moviereviewsdataset.com](https://archive.ics.uci.edu/dataset/878/cirrhosis+patient+survival+prediction+dataset-1)).
- Data preprocessing involved:
  - dropping missing values
  - converting `Age` from days into years
  - rename columns
  - feature transformations of continuous data into categorical data
  - hot encoding for modelling assessment

## Methodology
- Exploratoy data analysis (EDA)
- Hypotesis testing
- Correlation heatmap
- Model selection, evaluation and tuning

## Results
- Logistic regression with hyperparameter tuning achieved a highest accuracy of 80% compared to other models

## Discussion
- According to this study, almost 90% of the participants were females hence the sample does not represent the actual population of patients with liver disease. Therefore, it is recommended to repeat the trial with equal number of male and female participants.
- During the analysis, it is uncertain about the status of patient's censored information. Further collection of data in patients with censored information will be useful to explore other possible factors that may contribute to this research.
- Additional data such as medical imaging (eg: MRI, CT scan, ultrasound), concurrent illnesses (eg: cholethiasis, gallstone, portal hypertension etc) and laboratory investigations maybe useful to improve the accuracy of prediction

## Contributing
Contributions are welcome! If you'd like to contribute, let's have a chat!

## License
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Acknowledgments
- Thanks to the Python libraries for significant contribution to the project.

## Contact Information
For questions or feedback, feel free to reach out to me.
