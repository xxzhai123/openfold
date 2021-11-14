```sh
sudo apt install aria2
conda create -p ~/env/openfold python=3.7 -y
conda activate ~/env/openfold
pip install -r requirements.txt
conda install openmm=7.5.1 pdbfixer -y -c conda-forge
```