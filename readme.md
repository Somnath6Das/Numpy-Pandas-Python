conda create -p venv python==3.12

conda create -n venv python==3.12

conda activate venv/

pip install -r requirement.txt

pip install --user ipykernel

python -m ipykernel install --user --name global-python --display-name "Python (Global)"

conda install -c anaconda ipykernel

---

python3 -m venv myenv
source myenv/bin/activate

pip install --upgrade pip
pip install ipykernel
pip install pandas
