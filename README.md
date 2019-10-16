<div align="center">
  <img src="https://github.com/daviddao/green-ai/blob/master/green-ring.png" width="250px">
</div>

# Green Artificial Intelligence Standard
[![](https://tinyurl.com/greenai-pledge)](https://github.com/daviddao/green-ai)

The Green AI Standard aims to develop a standard and raise awareness for best environmental practices in AI research and development

## The climate issue in AI
Developing machine learning models is extremly costly for the environment ([Strubell *et al.* (2019)](https://arxiv.org/abs/1906.02243))
- Training [BERT](https://arxiv.org/abs/1810.04805) on a GPU is roughly equivalent to a trans-American flight (650kg CO2)
- One (512px) [BigGAN](https://arxiv.org/abs/1809.11096) experiment is equivalent to a trans-Atlantic roundtrip (~1 to 2t of CO2)
- Neural architecture search experiments for [Transformer](https://arxiv.org/abs/1706.03762) is emitting as much as 50 years of an average human life (~280t of CO2) 

Information and communications technology is on track to create 3.5% of global emissions by 2020–which is more than the aviation and shipping industries–and could hit 14% by 2040 ([Guardian (2018)](https://www.theguardian.com/environment/2017/dec/11/tsunami-of-data-could-consume-fifth-global-electricity-by-2025)). We need to take a stand now!

## Best practices in development

1. Report time to retrain machine learning models (e.g. GigaFLOPS till convergence, [Strubell *et al.* (2019)](https://arxiv.org/abs/1906.02243))
2. Report sensitivity of hyperparameters for machine learning models (e.g. variance with respect to Hyperparameters searched, [Strubell *et al.* (2019)](https://arxiv.org/abs/1906.02243))
3. Use more efficient alternatives to brute-force grid search for hyperparameter tuning (e.g. random or bayesian search, [Strubell *et al.* (2019)](https://arxiv.org/abs/1906.02243))

## Best practices in infrastructure

Minimize costs and carbon emissions by sharing local infrastructure instead of relying on on-demand cloud computing resources ([Strubell *et al.* (2019)](https://arxiv.org/abs/1906.02243))

## Offset your resulting emissions

We recommend offsetting your emissions to certified carbon neutrality projects if possible.
Offsets can be calculated via [MyClimate](https://co2.myclimate.org/en/offset_further_emissions) and purchased here:

- [MyClimate](https://www.myclimate.org/)
- [Gold Standard](https://www.goldstandard.org/)
- [ActForest](http://actforest.glideapp.io)

## Show your commitment with a badge on your repository

| **👇 The Pledge Badge** | **👇 The Carbon Neutral Badge** |
|-----------------|-----------------|
| [![](https://tinyurl.com/greenai-pledge)](https://github.com/daviddao/green-ai) | ![](https://tinyurl.com/greenai-neutral) |

**The pledge badge** shows your commitment to do the best to reduce the greenhouse gas emissions caused by your research by following the best practices developed by the Green AI Standard

**The Carbon Neutral Badge** shows that your greenhouse gas emissions caused by your code repository are offsetted. The badge should link to the offset certificate for verification

## Acknowledgement

The green ring is inspired by the [Climate Reality project](https://www.climaterealityproject.org/blog/why-does-al-gore-wear-green-ring-pin)
