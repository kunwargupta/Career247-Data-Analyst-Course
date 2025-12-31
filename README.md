# Career247 Data Analyst Course - Learning Journey

## Overview

This repository documents my comprehensive learning journey through the **Career247 Data Analyst Course**. It showcases the practical skills, projects, and in-depth knowledge I've acquired in data analysis, Python programming, and data visualization.

**Course Provider:** Career247  
**Duration:** Intensive, Hands-on Learning  
**Focus Areas:** Python, Data Structures, Data Analysis, Visualization, and Real-world Applications

---

## Course Structure & Learning Modules

### 1. **Python Fundamentals (Lab 1)**
- **Syntax & Structure**
  - Proper indentation and code comments
  - Line continuation and multi-line statements
  - Python best practices

- **Data Types & Type System**
  - Primitive data types: `int`, `float`, `str`, `bool`
  - Dynamic typing in Python
  - Type conversion and casting (implicit vs explicit)
  - Using `type()` and `isinstance()` functions

- **Control Flow**
  - Conditional statements (`if`, `elif`, `else`)
  - Nested conditions for complex logic
  - Loop constructs (`for` loops with `range()`, `while` loops)
  - Loop control statements: `break`, `continue`, `pass`
  - For-else and while-else constructs

- **Built-in Functions**
  - `len()`, `max()`, `min()`, `sum()`, `sorted()`, `round()`, `abs()`
  - List operations and aggregations

- **Input/Output & String Formatting**
  - User input with `input()`
  - Print formatting with f-strings and `.format()`
  - Precise decimal place control

### 2. **Data Structures (Lab 2)**

#### Lists
- Creation, indexing, and slicing
- List methods: `append()`, `extend()`, `insert()`, `pop()`, `remove()`, `sort()`
- List comprehensions for elegant and efficient transformations
- List slicing with negative indices and step values

#### Tuples
- Declaration and immutability (key characteristic)
- Use cases: function returns, dictionary keys, data protection
- Tuple unpacking and multi-variable assignment
- `zip()` function for pairing iterables

#### Sets
- Creating sets and removing duplicates
- Membership testing with `in` operator
- Set operations: `add()`, `remove()`, `discard()`
- Set operations: union (|), intersection (&), difference (-), symmetric difference (^)
- Use case: deduplication and membership checks

#### Dictionaries
- Key-value pair creation and access
- Dictionary methods: `get()`, `items()`, `keys()`, `values()`
- Updating and deleting entries
- Nested dictionaries for hierarchical data
- Dictionary comprehensions for rapid creation
- Checking key existence with `in` operator

#### Applied Logic with Collections
- Frequency mapping using dictionaries
- Common elements between lists/sets
- Complex data manipulation combining multiple structures

### 3. **Exception Handling & Standard Library (Lab 3)**

#### Exception Handling
- Try-except blocks for error management
- Multiple exception handling
- Else clause for successful execution
- Finally clause for resource cleanup
- Raising custom exceptions
- Custom exception classes
- Assertion statements for debugging

#### Standard Library Modules

**Math Module**
- Circle area calculations using `math.pi`
- `math.factorial()` for combinatorics
- `math.gcd()` for greatest common divisor
- Compound interest calculations

**Random Module**
- Random integer generation with fixed seeds for reproducibility
- `random.shuffle()` for randomizing sequences
- `random.sample()` for unique random selections
- Simulating real-world scenarios (coin flips, dice rolls)

**DateTime Module**
- Current date and time retrieval
- Timedelta for date arithmetic
- ISO format date parsing and formatting
- Chronological sorting of dates
- Custom date formatting with `strftime()`

### 4. **NumPy & Pandas Fundamentals (Lab 4)**

#### NumPy - Numerical Computing
- **Array Creation**
  - `np.array()`, `np.zeros()`, `np.ones()`
  - `np.arange()` and `np.linspace()` for sequences
  - 2D array creation and reshaping

