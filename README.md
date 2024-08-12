# HDCformer (Collaboratecom2023)

Paper Link: [An Evolving Transformer Network Based on Hybrid Dilated Convolution for Traffic Flow Prediction](https://link.springer.com/chapter/10.1007/978-3-031-54531-3_18)

## Model

HDCformer consists of a data embedding layer, a positional encoding layer, a stack of M identical encoder-decoder layers, and an output layer.

<div align=center>
<img src="https://github.com/HCHHOH/HDCformer/blob/main/img/res_overview.png" width='60%'>
</div>

## Main Results

The performance of HDCformer was validated on two real-world traffic flow datasets, PeMSD4 and PeMSD8. 

We split two datasets into training set, validation set, and test set in a ratio 6:2:2. We use the past day’s historical data (288 timesteps) to predict the traffic flow data for the next hour.

<div align=center>
<img src="https://github.com/HCHHOH/HDCformer/blob/main/img/res_experiment.png" width='75%'>
</div>

## Citation

```
@InProceedings{10.1007/978-3-031-54531-3_18,
  author="Yu, Qi and Ding, Weilong and Sun, Maoxiang and Huang, Jihai",
  editor="Gao, Honghao and Wang, Xinheng and Voros, Nikolaos",
  title="An Evolving Transformer Network Based on Hybrid Dilated Convolution for Traffic Flow Prediction",
  booktitle="Collaborative Computing: Networking, Applications and Worksharing",
  year="2024",
  publisher="Springer Nature Switzerland",
  address="Cham",
  pages="329--343",
  isbn="978-3-031-54531-3"
}


```
