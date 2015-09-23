# EtherPool

This is the pool source that runs the weipool backend share processing / payments

# Requirements
1. Redis
2. Geth
3. Node
# Usage
First change the config.js file to match your setup

Type
> node run.js

to start up the share server

> node updateBalances.js 

to update the balances

> python runPayments.py

to run payments


