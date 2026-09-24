# NumPy Industry-Based Analytics

**Practical applications of Python and NumPy to real-world numerical and analytical problems.**

<img width="1672" height="941" alt="project thumbnail" src="https://github.com/user-attachments/assets/04f4da4e-5020-4e9f-93ce-e736c6b81a8f" />

---

##  About This Repository

This repository documents my hands-on learning and application of **Python and NumPy** through a series of industry-based numerical computing projects.

The projects were designed to move beyond simply learning Python syntax and focus on applying numerical concepts to practical problems across different domains.

The work covers:

-  **Business Analytics**
-  **Education Analytics**
-  **Engineering & Scientific Computing**
-  **Renewable Energy**

Across the projects, I followed a practical analytical workflow:

> **Understand the problem → Represent the data → Perform the calculation → Inspect the result → Interpret the findings**

The goal was not only to produce numerical outputs, but also to understand what those outputs mean within a real-world context.

---

#  Projects

## 1.  Business Analytics - Sales Performance Calculator

<img width="1054" height="719" alt="Screenshot 2026-09-24 121112" src="https://github.com/user-attachments/assets/c4a94021-3d73-43b9-8329-659005261a1a" />

**Focus:** Retail Sales Analysis

This project uses NumPy to analyse daily sales recorded over one week for a hypothetical retail business.

### Objective

The objective was to use numerical analysis to understand weekly sales performance and examine the potential effect of a hypothetical 10% increase in sales.

### Analysis Performed

- Created a NumPy array containing daily sales
- Inspected the array type and shape
- Calculated total weekly sales
- Calculated average daily sales
- Applied a hypothetical 10% increase using element-wise operations
- Calculated the difference between adjusted and original sales
- Interpreted the results from a business perspective

### NumPy Concepts

```python
np.array()
np.sum()
np.mean()
```

The project also demonstrates:

- Scalar multiplication
- Element-wise subtraction
- Array inspection
- Numerical interpretation

### Key Learning

The exercise demonstrated the difference between **total performance** and **average performance**. While total sales describe the overall revenue generated during the week, average daily sales provide an indication of the typical daily performance.

---

## 2.  Education Analytics - Student Performance Analysis

<img width="1323" height="725" alt="Screenshot 2026-09-24 120857" src="https://github.com/user-attachments/assets/fe73bcc6-30dd-4091-9ea4-acde563e0023" />

**Focus:** Student Scores and Variation

This project applies NumPy to the analysis of student assessment scores.

### Objective

The objective was to understand overall student performance while examining how individual scores differ from the group average.

### Analysis Performed

- Created and inspected a NumPy array of student scores
- Calculated the mean score
- Calculated individual deviations from the mean
- Identified positive and negative deviations
- Squared the deviations
- Calculated the sum of squared deviations
- Connected the calculations to the conceptual process of calculating standard deviation
- Interpreted the findings in an education analytics context

### NumPy Concepts

```python
np.array()
np.mean()
np.sum()
```

The project also demonstrates:

- Element-wise subtraction
- Array exponentiation
- Deviation analysis
- Numerical interpretation

### Key Learning

The project demonstrated why an average alone may not provide a complete picture of student performance.

Examining deviations provides additional information about how individual scores compare with the group average and provides a foundation for understanding measures of variability such as standard deviation.

---

## 3.  Engineering & Scientific Computing - Trigonometric Series

<img width="1699" height="705" alt="Screenshot 2026-09-24 120156" src="https://github.com/user-attachments/assets/7a9cca43-40f8-419a-ac29-3ec1f51855e9" />

**Focus:** Numerical Sequences and Mathematical Computation

This project explores a mathematical series using NumPy and examines how the resulting numerical value changes as the number of terms increases.

### Objective

The objective was to work with angles, trigonometric functions, numerical sequences, element-wise operations, and partial sums.

### Analysis Performed

- Defined an angle of 30 degrees
- Converted the angle from degrees to radians
- Generated numerical sequences using `np.arange()`
- Calculated the sine of the angle
- Constructed individual series terms using element-wise division
- Calculated the sum of the generated terms
- Repeated the experiment using progressively larger numbers of terms
- Compared the resulting partial sums

### NumPy Concepts

```python
np.radians()
np.sin()
np.arange()
np.sum()
```

The project also demonstrates:

- Element-wise operations
- Broadcasting
- Numerical sequences
- Mathematical series
- Partial-sum analysis

### Key Learning

The experiment demonstrated how NumPy can be used to translate mathematical expressions into computational experiments and examine how numerical results change as additional terms are introduced.

