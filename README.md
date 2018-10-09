# DESCRIPTION
We implement an application of Convolutional Long-Short Term Memory neural network proposed by **[Shi et. al, 2015](https://arxiv.org/abs/1506.04214)** in 3D precipitation nowcasting in Kobe city, Japan. We show a significant improvement using this method, in comparision with an optical-flow based method of **[Otsuka et. al, 2016](https://journals.ametsoc.org/doi/10.1175/WAF-D-15-0063.1)**

**Contact me if you need source code of this application.**
## Architecture of ConvLSTM

### ConvLSTM
![](../master/Image/conv_1.png)
### Conditional ConvLSTM: combine with optical-flow based forecasting 
![](../master/Image/conv_2.png)

## Comparision in term of 3 metrics: MSE, B-MSE, threat score CSI
* **Quantitative evaluation**
![](../master/Image/result_1.png)

* **Horizotal & Vertical evolution of rainfall**
1.
![](../master/Image/image1.gif)
![](../master/Image/image5.gif)

2.
![](../master/Image/image4.gif)
![](../master/Image/image8.gif)
