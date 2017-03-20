---
title: 第一组抽样名单
---

可使用R和Rstudio来执行抽样过程，具体命令如下：

    install.packages(c("dplyr", "readxl"))
    library(dplyr)
    library(readxl)
    x = read_xl("group1-evopsy.xlsx")
    set.seed(743)
    sample_n(x, 6)

结果如下：

   序号    学号   姓名
  <dbl>   <dbl>  <chr>
1     1 1512890 黄子晴
2     4 1511105   商美
3     5 1512898 张雪丽
4     2 1512880   沈灏
5    11 1511496 潘子晴
6     3 1512886   安旭

