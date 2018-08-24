---
layout: post
title:  Data Visualization using ggplot2
subtitle: Part One
gh-repo: olawaleayilara/olawaleayilara.github.io
gh-badge: [star, fork, follow]
tags: [test]
---

## Introduction
In this training module, I will introduce readers to grammar of graphics in R, with a focus on ggplot2. This package was written by Hadley Wickham and Winston Chang. The repository can accessed using this [link](https://github.com/hadley/ggplot2). ggplot2 is part of the tidyverse package and it is useful for simple and complex data visualization. Using the tidyverse package make it easier to load different types of dataset in R and allows quick data manipulations before visualization. 

If you don't have tidyverse, you can install it with the code below:

```{r}
# install.packages("tidyverse")
library("tidyverse")
```

We will be using the United States college data which consists of the school name, city, state, region, highest degree offered by each school, SAT average scores, tution and so on.  Before, we move too far, I would to let you know that this dataset is not mine. I found it online and it can be accessed through this [link](http://672258.youcanlearnit.net). 

Let's import our data and store it R with the variable name visualData

```{r}
visualData <- read_csv('https://olawaleayilara.github.io/visualData.csv')
head(visualData)
```

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.