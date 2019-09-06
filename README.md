# Diving in

## Getting the environment ready
We first need to create an environment within which we can install and use python3. This we achieve through using virtual enviroment.

```
sudo apt-get install python3-pip
pip3 install virtualenv
python3 -m venv kamilimuds
source kamilimuds/bin/activate
pip install pandas numpy seaborn jupyterlab
jupyter lab
```