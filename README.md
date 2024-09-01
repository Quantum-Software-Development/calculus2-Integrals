# <p align="center"> ✍️ Calculus II - Function Integrals - Resolution of Mathematics Exercises

<br>

 <p align="center">
<img src="https://github.com/user-attachments/assets/8cee1a6f-8377-4d60-bf47-ae6dec56102e"/>

<br>

#### <p align="center"> AI Data Science - PUCSP University - Math Repository - [Professor Eric Bacconi Gonçalves](https://www.linkedin.com/in/eric-bacconi-423137/)

<br>


### <p align="center"> [![Sponsor Quantum Software Development](https://img.shields.io/badge/Sponsor-Quantum%20Software%20Development-brightgreen?logo=GitHub)](https://github.com/sponsors/Quantum-Software-Development)

<br>


## [Introduction to the Repository]()

Welcome to the "Basic Function Integrals" repository! This repository was created to provide an introduction to integral calculus II through practical examples. Here, you will find detailed solutions to various integrals of polynomial, trigonometric, and logarithmic functions. This material is suitable for both beginners and those who want to review fundamental concepts of calculus II.

This repository pertains to the Calculus II and Probability course of the Machine Learning discipline in the second semester of 2024 for the Data Science and Artificial Intelligence undergraduate program at the Pontifical Catholic University of São Paulo (PUC-SP).


## [Fundamental Concepts]()

This repository covers the basic concepts of integration, which is the process of finding the antiderivative of a function. Integration is an essential tool in calculus and is used to calculate areas under curves, volumes of solids of revolution, among other applications.


## [Why Integrals are Important for AI Data Scientists]()

Integrals are a crucial mathematical tool for AI Data Scientists due to their wide-ranging applications in data analysis, machine learning, and artificial intelligence. Here are a few key reasons:

   1. [Probability and Statistics:]() Many machine learning algorithms rely heavily on probability theory. Integrals are used to calculate probabilities, especially when dealing with continuous random variables. For instance, the probability of a certain outcome within a range can be found by integrating the probability density function over that range.

   2. [Optimization Algorithms:]() Machine learning models, particularly those in deep learning, often involve optimizing a cost function. These functions are typically minimized or maximized by calculating gradients, which involve integration in continuous spaces. Understanding the integral calculus behind these processes helps in fine-tuning algorithms for better performance.

   3. [Expectation and Variance:]() In the analysis of machine learning models, integrals are used to compute expected values (means) and variances of continuous random variables. These metrics are essential for evaluating model performance and understanding the underlying data distribution.

   4. [Continuous Data and Functions:]() When dealing with continuous data, integrals allow data scientists to perform crucial operations like calculating areas under curves (e.g., ROC AUC), smoothing data, or analyzing cumulative distributions. This understanding is key to making accurate predictions and assessments in AI models.

   5. [Neural Networks:]() In the realm of neural networks, integrals are fundamental to understanding how different layers interact, especially in cases involving activation functions or backpropagation, where continuous change is a core element.

## [Conclusion]()

Mastering integrals and their applications is vital for AI Data Scientists. Whether it’s in probability theory, optimization, or data analysis, integrals provide the mathematical foundation needed to build, understand, and improve complex machine learning models. By grasping these fundamental concepts, you’ll be better equipped to tackle the challenges and opportunities in the field of artificial intelligence.

## [Solved Exercises]()
The exercises solved in this repository cover indefinite integrals and are presented with step-by-step solutions. Each example includes the original integral, decomposition into simpler terms (when applicable), the integration of each term, and the final answer.

## [Exercise List]()

Below are the exercises solved in this repository. They have been written in LaTeX to ensure a clear and precise presentation. Feel free to use and improve the code as needed.

### [Exercises: Find the following integrals]() ☟

### [Exercicise A:]() 

<br>

 $${\huge \bf \int \left(x^{\frac{3}{2}} + 2x + 1\right) \, dx}$$

<br>

- 💡 [**Solution:**:]() We can integrate each term separately:

<br>

$$\huge \bf \int x^{\frac{3}{2}} \, dx + \int 2x \, dx + \int 1 \, dx$$

<br><br>

- [**1st:**]() ☞   $\huge \bf \int x^{\frac{3}{2}} dx$

 <br>

$$\huge \bf \frac{x^{\frac{3}{2} + 1}}{\frac{3}{2} + 1} \rightarrow \frac{x^{\frac{5}{2}}}{\frac{5}{2}} \rightarrow \frac{2}{5}x^{\frac{5}{2}}$$ 

