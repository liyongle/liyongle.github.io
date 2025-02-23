---
layout: post
title: [Computer Architecutre][1] How Chipsets are designed and manufactured
excerpt: "Memo during learning computer architecture in a questions driven way, and trying to figrue out why it is expensive."
categories: [Technology]
tags: [Computer]
modified: 2025-02-18
comments: true
---

### About this Series

During my work, I always asked myself many questions. Some are easy to reply while some are not. For example:

1. Why does computers use binary, not decimal or hexadecimal?

1. Since CANN has provided many operators (算子), why are developers are still developing new operators by themselves?

1. GPU/NPU/TPU are kind such expensive and can make such a huge revenue, why don't they produce more? What is the limitation?

Since I have got some answers, I would like to record it down. To be more efficient, it could be in Enlgish, Chinese or mixed. 


### Understand chipsets from cost point of view

Highly abstract, the cost can be:

```
COST = material + manfacturing + IP
```

Material to produce chipsets are known as sands, and the original cost is quit low. The IP is kind of fixed and let's put it aside as well. 

Manufacturing is the KEY. And to understand the manufacturing process, why not use **First Principles 第一性原理**. 

### What is inside the chips, like CPU?

- Die (Chip, Integrated Circuit)

    - CPU Core 

        - Layer
        
            - Wafer (晶圆)

            - Transistors

        - Isolators

        - Local connectors

        - Intermedia connectors
        
        - Global connectors

    - GPU Core
    
    - Memory Controbler

    - Compute Fabric

- Die ...

### How much is a chips factory?

Size: 8 football fields

Price: 

- Hundreds of machines

- Untraviolet Lithography: 170 Million USD

- Cheapest: a few Million USD

- 80 layers X photomasks ($300k)

- 每一层，加各种材料，然后光刻，逐步叠加完成


Duration: CPU travels among the machines for over **3 months**

### Takeaways

The reason that CPU is so expensive can be comprehenive from the materials, manufactoring processes, Quality and time. 

1. Materials

    - Silcon.

    - Chemical meterials.

1. Processes

    - Each layer needs one photomask
    
    - Each layer needs chemical materials, which take time

    - Machines are pretty expensive

1. Time

    - Many procesesses have to be serial, not parallel. 

    - Chemical reactions take time

1. Quality control

    - The more complicated, the easier to fail.

And these are some interesting figrues. 

1. Factory can be 8 football fields large.

1. Hundreds of machines

1. $170M for one Untraviolet Lithography

1. 30mm diameter for one wafer

1. 80 layers in one Die

1. $30K for each photomask (only for one layer)

1. 3 months for one CPU


### Cooling System

Water vs Air.

热导率、比热容是关键。用比热容就可以解释为什么用水最理想。


### Next blog

In the next one, the tradeoff during Chips design will be explained.


### Reference

1. The greatest book "*Computer Architecture: A Quantitative Approach*" by David A Patterson and John L. Hennessy

1. How are CPU made? **Highly recommended**.
[<img src="https://img.youtube.com/vi/dX9CGRZwD-w/maxresdefault.jpg">](https://www.youtube.com/watch?v=dX9CGRZwD-w)

1. Semiconductor production process explained
[<img src="https://img.youtube.com/vi/c9arR8T0Qts/maxresdefault.jpg">](https://youtu.be/c9arR8T0Qts?si=UsBRxIDNC0vhL9dL)
