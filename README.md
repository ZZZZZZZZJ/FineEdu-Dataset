# FineEdu-Dataset
 A Fine-grained Class Students Behavior Understanding Dataset with Jointly Action and Attention Annotations

## Done List
* Provide annotations of each image, including positions, postures, actions and gaze objects.

## To-do List
* Release image features.
* Release train-val pipelines.


UFold所解决的任务为：给定一个输入序列，预测他们的碱基配对模态(base pairing patterns)，即RNA的二级结构;

输入：长度为L的核苷酸序列$x=(x_1,x_2,...,x_L)$，其中$x_i \in \{`A', `U', `G', `C' \}$；

输出：RNA的二级结构，用接触矩阵（contact matrix）$A \in {\{0,1 \}}^{L \times L}$表示。其中$A_{ij} = 1$代表碱基$x_i$和碱基$x_j$的存在一个碱基对（base pairing），反之$A_{ij} = 0$代表不存在。
