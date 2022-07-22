# Building subgraph for GRT token transfer event

### Prereuisite
- `node js` installed.
- `graph-cli` installed
```
npm i -g @graphprotocol/graph-cli
```

### Instruction
Build schema
```
npm run codegen
```
Authenticate graph studio
```
graph auth
```
Deploy graph
```
graph deploy --studio <nameOfYourSubgraph>
```


