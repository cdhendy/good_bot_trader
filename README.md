Module 14 - Challenge 14 : GoodBot Trading Co.
==========================================

## Purpose

 The purpose of this notebook is to enhance existing trading signals with machine learning algorithms that can adapt to new data. 

---

## Technologies

Jupyter notebooks and the Pandas data analysis library were used in the creation of this project. Additionaly sklearn packages were leveraged for the creation of the notebook and following analysis. 

---

## Installation Guide

First, install the jupyter and pandas libraries. In your terminal or command shell install the following packages: 

```python
pip install jupyter
```

```python
pip install pandas
```

```python
pip install sklearn
```



This notebook was created using python 3.7.10. There were a number of issues with the packages within this specific conda environment, and I definitely recommend taking time to troubleshoot any package discrepencies that may arise. 

---
## Conclusion

DecisionTreeClassifier was a bad call to use in the New Machine Learning classifier, the results speak for themselves:

Before DTC: 

![Before](Resources\images\3_month_baseline\output.png?raw=true "Before")

With DTC:
![DTC](Resources\images\dtc.png?raw=true "DTC")

---

## Contributors

Created by: Christopher Henderson

cdhendy@gmail.com

[LinkedIn](https://www.linkedin.com/in/chris-henderson123/)

---

## License

(c) Copyright 2021 Chris Henderson

Licensed under the MIT license:

    http://www.opensource.org/licenses/mit-license.php

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.