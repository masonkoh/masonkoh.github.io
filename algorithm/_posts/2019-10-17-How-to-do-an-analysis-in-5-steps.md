---
layout: post
title: How to do an analysis in 5 steps
description: >
    How to do a Data Structure and Algorithms analysis?
author: Mason Ko
noindex: true
---
<!-- mk_log: "I'm writing this document manully, not by command or anything -->

* TOC
{:toc}

**Example Code**
{:.message}

~~~cpp
unsigned int factorial(unsigned int n){
    unsigned int rc = 1;
    
    // we don't start from 1 because multiplying 1*1 gives 1. So start from 2
    for(unsigned int i = 2; i <= n; i++){
        rc = rc * i;
    }
    return rc;

}
~~~



## H2 Establish variables and functions (mathematical ones):
{:.message}
Let *n* represent the value we are finding the factorial for

Let **T(n)** represent number of operations needed to find **n!** using the code

## H2 Count your operations
{:.message}