---

## 4.  Renewable Energy - Solar Grid Numerical Experiment
<img width="1397" height="734" alt="Screenshot 2026-09-24 121225" src="https://github.com/user-attachments/assets/6b73cc12-a66e-46d3-ab96-d6122d33def8" />

**Focus:** Solar Power Output and Temperature Effects

For the bonus challenge, I developed a small numerical experiment based on a renewable-energy scenario.

The experiment models the performance of a **150 kW solar array** under changing ambient temperatures.

### Objective

The objective was to use NumPy to model how changes in ambient temperature could affect solar-array efficiency and estimated power output.

### Analysis Performed

The experiment involved:

- Creating a numerical dataset
- Generating a sequence of operating hours
- Representing temperature values using NumPy arrays
- Calculating temperature deviations
- Modelling temperature-related efficiency losses
- Estimating hourly solar power output
- Calculating mean hourly output
- Calculating total energy generation
- Estimating energy loss relative to rated capacity
- Interpreting the results within a renewable-energy context

### NumPy Concepts

```python
np.array()
np.arange()
np.mean()
np.sum()
np.subtract()
np.multiply()
```

The project also demonstrates:

- Element-wise array operations
- Numerical modelling
- Mathematical relationships
- Scenario-based analysis
- Data interpretation

### Example Results

| Metric | Result |
|---|---:|
| Solar array capacity | 150 kW |
| Mean hourly output | ~145.45 kW |
| Total generation | ~1,745.40 kWh |
| Theoretical generation | 1,800 kWh |
| Estimated energy loss | ~54.60 kWh |

*The values above are based on the assumptions and calculations used in the numerical experiment.*

### Key Learning

This project demonstrated how fundamental NumPy operations can be combined to create a simple numerical model of a real-world engineering problem.

---

#  Key Skills Demonstrated

Through these projects, I gained practical experience with:

### Python & NumPy

- NumPy arrays
- Array creation and inspection
- `np.sum()`
- `np.mean()`
- `np.arange()`
- `np.radians()`
- `np.sin()`
- `np.add()`
- `np.subtract()`
- `np.multiply()`
- Element-wise division
- Broadcasting
- Mathematical sequences
- Numerical modelling

### Analytical Skills

- Data representation
- Numerical calculations
- Deviation analysis
- Mathematical reasoning
- Result inspection
- Interpretation of numerical outputs
- Translating calculations into real-world meaning

### Applied Domains

- Business analytics
- Education analytics
- Engineering
- Scientific computing
- Renewable energy

---

#  Analytical Workflow

A major focus of this project was developing the ability to approach numerical problems systematically.

```text
        REAL-WORLD PROBLEM
                ↓
        REPRESENT THE DATA
                ↓
       PERFORM CALCULATIONS
                ↓
          INSPECT RESULTS
                ↓
       INTERPRET THE FINDINGS
                ↓
       COMMUNICATE THE RESULT
```

This workflow reinforces an important principle:

> **Don't just run the code. Understand the calculation. Don't just get the output. Interpret it.**

---

#  Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Programming and numerical analysis |
| **NumPy** | Numerical computing and array operations |
| **Jupyter Notebook** | Interactive coding and documentation |
| **GitHub** | Version control and project documentation |

---

#  Repository Structure

```text
numpy-industry-based-analytics/
│
├── README.md
│
└── notebooks/
    ├── 01_sales_performance_calculator.ipynb
    ├── 02_student_performance_analysis.ipynb
    ├── 03_trigonometric_series_analysis.ipynb
    └── 04_renewable_energy_numerical_experiment.ipynb
```

---

#  Purpose of the Portfolio

This repository is part of my growing technical portfolio and documents my practical application of **Python and NumPy to numerical and analytical problems**.

The projects demonstrate how numerical computing can be applied beyond programming exercises to problems involving:

**Business → Education → Engineering → Renewable Energy**

The emphasis throughout the work is on connecting:

> **Data → Calculation → Result → Interpretation**

---

#  Author

### Chukwuemeka Somtochukwu Promise

GitHub: **[Promise-Steve](https://github.com/Promise-Steve)**

---

#  Technologies & Topics

`Python` `NumPy` `Jupyter Notebook` `Data Analytics` `Numerical Computing` `Scientific Computing` `Business Analytics` `Education Analytics` `Engineering` `Renewable Energy` `Problem Solving`

---

 **Thanks for visiting this repository. Feel free to explore the notebooks and follow my journey as I continue building practical skills in Python, data analytics, and numerical computing.**
