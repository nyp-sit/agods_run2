Installation instructions 

1. Create a conda environment with Python=3.9

```
conda create -n agods_env python=3.9
```

2. Install the required packages 

```
conda activate agods_env 
conda install pip 
pip install -r requirements.txt 
```

3. run ntklk_download.py to download the different nlkt databases. 

```
python nltk_download.py
```
