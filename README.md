# AmericasNLP 2023 Shared Task on Machine Translation into Indigenous Languages

## Baseline System

This year's baseline is the [best performing system from the 2021 AmericasNLP Shared Task](https://helda.helsinki.fi/bitstream/handle/10138/334239/2021.americasnlp_1.29.pdf?sequence=1&isAllowed=y), particularly the *B-0dev* model. The repository for this model can be found [here](https://github.com/Helsinki-NLP/americasnlp2021-st). Baseline performance for the system is described, per-language, below:

| ISO| Language | ChrF |
---|---|----
aym | Aymara | 0.283
bzd |Bribri | 0.165
cni | Asháninka| 0.258
gn | Guarani| 0.336
hch |Wixarika | 0.304
nah | Nahuatl| 0.266
oto | Otomí| 0.147
quy |Quechua | 0.343
shp |Shipibo-Konibo | 0.329
tar |Rarámuri | 0.184

## Competition Rules

1. This year's competition will be similar to Track 2 of the 2021 Competition: training on the development set is **not** allowed.
2. Using the [AmericasNLI](https://aclanthology.org/2022.acl-long.435.pdf) test set for hyperparameter tuning or decision making is not allowed. 
