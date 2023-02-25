# Feature-Reduction

![Project Image](project-image-url)

> This is a ReadMe template to help save you time and effort.

---

### Table of Contents
<!-- You're sections headers will be used to reference location of destination. -->

- [Description](#description)
- [How To Use](#how-to-use)
- [References](#references)
- [License](#license)
- [Author Info](#author-info)

---

## Description

Using various techniques to reduce the number of features in a dataset

- Import the housing data as a data frame and ensure that the data is loaded properly.
- Drop the "Id" column and any features that are missing more than 40% of their values.
- For numerical columns, fill in any missing data with the median value.
- - For categorical columns, fill in any missing data with the most common value (mode).
- Convert the categorical columns to dummy variables.
- Split the data into a training and test set, where the SalePrice column is the target.
- Run a linear regression and report the R2-value and RMSE on the test set.
- Fit and transform the training features with a PCA so that 90% of the variance is retained (see section 9.1 in the Machine - Learning with Python Cookbook).
- How many features are in the PCA-transformed matrix?
- Transform but DO NOT fit the test features with the same PCA.
- Repeat step 7 with your PCA transformed data.
- Take your original training features (from step 6) and apply a min-max scaler to them.
- Find the min-max scaled features in your training set that have a variance above 0.1 (see Section 10.1 in the Machine Learning with Python Cookbook).
- - Transform but DO NOT fit the test features with the same steps applied in steps 11 and 12.
- Repeat step 7 with the high variance data.
- Summarize your findings.

#### Technologies

- Python
- 

[Back To The Top](#read-me-template)

---

## How To Use

#### Installation

No special instructions here for the python file.  You'll need to update the code to point to where you've saved your product review information.

#### API Reference

```
[Back To The Top](#read-me-template)

---

## References
[Back To The Top](#read-me-template)

---

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#read-me-template)

---

## Author Info

- Github - [Michael Paris - Razrbak501](https://github.com/razrbak501)
- LinkedIn - [Michael Paris](https://www.linkedin.com/in/michael-alan-paris/)

[Back To The Top](#read-me-template)
