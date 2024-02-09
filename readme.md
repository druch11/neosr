# Check [upstream](https://github.com/muslll/neosr) for information about project

Installation:
```
#requires python 3.11

git clone https://github.com/druch11/neosr
cd neosr
python -m venv venv
source venv/bin/activate
pip install -e .
```

Training:
```
python train.py --auto_resume -opt /path/to/option.yml
```
