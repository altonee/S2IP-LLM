# S2IP-LLM
Official reponsitory for "S^2IP-LLM: Semantic Space Informed Prompt Learning with LLM for Time Series Forecasting"




## 🛠 Prerequisites

Ensure you have installed the necessary dependencies by first building environment:

```
conda create -n "myenv" python=3.10.0
conda activate myenv
```
Inside the folder, run:
```
pip install -r requirements.txt
```

## 📊 Prepare Datastes

Begin by downloading the required datasets. All datasets are conveniently available at [Autoformer](https://drive.google.com/drive/folders/1ZOYpTUa82_jCcxIdTmyr0LXQfvaM9vIy). Create a separate folder named `./data` 



## 💻 Training

All scripts are located in `./scripts`. Example:

```shell
cd long-term_Forecasting 
sh scripts/etth1.sh
```

## Model_checkpoints

Some model checkpoints can be found at:
[Drive](https://shorturl.at/cDd46)




## 📚 Citation
If you find this repo useful, please consider citing our paper as follows:
```
@inproceedings{pan2024s,
  title={$ S\^{} 2$ IP-LLM: Semantic Space Informed Prompt Learning with LLM for Time Series Forecasting},
  author={Pan, Zijie and Jiang, Yushan and Garg, Sahil and Schneider, Anderson and Nevmyvaka, Yuriy and Song, Dongjin},
  booktitle={Forty-first International Conference on Machine Learning},
  year={2024}
}
```
