# Solidity_Counter
Basic counter in Solidity (Remix IDE)

Steps to compile:

1. Download Remix IDE app on Desktop, Windows, or Linux. Or use the web based version.

Remix IDE compiler configuration settings.

2. Check Compiler 0.5.17

3. Language: Solidity

4. EVM Version: Byzantium

5. When deploying the contract, make sure you have a value in the uint256 _count field.

Otherwise you will run into the following error when compiling: 

"creation of Counter errored: Error encoding arguments: Error: invalid BigNumber string (argument="value" value="" code=INVALID_ARGUMENT version=bignumber/5.5.0)"
