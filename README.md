# Project Description
![PyPI - Downloads](https://img.shields.io/pypi/dd/pycogat)


# pycogat
Python package that splits CogAT score report PDF export into single page PDFs and labels output by the ID extracted from the PDF.

## Installation
~~~ python
pip install pycogat
~~~

### Usage
~~~ python
import pycogat
from pycogat.cogat import cogat_split

cogat_split('C:\Documents\Reports\cogat_score_report.pdf',6)
~~~
>[!NOTE]
>pycogat can search for IDs on the CogAT score reports based on their length, in the case above the length of the ID is 6.
