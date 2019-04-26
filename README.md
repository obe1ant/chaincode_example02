# chaincode_example02
## A simple chaincode example from hyperledger fabric project

## Install parameters:
### Initialize the chaincode. Create account A with 100 units and B with 200 unites.

```
{
"function":"init",
"args":["a","100","b","200"]
}
```


## Invoke parameters:
### Trigger transaction, make payment of 100 units from A to B

```
{
"function":"invoke",
"args":["a","b","100"]
}
```


## Query parameters:
### Query the current units of A

```
{
"function":"query",
"args":["a"]
}
```
