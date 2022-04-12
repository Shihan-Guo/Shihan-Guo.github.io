---
title: "Report Reading Series 1 | US Stock–Bond Correlation"
layout: post
date: 2022-03-13 23:10
image: /assets/images/markdown.jpg
headerImage: flase
tag:
- Report Reading
star: true
category: blog
author: Shihan Guo
description: US Stock–Bond Correlation What are the macroeconomic drivers?
---
<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

# US Stock–Bond Correlation
-----

[US Stock-Bond Correlation - What Are the Macroeconomic Drivers?](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3855610)

### The Changing Patterns of Correlation 
- Negative correlation for the last 20 years
- Positive correlation for more than 30 years prior to 2000
- Negative during 1950 - 1965

<p align="center">
	<img src="/assets/posts/US Stock-Bond Correlation/correlation.png" width="75%"/>
</p>

### Macroeconomic Drivers
#### The decomposition
- **The level and stability of interest rates**
- **The perceived riskiness of stocks and bonds**
- **The co-movement of interest rates and economic growth**
<p align="center">
	<img src="/assets/posts/US Stock-Bond Correlation/DCF.png" width="50%"/>
</p>
We could represent the prices of bonds and stocks using DCF model, where $CP$ is the fixed coupon payment, $FV$ is the face-value of the bond, $CF_t$ is the future stock cash flows, $BRP_t$ is the risk premium for bonds and $ERP_t$ is the risk premium for equities.   
Based on the representations, we could decompose the covariance between stock and bond as follow:  
<p align="center">
    $cov_t \approx \gamma_1 var_t(\Delta_i) + \gamma_2 cov_t(\Delta CF, \Delta_i) + \gamma_3 cov_t(\Delta ERP, \Delta BRP) + \text{other terms} + \epsilon_t$
</p>


