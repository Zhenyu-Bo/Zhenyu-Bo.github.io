---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a junior student from the School of Computer Science at University of Science and Technology of China(USTC) and I'm a member of [Huaxia Computer Science and Technology Elite Program](https://catalog.ustc.edu.cn/program/t15). In addition to my major in computer science, I also minor in finance.

**I am actively seeking a PhD position for 2026 Fall. If you have any information, please contact me!**

Research Interest
======
My research interest lies in **Computer Vision**, **LLM(Reasoning, Optimization, etc.)**, **NLP**, **Multimodal Learning** and so on.

To be honest, there are so many directions in the computer field and I've only touched a few of them. I ruled out a lot of directions based on my first instinct, and based on my own superficial understanding, I thought I might be interested in certain directions. Therefore, I think the above descriptions of my research interest is not comprehensive but it is the best judgment I can make at this time.

<!-- I am currently an undergraduate at USTC and working at [CODIA](https://code.bdaa.pro/) team. -->
You can find my CV here: [CV](../files/CV/CV-USTC-ZhenyuBo.pdf).
You can contact me through [Email](mailto:bzy1117@mail.ustc.edu.cn).

Honors
======
* National Scholarship (The highest honor for Chinese undergraduates, 2024)
* Jianghuai NIO Scholarship (Top 10%, 2023)
* Hua Xia Talent Scholarship (Top 10%, 2023, 2024)
* WorldQuant International Quant Championship Gold Level(2023)

Research Experience
======
**1. Cognitive Diagnosis Optimization**

I worked at [CODIA](https://code.bdaa.pro/dashboard/) team focusing on diagnosing the student's ability level based on the student's historical answer records. I successfully improved the fairness and accuracy of the prediction of the model. The following are the details.
**Fairness**: During the model training process, groups with more data exert greater influence and achieve better fitting performance, which leads to unfair predictions across different groups. I addressed this by dynamically balancing the ratio of data from each group in training batches, prioritizing underperforming groups to maintain balanced performance, thus enhancing fairness.
**Accuracy**: An auxiliary model assesses data reliability through prediction discrepancies with the main model (smaller differences indicate more reliable student data). Based on date reliability, I adjust data weights to reduce noise impact, improving accuracy.

**2. LLM-assisted Code Repair**

It is one of my curriculum projects and can be accessed via [Code-Assistant](https://github.com/Zhenyu-Bo/Code-Assistant).

**Motivation:**
* LLMs lack awareness of untrained repositories, making it difficult to retrieve code information relevant to current needs.
* Code repositories often contain massive files, and token limits combined with LLMs' constrained long-context comprehension prevent inputting all information as prompts. 

**Solution:**
My strategy is using RAG to provide precise information which LLMs exactly need to improve code awareness of LLM and reduce context overhead. To be more specific yet concise, I construct a function call dependency table for files in the code repository, then extract all relevant functions based on user requests and inject them as prompts into LLMs.

**3. FreeRTOS Security Enhancement**

It is also one of my curriculum projects and can be accessed via [mustrust](https://github.com/OSH-2024/mustrust).

**Description:**
We use Rust to rewrite the core code of FreeRTOS (using C) to improve security.
