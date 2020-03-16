# Customer-Segments
Creating customer segments for a wholesale distributor. 

# Install
This project requires Python 2.7 and the following Python libraries installed:

* [NumPy](www.numpy.org)
* [Pandas](pandas.pydata.org)
* [matplotlib](matplotlib.org)
* [scikit-learn](scikit-learn.org)

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

# Code

Template code is provided in the customer_segments.ipynb notebook file. You will also be required to use the included visuals.py Python file and the customers.csv dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in visuals.py is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

# Run

In a terminal or command window, navigate to the top-level project directory customer_segments/ (that contains this README) and run one of the following commands:

```python
ipython notebook customer_segments.ipynb
```
or

```python
jupyter notebook customer_segments.ipynb
```

# Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the UCI Machine Learning Repository.

Note (m.u.) is shorthand for monetary units.

# Features

* Fresh: annual spending (m.u.) on fresh products (Continuous);
* Milk: annual spending (m.u.) on milk products (Continuous);
* Grocery: annual spending (m.u.) on grocery products (Continuous);
* Frozen: annual spending (m.u.) on frozen products (Continuous);
* Detergents_Paper: annual spending (m.u.) on detergents and paper products (Continuous);
* Delicatessen: annual spending (m.u.) on and delicatessen products (Continuous);
* Channel: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
* Region: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal)
