# TRX-Sweeper

## CONFIGURATION
### first configure the bot by correctly filling the fields in (config.json) file
### Fields:
  ### "PRIVATE_KEY" - private key of the wallet you wish to activate multisig or auto-withdraw *(main wallet)*
  ### "SIGNER_PRIVATE_KEY" - private key of external wallet you want to use for signing the main wallet.
  ### "RECIPIENT" - TRX address of wallet you want to receive funds from auto-withdraw
  ### "API_KEY" - API Key for making requests to TRX Blockchain *(you can get it free from: https://trongrid.io)*





## USAGE
## Note: Refer to tutorials on how to setup and use Node.js environment.

### Signing wallet - Activating MultiSig
#### To activate multisig on a new wallet, make sure you have a minimum of 100 TRX for multisig fee. Fill the "SIGNER_PRIVATE_KEY" of the external wallet you want to use to sign the wallet. Run the command below to activate multisig

#### > npm run sign

### Activating auto-withdraw
#### > npm run start
