# Educational Inequality and ACT Performance

This project addresses inequality of educational opportunity in U.S. high schools.Using data science methods, this project analyzes 
average student performance on the ACT or SAT exams that students take as part of the college application process. Visualizations and statistical tests are used to support the findings and provide insights into range of school performance on these exams and the school performance associated with socioeconomic factors.

---

## Project Overview

This project examines how socio-economic factors affect ACT scores, using school data on income, parental education, and reduced-price lunch participation. The analysis shows that higher income and education levels, along with lower economic disadvantage, are strongly linked to better ACT performance. These results suggest that targeted support for disadvantaged schools could help reduce achievement gaps.
- **Objective:** The goal of the project s to find out whether the average ACT scores of the school is related to socio-economic factors.
- **Domain:** Education
- **Key Techniques:** Simple Linear Regression,Multi Linear regression.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** Edgap dataset : https://www.edgap.org
              School Information data : https://github.com/brian-fischer/DATA-5100
              School data : https://nces.ed.gov/programs/edge/
- **Description:** Brief overview of the dataset features, size, and format

---

## Analysis

The analysis was carried out in a Jupyter notebook. The workflow begins with data preparation (cleaning and merging datasets), followed by exploratory analysis (descriptive statistics and visualizations). Next, the modeling and hypothesis testing notebook fits regression models and evaluates predictors, and finally, the results notebook summarizes findings and produces report-ready figures. Running the notebooks in this order fully reproduces the results.

---

## Results
The socio-economic features has strong influence on ACT scores, especially reduced lunch feature is the strongest predictor .

---

## Authors

- Prithika Kandasamy - https://github.com/prithika029

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used 
	Tool : Jupyter notebook 
	Libraries : pandas, numpy, matplotlib, pyplot, seaborn
- Inspiration or collaborators - https://github.com/brian-fischer/DATA-5100/tree/main