<br><br>

- [**2st:**]()  ☞   $\huge \bf \int 2x dx\$

 <br>

 $$\huge \bf \frac{x^{1+1}}{1+1} \rightarrow 2 \cdot \frac{x^2}{2} \rightarrow x^2$$

<br><br>
 
- [**3st:**]()  ☞   $\huge \bf  \int 1 dx$

 <br>

<p align="center"> The indefinite integral of \(1\) with respect to \(x\) is given by:

 <br>

$$\huge \bf \int 1 \, dx \rightarrow x + k$$

 <br>

<p align="center"> where \(k\) is the constant of integration. 

$$\huge \bf \ x + k$$

 <br>

###  <p align="center"> [**Final Result:**]() 

 <br>

$$\huge \bf \int \left(x^{\frac{3}{2}} + 2x + 1\right) \, dx \rightarrow \frac{2}{5}x^{\frac{5}{2}} + x^2 + x + k$$

 <br>

 #
 
### [Exercicise B:]() 

$$\huge \bf \int \sqrt[3]{x^2} \, dx$$

<br>

<p align="center"> First, express the cube root as a fractional exponent:

<br>

$$\huge \bf \int x^{\frac{2}{3}} \, dx$$

<br>

<p align="center"> Integrating: 

 <br>

$$\huge \bf \frac{x^{\frac{2}{3} + 1}}{\frac{2}{3} + 1} \rightarrow \frac{x^{\frac{5}{3}}}{\frac{5}{3}} \rightarrow \frac{3}{5}x^{\frac{5}{3}}$$

 <br>

 ###  <p align="center"> [**Final Result:**]() 

 <br>

 $$\huge \bf \int \sqrt[3]{x^2} dx \rightarrow \frac{3}{5}x^{\frac{5}{3}} + k$$

 <br>

#

### [Exercicise C:]() 

 <br>

$$\huge \bf \int \frac{1}{x^3} \, dx$$


<p align="center"> Solution of the integral: ☟

$$\huge \bf \int x^n \, dx = \frac{x^{n+1}}{n+1} + k$$ 

<p align="center"> Applying the rule to the given function: ☟

$$\huge \bf \int x^{-3} \, dx = \frac{x^{-2}}{-2} + C = -\frac{1}{2x^2} + k$$


<p align="center"> Solution of the integral: ☟

$$\huge \bf \frac{1}{2x^2} + k$$

###  <p align="center"> [**Final Result:**]() 

$$\huge \bf \int \frac{1}{x^3} \, dx = -\frac{1}{2x^2} + k$$

#

### [Exercicise D:]() 

 <br>

$$\huge \bf \int \frac{x^2 + x + 1}{\sqrt{x}} \, dx$$


- 💡 [**Solution:**:]() We can integrate each term separately:

$$\huge \bf \int \left(\frac{x^2}{\sqrt{x}} + \frac{x}{\sqrt{x}} + \frac{1}{\sqrt{x}}\right) \, dx$$

<p align="center"> This simplifies to: 

$$\huge \bf \int \left(x^{\frac{3}{2}} + x^{\frac{1}{2}} + x^{-\frac{1}{2}}\right) \, dx$$

<p align="center"> [Integrating each term:]() ☟

 $$\huge \bf  \int x^{\frac{3}{2}} \, dx = \frac{2}{5}x^{\frac{5}{2}}$$









 






























### [Contribute]()

Contributions are welcome! If you want to add more examples, correct errors, or improve the documentation, please submit a pull request. Let's learn and grow together on the journey of integral calculus.

### [How to Contribute]()

Any contributions are highly appreciated.  You can contribute in two ways:

   1. Create an issue and tell us your idea 💡. Make sure that you use the new idea label in this case;

   2. Fork the project and submit a full requesto with your new idea. Before doing that, please make sure that you read and follow the [Contributions Guide](https://github.com/Mindful-AI-Assistants/.github/blob/9e7e98f98af07a1d6c4bdeb349e1a9db04f8ed0e/CONTRIBUTIBNG.md). ⊹★🔭๋࣭


## [Main Contributors]() 

- [Fabiana 🚀 Campanari](https://github.com/FabianaCampanari)






#

###### <p align="center"> [Copyright 2024 Quantum Software Development. Code released under the MIT License license.](https://github.com/Quantum-Software-Development/Math/blob/3bf8270ca09d3848f2bf22f9ac89368e52a2fb66/LICENSE)

