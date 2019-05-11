# Chinese NLP tasks

## Entity linking

See [here](../english/entity_linking.md) for more information about the task.

### Datasets

#### AIDA CoNLL-YAGO Dataset

##### Disambiguation-Only Models

|  Model | Micro-Precision | Paper / Source | Code | 
| ------------- | :-----:| :----: | :----: |
| Sil et al. (2018) | 84.4 | [Neural Cross-Lingual Entity Linking](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16501/16101) | |
| Tsai & Roth (2016) | 83.6 | [Cross-lingual wikification using multilingual embeddings](http://cogcomp.org/papers/TsaiRo16b.pdf) | |

[Go back to the README](../README.md)

## Named entity recognition 
See [here](../english/named_entity_recognition.md#named-entity-recognition) for more information about the task.

### Datasets

#### MSRA
The [MSRA](https://www.aclweb.org/anthology/W06-0115) is a Simplified Chinese character corpora provided by Microsoft Research Asia
(MSRA) for WS and NER. This dataset consists of newswire text tagged with three different entity types (PER, LOC, ORG).

| Model           | F1  |  Paper / Source | Code |
| ------------- | :-----:| --- | --- |
| Lattice LSTM (Zhang et al., 2018) | 93.18 | [Chinese NER Using Lattice LSTM](https://arxiv.org/abs/1805.02023) | [LatticeLSTM](https://github.com/jiesutd/LatticeLSTM) |
| BiLSTM-CRF with Chinese radical features (Dong et al., 2016) | 90.95 | [Character-Based LSTM-CRF with Radical-Level Features for Chinese Named Entity Recognition](https://link.springer.com/chapter/10.1007/978-3-319-50496-4_20) | |
| CRF (Chen et al., 2006) | 86.2 | [Chinese Named Entity Recognition with Conditional Probabilistic
Models ](https://www.aclweb.org/anthology/W06-0130) | |
