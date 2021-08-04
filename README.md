# AI_Group
group assignment for AI

run 'python install -r diabetes.csv'
import numpy as np
import pandas as pd

# use the inbuilt dataset
from sklearn.datasets import load_diabetes

diabetes = load_diabetes()
print (diabetes.data);
