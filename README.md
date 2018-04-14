<<<<<<< HEAD
# NeoHackathon

1. Need an MVP (Minimum Viable Product)
2. Should be developed and able to demonstrate on NEO Blockchain Network
3. POWERPOINT Presentation
4.
=======
### Requirements

Usage requires Python 3.6+

### Installation

Clone the repository and navigate into the project directory.
Make a Python 3 virtual environment and activate it via

```shell
python3 -m venv venv
source venv/bin/activate
```

or to explicitly install Python 3.6 via

```shell
virtualenv -p /usr/local/bin/python3.6 venv
source venv/bin/activate
```

Then install the requirements via

```shell
pip install -r requirements.txt
```

### Compilation

The template may be compiled as follows

```python
python3 compile.py
```

This will compile your template to `genki_smart_contract.avm`

### Import

In neo-python prompt:

```neo-python
import contract ../NeoHackathon/genki_smart_contract.avm 0702 05 True False
```

### Deploy (Owner Check)

In neo-python prompt:

```neo-python
testinvoke {contract_hash} deploy []
```

### Check circulation and token_sold

In neo-python prompt:

```neo-python
testinvoke {contract_hash} circulation []
testinvoke {contract_hash} token_sold []
```
>>>>>>> Finish
