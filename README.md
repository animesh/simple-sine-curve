```sh
git clone https://github.com/animesh/simple-sine-curve
cd simple-sine-curve
git restore --source=HEAD :/
pip install tensortrade==1.0.1b0
pip install -r requirements.txt
python scripts/main.py
curl http://10.140.141.183:8265/
```