- **Array Properties**
  - `shape`, `ndim`, `dtype` attributes
  - Type casting with `astype()`

- **Element-wise Operations**
  - Arithmetic operations: addition, subtraction, multiplication, division
  - Broadcasting: operating on arrays of different shapes
  - Scalar operations

- **Aggregations**
  - Overall: `sum()`, `mean()`, `std()`
  - Axis-specific: row-wise and column-wise aggregations
  - Statistical analysis on multi-dimensional data

#### Pandas - Data Manipulation
- **Series Creation**
  - From lists and dictionaries
  - Custom indexing
  - Label-based and position-based access
  - Slicing with labels and positions

- **DataFrame Fundamentals**
  - Creation from dictionaries and list of dictionaries
  - `head()`, `tail()`, `info()`, `describe()`
  - Column and row selection

- **Data Selection with `loc` and `iloc`**
  - Label-based selection with `loc[]`
  - Position-based selection with `iloc[]`
  - Boolean indexing for conditional filtering

- **Column Operations**
  - Adding new columns with conditions
  - Removing columns with `drop()`
  - Renaming columns with `rename()`
  - Updating values based on conditions

- **Filtering & Sorting**
  - Multi-condition filtering
  - Sorting by single and multiple columns
  - Ascending and descending order

- **Missing Data Handling**
  - Detecting missing values: `isnull()`, `isna()`
  - Dropping rows with `dropna()`
  - Filling missing values with `fillna()`
  - Mean/median imputation

### 5. **Data Analysis & Visualization (Lab 5)**

#### Case Study: Myntra Pants Dataset

**Data Loading & Exploration**
- Loading CSV files into DataFrames
- Understanding dataset shape and structure
- Column inspection and data types

**Data Cleaning**
- Checking for missing values across columns
- Converting columns to appropriate numeric types
- Handling inconsistencies in price and discount data
- Clipping values to valid ranges
- Creating new derived columns (e.g., net discount, discount amount)

**Feature Engineering**
- `pd.cut()` for binning ratings into categories
- `pd.qcut()` for quantile-based binning (quartiles)
- Creating composite scores (value-score combining ratings and discount)
- Price-to-MRP ratios and percentage calculations

#### GroupBy & Aggregations
- Grouping by single columns (e.g., brand)
- Computing multiple aggregations: mean, sum, count
- Multi-level groupBy with multiple columns
- Using `agg()` for custom aggregations
- Multi-index DataFrames

#### Pivot Tables
- Creating pivot tables with specified:
  - Index (rows)
  - Columns
  - Values and aggregation functions
- Analyzing data from multiple perspectives

#### Merging & Joining
- Creating mapping DataFrames
- Merging DataFrames on common columns
- Preserving and enriching data through joins

#### Visualization with Pandas
- **Bar Charts**: Top brands by product count
- **Histograms**: Distribution of net discount
- **Pie Charts**: Market segment representation
- **Line Charts**: Price trends across rating bands
- **Horizontal Bar Charts**: Top brands by metrics

#### Matplotlib Introduction
- Direct plotting with `matplotlib.pyplot`
- Scatter plots for relationship analysis
- Customization: alpha, labels, titles
- Subplots for multi-panel visualizations
- Figure management and layout

---

## Key Skills Acquired

### Programming Competencies
✅ Python syntax and best practices  
✅ Object-oriented and functional programming paradigms  
✅ Exception handling and debugging  
✅ Working with multiple data structures efficiently  

### Data Manipulation
✅ Data loading and exploration  
✅ Data cleaning and transformation  
✅ Handling missing and inconsistent data  
✅ Feature engineering and derived columns  
✅ GroupBy operations and aggregations  

### Analysis & Insights
✅ Statistical computations (mean, median, std, percentiles)  
✅ Multi-dimensional data analysis  
✅ Trend identification and pattern recognition  
✅ Comparative analysis across categories  

