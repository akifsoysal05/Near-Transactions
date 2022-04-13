# Near-Transactions
Near transaction With smart contracts
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.


PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> yarn
yarn install v1.22.18
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...
Done in 4.95s.
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> yarn build:release
$ asb
Done in 23.58s.
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> near dev-deploy ./build/release/singleton.wasm/.
near : The term 'near' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify th 
at the path is correct and try again.
At line:1 char:1
+ near dev-deploy ./build/release/singleton.wasm/.
+ ~~~~
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> near dev-deploy ./build/release/simple.wasm.
near : The term 'near' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify th 
at the path is correct and try again.
At line:1 char:1
+ near dev-deploy ./build/release/simple.wasm.
+ ~~~~
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> dev-deploy ./build/release/simple.wasm.
dev-deploy : The term 'dev-deploy' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was include 
d, verify that the path is correct and try again.
At line:1 char:1
+ dev-deploy ./build/release/simple.wasm.
    + CategoryInfo          : ObjectNotFound: (dev-deploy:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> singleton.wasm,
At line:1 char:15
+ singleton.wasm,
+               ~
Missing argument in parameter list.

PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> singleton.wasm
singleton.wasm : The term 'singleton.wasm' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was
 included, verify that the path is correct and try again.                                                                program. Check the spelling of the name, or if a path was
At line:1 char:1
+ singleton.wasm
+ ~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (singleton.wasm:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> npm install --save near-sdk-as
added 110 packages, changed 39 packages, and audited 214 packages in 36s

21 packages are looking for funding
  run `npm fund` for details

6 high severity vulnerabilities

To address all issues (including breaking changes), run:

Run `npm audit` for details.
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> near dev-deploy ./build/release/singleton.wasm.
near : The term 'near' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
 spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ near dev-deploy ./build/release/singleton.wasm.
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (near:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> npm install -g near-cli
npm WARN deprecated @ledgerhq/hw-transport-u2f@5.36.0-deprecated: @ledgerhq/hw-transport-u2f is deprecated. Please use @ledgerhq/hw-transport-webusb or @ledgerhq/hw-transport-webhid. https://github.com/LedgerHQ/ledgerjs/blob/master/docs/migrate_webusb.md

added 303 packages, and audited 304 packages in 31s

25 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> near dev-deploy ./build/release/singleton.wasm.  
Please help us to collect data on near-cli usage to improve developer experience.
We will never send private information. We collect which commands are run with attributes and your account ID.
Note that your account ID and all associated on-chain transactions are already being recorded on public blockchain.


PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> near dev-deploy ./build/release/singleton.wasm  
Starting deployment. Account id: dev-1649854490105-25450361751971, node: https://rpc.testnet.near.org, helper: https://helper.testnet.near.org, file: ./build/release/singleton.wasm
Transaction Id FTdEkmo8MZLB1tdcVNdxik9ou233G3MdKJPcP2bBibDL
To see the transaction in the transaction explorer, please open this url in your browser
https://explorer.testnet.near.org/transactions/FTdEkmo8MZLB1tdcVNdxik9ou233G3MdKJPcP2bBibDL
Done deploying to dev-1649854490105-25450361751971
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> near login
If your browser doesn't automatically open, please visit this URL
https://wallet.testnet.near.org/login/?referrer=NEAR+CLI&public_key=ed25519%3A7uxUK8XYwujL6teEopp7srHKfUTw3onLjaZVuz37M3aM
Please authorize at least one account at the URL above.
                                                                                                                        aM
Which account did you authorize for use with NEAR CLI?
Enter it here:
akifsoysall.testnet

PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main> near deploy --accountId akifsoysall.testnet --wasmFile ./build/release/singleton.wasm
Starting deployment. Account id: akifsoysall.testnet, node: https://rpc.testnet.near.org, helper: https://helper.testnet.near.org, file: ./build/release/singleton.wasm
Transaction Id 6GArCc3fb7FBjh14aN9PsmjVRekCWdvaMuvqYBBc12X6
To see the transaction in the transaction explorer, please open this url in your browser
https://explorer.testnet.near.org/transactions/6GArCc3fb7FBjh14aN9PsmjVRekCWdvaMuvqYBBc12X6
Done deploying to akifsoysall.testnet
PS C:\Users\Administrator\Desktop\starter--near-sdk-as-main>
