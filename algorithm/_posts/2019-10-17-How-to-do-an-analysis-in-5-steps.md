---
layout: post
title: How to do an analysis in 5 steps
description: How to do a Data Structure and Algorithms analysis?
author: Mason Ko
noindex: true
---
<!-- mk_log: "I'm writing this document manully, not by command or anything -->


'''cpp

unsigned int factorial(unsigned int n){
    unsigned int rc = 1;
    
    // we don't start from 1 because multiplying 1*1 gives 1. So start from 2

    for(unsigned int i = 2; i <= n; i++){
        rc = rc * i;
    }
    return rc;
}

'''


