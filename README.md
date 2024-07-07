# CandyMachine_SPL_Token
- A simple UI for mint the NFTS using the spltoken.
  
## Prerequisites
- Solana CLI.
- Basic Frontend Knowledge.
- spl-token library.

## Steps  to Follow for Creating SPL Token
```
1.solana-keygen new --outfile ~/my-solana-wallet.json
2.solana config set --keypair ~/my-solana-wallet.json
3.solana airdrop 2 --url https://api.devnet.solana.com
4.spl-token create-token

Creating token HaNsXaieozs5G7fbCfvWjjKr54YXfpXV6L8owMEGSJpz under program TokenkegQfeZyiNwAJbNbGKPFXCWuBvf9Ss623VQ5DA
Address:  HaNsXaieozs5G7fbCfvWjjKr54YXfpXV6L8owMEGSJpz
Decimals:  9
Signature: z5sY2b3EEtBFiJBD7j2XaA7tUxcTZCdX83SLLxFkTnqNtRy28GmtSABHND2wkLAtBpW5TooJSKidw8QsyxgMXDd

5.spl-token create-account HaNsXaieozs5G7fbCfvWjjKr54YXfpXV6L8owMEGSJpz
Creating account Chs2DmQ7snvndm5hDZrcSRe7AA6xtPS1GWmXPhPZH9MT

Signature: 2DVVYaBJ8R8q5635EQsMMsfQbNK5yegrxco25iYVK7ACcR6GJv6doXF5xAR3UsJNDy6CStCkNZRXYurCfRqugqug

6.spl-token mint HaNsXaieozs5G7fbCfvWjjKr54YXfpXV6L8owMEGSJpz 1000 Chs2DmQ7snvndm5hDZrcSRe7AA6xtPS1GWmXPhPZH9MT
Minting 1000 tokens
  Token: HaNsXaieozs5G7fbCfvWjjKr54YXfpXV6L8owMEGSJpz
  Recipient: Chs2DmQ7snvndm5hDZrcSRe7AA6xtPS1GWmXPhPZH9MT

Signature: 61DzdBsRGWQRVPX9KicCf9DwgkHafB4LxQFmNagz3BaqM8QdJEEd2TzPZag39v3xrYPSzDiZFNPTnyfempS5N25E

```

## Steps to Follow to Create,deploy,mint CandyMachine
```
 1.sugar upload : to upload assets.
 2. sugar verify : to verify the config.
 3. sugar deploy :to deploy the assests to the candymachine.
 4.sugar validate :to validate candymachine.
 5.sugar mint : to mint the assets to solana account based on the config file.

```
## Getting Started 
-- Git clone : clone the repo using the repo link to local machine .
-- navigate to root directory.
-- run npm install.
-- modify the environmnet variables.
-- npm run dev : to start the application on the localhost at some port .

# Author
- Lokesh Reddy .
  

