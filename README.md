# AlgoInvest&Trade

## Brute Force

Tests every possible combination of the 20 stocks (2^n combinations) and
keeps the most profitable one that fits within the 500 € budget.

------------------------------------------------------------------------

## Optimized

A greedy approach inspired by the knapsack problem: it sorts the most
profitable stocks and builds the ideal portfolio without exceeding the
budget.

------------------------------------------------------------------------

## Exploration Report

After verifying the accuracy of Sienna's calculations, it was found that
her solution was not optimal. A new algorithm based on a greedy approach
was developed, making it possible to obtain a more profitable solution
in a shorter computation time, although without guaranteeing global
optimality.

------------------------------------------------------------------------

## Prerequisites

-   **Python 3** installed on your machine
-   Internet connection

------------------------------------------------------------------------

## Installation and Usage

### 1. Clone the Project Repository

Open a terminal, navigate to the directory of your choice, and clone the
repository:

``` bash
git clone https://github.com/mouquettom/algoinvest.git
cd algoinvest
```

### 2. Install the Packages

``` bash
pip install -r tom_mouquet_3_diapositives_042025/requirements.txt
```

### 3. Run the Scripts

From the root of the repository:

``` bash
python tom_mouquet_1_bruteforce_042025/bruteforce.py
python tom_mouquet_2_optimized_042025/optimized.py
python tom_mouquet_3_diapositives_042025/correction_dataset_01_algo_glouton.py
python tom_mouquet_3_diapositives_042025/correction_dataset_02_algo_glouton.py
```

------------------------------------------------------------------------

## Author

@tom_mouquet

Project developed as part of the OpenClassrooms **Développeur
d'application Python** training program.
