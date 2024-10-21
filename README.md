# Project Overview

## Libraries Used

The following libraries are utilized in this project:

1. **Numpy v1.26.0**  
   - Numpy is used for working with arrays and has functions for linear algebra, Fourier transform, and matrices.  
   - Installation: `pip install numpy==1.26.0`

2. **Pandas v2.1.1**  
   - Pandas is used for working with datasets, providing functions for data analysis, cleaning, exploration, and manipulation. The name "Pandas" refers to both "Panel Data" and "Python Data Analysis."  
   - Installation: `pip install pandas==2.1.1`

3. **Seaborn v0.13.0**  
   - Seaborn is used for visualizing random distributions and creating attractive statistical graphics.  
   - Installation: `pip install seaborn==0.13.0`

4. **Matplotlib v3.8.0**  
   - Matplotlib is used for creating static, animated, and interactive visualizations in Python.  
   - Installation: `pip install matplotlib==3.8.0`

5. **TensorFlow v2.14.0**  
   - TensorFlow is used for developing machine learning models for tasks such as natural language processing, image recognition, handwriting recognition, and computational simulations like partial differential equations.  
   - Installation: `pip install tensorflow==2.14.0`

6. **Keras v2.14.0**  
   - Keras is a high-level deep learning API for implementing neural networks, developed by Google.  
   - Installation: `pip install keras==2.14.0`

7. **scikit-learn v1.3**  
   - scikit-learn is used for implementing machine learning models and statistical modeling techniques.  
   - Installation: `pip install scikit-learn==1.3`

To install all the necessary libraries at once, run the following command in your folder directory:

```bash
pip install -r requirements.txt

```
Each file of pybook has separate Model and and its combination with feature selection method.


Dataset Creation
Install ulog plugin and give the path of ulog files in both directories of spoofed and benign. 

Link

https://github.com/PX4/pyulog

This is extract flight data from both ulog files merge both files and remove NAN values and use SMOTE for data balancing.


Access the code at:  

[![DOI](https://zenodo.org/badge/790691904.svg)](https://doi.org/10.5281/zenodo.13963837)


