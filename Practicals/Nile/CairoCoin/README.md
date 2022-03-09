# Install dependencies
```cd Practicals/Nile/CairoCoin```
```python3 -m venv env```
```source env/bin/activate```
```pip install cairo-nile```
# setup the  project
```nile init```
# Start a local node
```nile node &```
# Compile the contracts
```nile compile```  # compiles all contracts under the contracts directory

# Deploy the contract 
```nile deploy contract --alias my_contract```
```nile setup PKEY1```

# Now add a variable similar to balance called supply and a function get_supply to return the supply
# re compile the contract
```nile compile```
# re deploy the contract to new alias my_contract2
```nile deploy contract --alias my_contract2```
# call the get_balance and get_supply functions
```nile call my_contract2 get_balance```
```nile call my_contract2 get_supply```


