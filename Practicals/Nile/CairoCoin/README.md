### Install dependencies
```cd Practicals/Nile/CairoCoin```
```python3 -m venv env```
```source env/bin/activate```
```pip install cairo-nile```

### setup the  project
```nile init```
### Start a local node
```nile node &```
###  Compile the contracts
```nile compile```  # compiles all contracts under the contracts directory

###  Deploy the contract 
```nile deploy contract --alias my_contract```

(Edit the .env file to provide a different private key, do not use this key elsewhere)

```nile setup PKEY1```