### Visualization
✅ Creating publication-quality plots  
✅ Choosing appropriate chart types  
✅ Data-driven storytelling through visuals  
✅ Multi-panel layouts and subplots  

---

## Labs & Practice Files

### Lab 1: Python Fundamentals
- File: `Python_Lab1.ipynb`
- Topics: Syntax, variables, data types, control flow, built-ins

### Lab 2: Data Structures
- File: `Python_Lab2.ipynb`
- Topics: Lists, tuples, sets, dictionaries, comprehensions

### Lab 3: Exception Handling & Libraries
- File: `Python_Lab3.ipynb`
- Topics: Try-except, math, random, datetime modules

### Lab 4: NumPy & Pandas Basics
- File: `Python_Lab4.ipynb`
- Topics: Array operations, Series, DataFrame fundamentals

### Lab 5: Data Analysis & Visualization
- File: `Python_Lab5.ipynb`
- Topics: Myntra case study, groupBy, pivot tables, plotting

---

## Real-World Applications

This course emphasizes practical, real-world applications:

1. **E-commerce Analytics** (Myntra dataset)
   - Brand performance analysis
   - Price optimization insights
   - Rating and review impact

2. **Data Quality Management**
   - Identifying and handling missing values
   - Detecting and correcting data inconsistencies
   - Data validation techniques

3. **Business Intelligence**
   - Creating executive summaries through pivot tables
   - Generating actionable insights from raw data
   - Visual reporting for stakeholders

4. **Statistical Analysis**
   - Distribution analysis
   - Correlation and trend identification
   - Comparative metrics across categories

---

## Learning Outcomes

By completing this course, I have demonstrated proficiency in:

1. **Foundation**: Strong grasp of Python fundamentals, data types, and control structures
2. **Data Structures**: Expert-level understanding of when and how to use different collections
3. **Problem-Solving**: Ability to break down complex data problems into manageable steps
4. **Data Analysis**: End-to-end analysis from raw data to actionable insights
5. **Communication**: Presenting data findings through clear visualizations
6. **Best Practices**: Writing clean, efficient, and maintainable code

---

## Technologies & Tools

- **Python 3.x** - Core programming language
- **NumPy** - Numerical computing and array operations
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Jupyter/Colab** - Interactive development environment

---

## How to Use This Repository

1. **Explore the Labs**: Navigate through each lab notebook to see:
   - Exercise descriptions
   - Implemented solutions
   - Output and results

2. **Study the Concepts**: Review the detailed explanations of each topic

3. **Practice**: Use these materials as reference for your own data analysis projects

4. **Reference**: Bookmark specific labs for quick code snippets and syntax reminders

---

## Future Enhancements

As I continue my data analysis journey, I plan to:
- [ ] Add more complex case studies
- [ ] Implement machine learning algorithms
- [ ] Create advanced visualization dashboards
- [ ] Document business intelligence projects
- [ ] Build predictive modeling examples

---

## Reflection & Takeaways

The Career247 Data Analyst Course provided comprehensive training in the fundamental tools and techniques used by professional data analysts. The emphasis on hands-on practice through multiple labs helped solidify theoretical concepts into practical skills. The progression from basic Python to data manipulation to visualization created a logical learning path that builds towards real-world data analysis capabilities.

Key insights:
- **Data quality** is paramount; much of analysis is about cleaning and preparing data
- **Visualization** bridges the gap between technical analysis and business understanding
- **Code efficiency** matters when working with large datasets
- **Best practices** in writing clean code pay off throughout a project lifecycle

---

## Contact & Additional Resources

- **Author**: Kunwar Ji Gupta
- **GitHub**: [@kunwargupta](https://github.com/kunwargupta)
- **Course**: Career247 Data Analyst Certification Program

---

## License

This repository is for educational purposes. The code and documentation are provided as-is for learning and reference.

---

**Last Updated**: December 31, 2025  
**Status**: Actively Learning & Building
