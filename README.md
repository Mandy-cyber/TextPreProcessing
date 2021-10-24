# TextPreProcessing
![GitHub release (latest by date)](https://img.shields.io/github/v/release/Mandy-cyber/TextPreProcessing?color=%23ff5373&style=flat-square)  ![GitHub](https://img.shields.io/github/license/Mandy-cyber/TextPreProcessing?color=%23bce1ff&logo=MIT&style=flat-square)  ![GitHub repo size](https://img.shields.io/github/repo-size/Mandy-cyber/TextPreProcessing?color=%23ffcbc6&style=flat-square)
#### *Python package for preprocessing text for NLP models*

## **INSTALLATION**

[Download PyPi Package](https://pypi.org/project/text-ppf/#files) , or <br>
```$
$ pip install text-ppf
```
To upgrade:
```$
$ pip install text-ppf --upgrade
```
<br>

## **WHAT IT DOES**
An all-in-one function which,
<ul>
  <li>Removes punctuation</li>
  <li>Splits the text into a list of words</li>
  <li>Removes stopwords</li>
  <li>Makes each word lowercase</li>
  <li>Lemmatizes each word</li>
</ul>
<br>

## **USAGE**
### _text_ppf_

```python
import pandas as pd
from text_ppf import text_ppf

#LOADING DATASET
df = pd.read_csv('filename.csv')
# print(df.head)

dfNew = df['heading'].apply(text_ppf.clean_up)
print(dfNew)
```


