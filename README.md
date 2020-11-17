# 模型蒸馏

<img src="v2-dad358add9bbc2aae87f85dfcfec1f57_1440w.jpg" alt="v2-dad358add9bbc2aae87f85dfcfec1f57_1440w" style="zoom: 25%;" />

[Distilling the Knowledge in a Neural Network](arxiv.org/pdf/1503.02531.pdf)

“蝴蝶以毛毛虫的形式吃树叶积攒能量逐渐成长，最后变换成蝴蝶这一终极形态来完成繁殖。”

![1605616404163](1605616404163.png)

![1605616691627](1605616691627.png)

### 蒸馏温度，软标签

$$Soft Logit: q_i=\frac{exp(z_i/T)}{\Sigma_jexp(z_i/T)} $$

