---
layout: homepage
---


## EagleEye: Attack-Agnostic Defenses against Adversarial Inputs

<hr>

### Overview


<div align="center"><img src="{{ site.baseurl }}/assets/img/eagleeye.png" alt="eagleeye" height="50%" width="50%" align="middle"/></div>

Deep learning systems are inherently vulnerable to adversarial inputs, which are maliciously crafted samples to trigger deep neural networks (DNNs) to misbehave, leading to disastrous consequences in security-critical applications. The fundamental challenges of defending against such attacks stem from their adaptive and variable nature: adversarial inputs are tailored to target DNNs, while crafting strategies vary greatly with concrete attacks. This project develops EagleEye, a universal, attack-agnostic defense framework that (i) works effectively against unseen attack variants, (ii) preserves predictive power of deep neural networks, (iii) complements existing defense mechanisms, and (iv) provides comprehensive diagnosis about potential risks in deep learning outputs.

In particular, EagleEye leverages a set of invariant properties underlying most attacks, including the “minimality principle”: to maximize attack evasiveness, an adversarial input is generated by applying the minimum possible distortion to a legitimate input. By exploiting such properties in a principled manner, EagleEye effectively discriminates adversarial inputs (integrity checking) and even uncovers their correct outputs (truth recovery).

<hr>

### Publications


*  **<font color="purple"> Interpretable Deep Learning under Fire </font>**<br>
*<font color="black">Xinyang Zhang, Ningfei Wang, Shouling Ji, Hua Shen, Ting
  Wang</font>* <br>
*<font color="blue"> <a href="https://arxiv.org/abs/1812.00891 ">ArXiv e-prints, 2018</a> </font>*

*  **<font color="purple">TextBugger: Generating Adversarial Text Against Real-world Applications</font>** [[pdf]({{ site.url }}/paper/Li-ndss-2019.pdf)]<br>
*<font color="black">Jinfeng Li, Shouling Ji, Tianyu Du, Bo Li, Ting Wang</font>* <br>
*<font color="blue">The 2019 Network and Distributed System Security Symposium (NDSS '19)</font>*

*  **<font color="purple">DeepSec: A Uniform Platform for Security Analysis of Deep Learning Models</font>** [[pdf]({{ site.url }}/paper/Ling-sp-2019.pdf)]<br>
*<font color="black">Xiang Ling, Shouling Ji, Jiaxu Zou, Jiannan Wang, Chunming Wu, Bo Li, Ting Wang</font>* <br>
*<font color="blue">The 40th IEEE Symposium on Security and Privacy (S&P '19)</font>*

*  **<font color="purple">Towards Evaluating the Security of Image CAPTCHA in The Wild</font>** [[pdf]({{ site.url }}/paper/Zhao-aisec-2018.pdf)]<br>
*<font color="black">Binbin Zhao, Haiqin Weng, Shouling Ji, Jianhai Chen, Ting Wang, Qinming He, Raheem Beyah</font>* <br>
*<font color="blue">The 11th ACM Workshop on Artificial Intelligence and Security (AISec '18)</font>*

*  **<font color="purple"> Towards A Unified Theory of Adversarial Inputs and Adversarial Models </font>**<br>
*<font color="black">Ting Wang</font>* <br>
*<font color="blue"> <a href="https://arxiv.org/abs/">ArXiv e-prints, 2018</a> </font>*

<!-- *  **<font color="purple"> Unified and Certified Defenses against Adversarial Inputs </font>**<br>
*<font color="black">Xinyang Zhang, Chanh Nguyen, Shouling Ji, Ting Wang</font>* -->

*  **<font color="purple">Model-Reuse Attacks on Deep Learning Systems</font>** [[pdf]({{ site.url }}/paper/Ji-ccs-2018.pdf)] <br>
*<font color="black">Yujie Ji, Xinyang Zhang, Shouling Ji, Xiapu Luo, Ting Wang</font>* <br>
*<font color="blue">The 25th ACM Conference on Computer and Communications Security (CCS '18)</font>*


*  **<font color="purple"> EagleEye: Attack-Agnostic Defense against Adversarial Inputs </font>**<br>
*<font color="black">Yujie Ji, Xinyang Zhang, Ting Wang</font>* <br>
*<font color="blue"> <a href="https://arxiv.org/abs/1808.00123">ArXiv e-prints, 2018</a> </font>*

* **<font color="purple">Differentially Private Distributed Online Learning</font>** [[pdf]({{ site.url }}/paper/li-tkde-2018.pdf), [bibtex]({{ site.url }}/references.html#Li:2018:tkde)]<br>
*<font color="black">Chencheng Li, Pan Zhou, Li Xiong, Qian Wang, and Ting Wang</font>* <br>
*<font color="blue">IEEE Transactions on Knowledge and Data Engineering (TKDE)</font>*

* **<font color="purple">Quantifying Graph Anonymity, Utility, and De-anonymity</font>** [[pdf]({{ site.url }}/paper/ji-infocom-2018.pdf), [bibtex]({{ site.url }}/references.html#Ji:2018:infocom)]<br>
*<font color="black">Shouling Ji, Tianyu Du, Zhen Hong, Ting Wang, Raheem Beyah</font>* <br>
*<font color="blue">2018 IEEE International Conference on Computer Communications (INFOCOM '18)</font>*

* **<font color="purple">Backdoor Attacks against Learning Systems</font>** [[pdf]({{ site.url }}/paper/ji-cns-2017.pdf), [bibtex]({{ site.url }}/references.html#Ji:2017:cns)]<br>
*<font color="black">Yujie Ji, Xinyang Zhang, Ting Wang</font>* <br>
*<font color="blue">The 5th IEEE Conference on Communications and Network Security (CNS '17)</font>*



<hr>

### Code & Datasets

<hr>

<img src="{{ site.baseurl }}/assets/img/nsf.jpg" alt="nsf" height="10%" width="10%" align="absmiddle"/> We are grateful for the National Science Foundation (NSF) to support our research.