# Steps to install

1. Clone the repository

```bash
git clone https://github.com/branyang02/3dEdits.git --recursive
```

2. Install dependencies

```bash
conda create -n 3dedits python=3.8.19
```

3. Install PyTorch

```bash
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.6 -c pytorch -c conda-forge
```

4. Install other dependencies

```bash
pip install -r requirements.txt
```
