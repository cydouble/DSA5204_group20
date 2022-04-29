# DSA5204_group20
In this project, we mainly reproduce the algorithm of the [On the automatic generation of medical imaging reports](https://arxiv.org/abs/1711.08195), and based on it, we propose and implement our extended scheme. More specifically, we extend the work of the original paper in three aspects: (1) For the dataset, we use the different data source from Kaggle; (2) For the encoder, we extract more complete visual features by using both the front and lateral images rather than using only one single image; (3) For the Decoder, we introduce self-attention mechanism to mine the intrinsic dependence of semantic and visual features.

## dataset
Image dataset:
- Kaggle: [Chest X-rays (Indiana University)](https://www.kaggle.com/datasets/raddar/chest-xrays-indiana-university)
Text datast:
- Indiana_projections.csv
- Indiana_reports.csv
