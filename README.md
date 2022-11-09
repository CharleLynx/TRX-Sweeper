# TRX-Sweeper

## CONFIGURATION
### first configure the bot by correctly filling the fields in (config.json) file
### Fields:
  ### "PRIVATE_KEY" - private key of the wallet you wish to activate multisig or auto-withdraw *(main wallet)*
  ### "SIGNER_PRIVATE_KEY" - private key of external wallet you want to use for signing the main wallet.
  ### "RECIPIENT" - TRX address of wallet you want to receive funds from auto-withdraw
  ### "API_KEY" - API Key for making requests to TRX Blockchain *(you can get it free from: https://trongrid.io)*


## USAGE

### Signing wallet
#### Run: npm run sign

### Activating auto-withdraw
#### Run: npm run start
