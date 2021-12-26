# Solidity_Counter
Basic counter in Solidity (Remix IDE)

Steps to compile:

Download Remix IDE app on Desktop, Windows, or Linux. Or use the web based version.

Remix IDE compiler configuration settings.
Check Compiler 0.5.17

Language: Solidity
EVM Version: Byzantium

When deploying the contract, make sure you have a value in the uint256 _count field.

Otherwise you will run into the following error when compiling: 

"creation of Counter errored: Error encoding arguments: Error: invalid BigNumber string (argument="value" value="" code=INVALID_ARGUMENT version=bignumber/5.5.0)"
