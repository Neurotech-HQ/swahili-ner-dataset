<samp>

# SWAHILI-NER-DATASET

Swahili NER dataset is Named Entity Recognition (NER) dataset generated from <https://huggingface.co/datasets/swahili> using back translation techniques.

In case you're interested to explore more about the script used to generate this dataset, please have a look into [Augumented Swahili Data](https://github.com/Neurotech-HQ/Augumented-swahili-ner-data).

This data has been cleaned using couple of techniques and ready for training a Spacy NER model without any modifications, with this data we were able to train a [swahili-spacy-ner](<https://share.streamlit.io/neurotech-hq/swahili-ner-spacy/main/app.py>.

# EXPLORING DATA

Here an example on how the dataset have been structured;

```json
[
    [
        "Alisema kwamba wengi wa watoto hao wa UNCA walikuwa wanawake waliodai kwamba benki hiyo ilikuwa ikitoa mkopo kwa UNCKKKau na UNK",
        {
            "entities": [
                [
                    125,
                    128,
                    "ORG"
                ]
            ]
        }
    ],
    [
        "Katika mikoa ya kati mvua hutazamiwa kunyesha na dodoma kutoka maeneo ya tatu na ya nne ya novemba mwaka huu na kupimwa kwa wastani",
        {
            "entities": [
                [
                    84,
                    87,
                    "ORDINAL"
                ]
            ]
        }
    ],
    .......
]
```

## CONTRIBUTION

This dataset is opensource under ```MIT LICENSE``` therefore you're warmly welcome to contribute,```JUST FORK IT```.

## ISSUES

In case you're having any issues, please raise one so as we can quickly fix it.

## GIVE IT STAR

Did you find this repo useful ? Give it a star so more people can find about this

## CREDITS

All the credits to;
1. [Kalebu](https://github.com/kalebu/)
2. [Anthony Mipawa](https://github.com/Tonyloyt)
3. [akshayb7](https://github.com/akshayb7)
</samp>
