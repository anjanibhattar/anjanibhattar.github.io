---
title: "Web Scraping Project"
date: 20198-07-17
tags: [web scraping, data science, wikipedia, python, beautiful soup]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Web Scraping, Wikipedia, Python, Beautiful Soup"
mathjax: "true"
---

# H1 Heading

## H2 Heading

### H3 Heading

In this project, I've attempted to learn and implement the basics of web scraping using the Python library, Beautiful Soup to scrape content from a [Wikipedia page](https://en.wikipedia.org/wiki/List_of_aircraft_accidents_and_incidents_resulting_in_at_least_50_fatalities) containing the list of all aircraft accidents and incidents resulting in at least 50 fatalities.

The list of 549 records containing 13 variables (columns) are available in a table which I've scraped using the BeautifulSoup library in Python.

Inspecting the HTML of the Wikipedia page, it can be observed that the text in the first 5 columns, related to Deaths are available within the 'th' tags of the table, while the text in the rest of the columns is available within the 'td' tags.

The data from the first 5 columns with the 'th' tags has been extracted into one dataframe and the data from the rest of the columns with the 'td' tags into another dataframe. Both the dataframes have then been concatenated to form a single dataframe.

I've referred to several websites and blogs to understand the basics of web scraping and using the BeautifulSoup library along with the BS4 documentation.

<!---
What about a [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$

--->
