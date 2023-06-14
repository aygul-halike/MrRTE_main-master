
## Requirements

The main requirements are:

  - python==3.7.9
  - pytorch==1.6.0
  - transformers==3.2.0
  - tqdm

## Datasets

- URTE/UYRE_D


## Usage

**1. Get pre-trained BERT model for PyTorch**

Download [bert-base-multilingual-cased](https://huggingface.co/bert-base-multilingual-cased/tree/main) which contains `pytroch_model.bin`, `vocab.txt` and `config.json`. Put these under `./pretrain_models`.

**2. Build Data**

Put our preprocessed datasets under `./data`.

**3. Train**

Just run the script in `./script` by `sh train.sh`.



**4. Evaluate**

Just run the script in `./script` by `sh evaluate.sh`.

