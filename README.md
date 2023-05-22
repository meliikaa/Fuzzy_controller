# Fuzzy_controller
fuzzy controller with the help of fuzzyLogicDesigner


This repository contains the code and files for a fuzzy logic controller designed using the Fuzzy Logic Designer in MATLAB. The purpose of this project is to develop a fuzzy logic-based controller that can make intelligent decisions based on input variables and predefined fuzzy rules.


**Project Overview**

The fuzzy logic controller is designed to emulate human-like decision-making by utilizing fuzzy logic principles. It takes input variables, fuzzifies them into linguistic terms, applies predefined fuzzy rules, and performs fuzzy inference to generate appropriate control actions.

The main steps involved in the project are as follows:

1- Variable Definition: Identify and define the input variables and output variables that the fuzzy logic controller will operate on. Each variable is divided into linguistic terms, such as "low," "medium," and "high," to represent their fuzzy values.

2- Fuzzy Membership Functions: Assign appropriate membership functions to each linguistic term for the input and output variables. These functions define the degree of membership of a value in a linguistic term.

3- Rule Base: Define a set of fuzzy rules that determine how the input variables influence the output variable. These rules express relationships between linguistic terms using logical operators like "and" and "or."

4- Fuzzy Inference: Perform fuzzy inference by applying the defined rules to the fuzzy input values. This process involves combining the fuzzy sets according to the rule base to generate a fuzzy output.

5- Defuzzification: Convert the fuzzy output into a crisp value that represents the final control action. Various defuzzification methods, such as centroid or maxima defuzzification, can be used to obtain the crisp output.

**Getting Started**

To get started with the fuzzy logic controller, follow these steps:

1- Clone the repository to your local machine or download the code files.

2- Open MATLAB and load the fuzzy logic file (.fis) using the Fuzzy Logic Designer or by calling the readfis function.

3- Define the input variables, output variables, membership functions, and rules in the Fuzzy Logic Designer.

4- Modify the MATLAB code in src/ to incorporate the fuzzy logic controller into your specific application. This may involve integrating the fuzzy logic controller with other components or systems.

5- Use the provided input data or input your own data to test and evaluate the performance of the fuzzy logic controller.
