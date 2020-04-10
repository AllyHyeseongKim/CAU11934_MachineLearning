# CAU11934_MachineLarning

This is for study and assignment of the assignment of the course No.11934(2020-1).


## Assignment01

### 1. Google Classroom

### 2. Github

### 3. Colab


## Assignment02: Linear Regression

### 1. Data

- generate a set of $`m`$ point pairs $`\{ (x^{(i)}, y^{(i)}) \}_{i = 1}^m`$ from random perturbations using `random` function based on a linear function that you define
- $`\hat{y} = a x + b`$ where $`a, b \in \mathbb{R}`$
- $`y = \hat{y} + n`$ where $`n \sim \mathcal{N}(0, \sigma^2)`$ is drawn from the normal distribution with mean $`0`$ and standard deviation $`\sigma`$
- you can choose $`m, a, b`$ and $`\sigma > 0`$

### 2. Linear Model

- $`h_\theta(x) = \theta_0 + \theta_1 x`$, $`\quad`$ where $`\theta = (\theta_0, \theta_1)`$ and $`\theta_0, \theta_1 \in \mathbb{R}`$

### 3. Objective Function

- $`J(\theta) = \frac{1}{2 m} \sum_{i=1}^m (h_\theta(x^{(i)}) - y^{(i)})^2`$

### 4. Gradient Descent
 
- $`\theta_0^{(t+1)} \coloneqq \theta_0^{(t)} - \alpha \frac{1}{m} \sum_{i=1}^{m} (h_\theta(x^{(i)}) - y^{(i)})`$
- $`\theta_1^{(t+1)} \coloneqq \theta_1^{(t)} - \alpha \frac{1}{m} \sum_{i=1}^{m} (h_\theta(x^{(i)}) - y^{(i)}) x^{(i)}`$
- you can choose a step-size (learning rate) $`\alpha > 0`$ in $`\mathbb{R}`$
- you can choose any initial conditions for $`\theta_0^{(0)}`$ and $`\theta_1^{(0)}`$


## Assignment03

### 1. Data

- load a set of data points $`\{ (x^{(i)}, y^{(i)}) \}`$ from the given CSV file (data.csv)

### 2. Linear Model

- $`h_\theta(x) = \theta_0 + \theta_1 x`$, $`\quad`$ where $`\theta = (\theta_0, \theta_1)`$ and $`\theta_0, \theta_1 \in \mathbb{R}`$

### 3. Objective Function

- $`J(\theta_0, \theta_1) = \frac{1}{2 m} \sum_{i=1}^m ( \theta_0 + \theta_1 x^{(i)} - y^{(i)} )^2`$

### 4. Gradient Descent
 
- $`\theta_0^{(t+1)} \coloneqq \theta_0^{(t)} - \alpha \frac{1}{m} \sum_{i=1}^{m} (h_\theta(x^{(i)}) - y^{(i)})`$
- $`\theta_1^{(t+1)} \coloneqq \theta_1^{(t)} - \alpha \frac{1}{m} \sum_{i=1}^{m} (h_\theta(x^{(i)}) - y^{(i)}) x^{(i)}`$

### 5. Energy Surface

- three dimentional surface by $`(\theta_0, \theta_1, J(\theta_0, \theta_1))`$
