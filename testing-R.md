# Hello and welcome to the R-world!!

Let us see how we might use R as a simple calculator: 

```R
2 + 2
```

4

What about loading up some data and generating some plots?

```R
library(tidyverse)
ggplot(
    data = diamonds,
    aes(x = carat, y = price),
    color = "cornflowerblue",
    fill = "cornflowerblue"
    ) +
    geom_point() +
    hrbrthemes::theme_ft_rc()
```
