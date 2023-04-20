# AmericasNLP 2023 Shared Task on Machine Translation into Indigenous Languages

**Update 4/21/2023**: The surprise langauge -- Chatino -- has been released! It is now available under `data/chatino-spanish`. In this directory, you can find the train and dev files, along with another file, `ctp-eng.tsv` which contains parallel data between another variant of Chatino and English. We hope that this additional data, although it is from a different domain, will be helpful in improving the Chatino--Spanish translations. 
## Shared Task

For the 2023 Shared Task, Spanish (or another high-resource language) will be used as the source language, and model outputs should be in the target Indigenous language. 

### Rules

1. This year's shared task will be similar to Track 2 of the 2021 ST: training on the development set is **not** allowed.
2. Using the [AmericasNLI](https://aclanthology.org/2022.acl-long.435.pdf) test set for hyperparameter tuning or any form of decision making is not allowed. 
3. Evaluation will be done using the `evaluate.py` script. The final order of teams will be selected using average ChrF across all languages.


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

