## ArQmA 2/2 Multisig

First, the wallet to be converted to multisig **must be empty**.
 It is best to use a brand-new walllet for the purpose, although not 
required. It is strongly advised to make a copy of the wallet files 
first, just in case something goes wrong.

### Set-up

#### Step 1 Initiate Creation of Multisig Wallet and Exchange Data

**Person A** commands:

`[wallet 47HSuD]: prepare_multisig`

The output will be something like: 

MultisigV1WHyBiEPV5rv3jgU59QUv2ZYTvmN3pwzCL8mp5jTDxkkhRzDjL1T8A2dHTYLmprbUsiLzvPLqRc1GkFHp3mq7dFq6BiE98Ur5cD6P46YYLd5QwD4diqe4VRSiS7GYHATbL4cLGidyNUbWha4EU7ET2jfJ7UKUVZRhNb5prZxfsJddbzaw
Send this multisig info to all other participants, then use make_multisig &lt;info1&gt; [&lt;info2&gt;...] with others' multisig info
  
This includes the PRIVATE view key, so needs to be disclosed only to that multisig wallet's participants

Copy the entire line 

Multisig...bzaw be sure to capture the whole thing when copying. Send this line to person B.

**Person B** does the same and sends his output to person A. Person B commands:

`[wallet 48e86K]: prepare_multisig`

Person B gets the output

MultisigV1ZST26VmNuozbbHL9PeDuqiLDuMLCmaCRxBBLoK7yuxsHXyUiMr2SjxXgnsWrbmVRpghFTtcHEDLDnbPcqdoSuum1bLCFvmoFGrK7z3AtizKPTG96ukb4mzzqPcCD55ZCb1Y8cUL4RipVtcB4YbzZyK5eZdRLxAKi8TvyTD9h3QjVraXs
Send this multisig info to all other participants, then use make_multisig &lt;info1&gt; [&lt;info2&gt;...] with others' multisig info
This includes the PRIVATE view key, so needs to be disclosed only to that multisig wallet's participants and sends it to person A.

#### Step 2 Create Multisig Wallets

Both person A and person B now have the 

Multisig... text
 from the other one. With that, each of them can create their part of 
the multisig wallet. Before you proceed, note that the **wallet will lose access to the underlying account when converted to multisig**.
 This is not really a problem, since we started with an empty one, and 
if all goes ok with this step, you won't ever need it unless you want to
 go through the process again for whatever reason (like HDD died, but 
you have the seed mnemonic of the underlying account and want to 
reconstruct the multisig wallet).

**Person A** commands:

`[wallet 47HSuD]: make_multisig 2 MultisigV1ZST26VmNuozbbHL9PeDuqiLDuMLCmaCRxBBLoK7yuxsHXyUiMr2SjxXgnsWrbmVRpghFTtcHEDLDnbPcqdoSuum1bLCFvmoFGrK7z3AtizKPTG96ukb4mzzqPcCD55ZCb1Y8cUL4RipVtcB4YbzZyK5eZdRLxAKi8TvyTD9h3QjVraXs`

and the output will be something like:

2/2 multisig address: 47RGRFeLPT51qvDWuw7SGf57JK7AziAVqYucct8z5yEDQ1XqU8zKEjidWjqPXk7PuHP3MJDN2AJATKy9PH7zaGV7MB8X6CH

**Person B** commands:

`[wallet 48e86K]: make_multisig 2 MultisigV1WHyBiEPV5rv3jgU59QUv2ZYTvmN3pwzCL8mp5jTDxkkhRzDjL1T8A2dHTYLmprbUsiLzvPLqRc1GkFHp3mq7dFq6BiE98Ur5cD6P46YYLd5QwD4diqe4VRSiS7GYHATbL4cLGidyNUbWha4EU7ET2jfJ7UKUVZRhNb5prZxfsJddbzaw`

and the output should be something like:

2/2 multisig address: 47RGRFeLPT51qvDWuw7SGf57JK7AziAVqYucct8z5yEDQ1XqU8zKEjidWjqPXk7PuHP3MJDN2AJATKy9PH7zaGV7MB8X6CH

Now exchange addresses and compare, **they must be the same**.

### Receiving

#### Step 1 Fund The Multisig Account

This is simple. Just send to the shared address. You can send multiple times, same like normal wallet. You can use payment ID as well,
 or generate an integrated address to receive funds.

Best part, whomever is sending the funds won't be able to tell that the address belongs to a multisig wallet since it looks as any other.

#### Step 2 Check Multisig Account Balance

Just open the wallet and command refresh. Once completed, both persons can verrify that the funds arrived.

**Person A** commands:

`[wallet 47HSuD]: show_transfers and can see all incoming transfers.`

 1357156     in      07:50:35 PM       0.100000000000 88ba687dc79a0b39e6de6d0763eda8363d33d9f58ec9a096171bd9a7f1dae873 0000000000000000 - 
 1357161     in      08:00:18 PM       0.100000000000 d6ac845b9400759525519cdc5d514eb8f5b1d265b24d1c016e75b20ed3b4b7da 0000000000000000 - 

**Person B** can do the same:

`[wallet 48e86K]: show_transfers and will see the same:`

 1357156     in      07:50:35 PM       0.100000000000 88ba687dc79a0b39e6de6d0763eda8363d33d9f58ec9a096171bd9a7f1dae873 0000000000000000 - 
 1357161     in      08:00:18 PM       0.100000000000 d6ac845b9400759525519cdc5d514eb8f5b1d265b24d1c016e75b20ed3b4b7da 0000000000000000 - 

### Spending

#### Step 1 Syncronizing Key Images

Without this step, it will not be possible to create a spending transaction.

**Person A** commands:

`[wallet 47HSuD]: export_multisig_info testmp1 where `

testmp1 can be any filename. The output will be:

Multisig info exported to testmp1

The file 

testmp1 will be located in the shell working folder*

Person A sends that file to Person B.

**Person B** does the same and commands:

`[wallet 48e86K]: export_multisig_info testmp2 and the output will be:`

Multisig info exported to testmp2

The file testmp2 will be located in the shell working folder*

Person B sends that file to person A.

Now, they must both import each other's file.

**Person A** commands:

`[wallet 47HSuD]: import_multisig_info testmp2 (the wallet will look for it in the shell working folder*) and the output will look like:`

2 outputs found in testmp2
Height 1357156, transaction &lt;88ba687dc79a0b39e6de6d0763eda8363d33d9f58ec9a096171bd9a7f1dae873&gt;, received 0.100000000000
Height 1357161, transaction &lt;d6ac845b9400759525519cdc5d514eb8f5b1d265b24d1c016e75b20ed3b4b7da&gt;, received 0.100000000000

**Person B** commands:

`[wallet 48e86K]: import_multisig_info testmp1 (the wallet will look for it in the shell working folder*) and the output will look like:`

2 outputs found in testmp1
Height 1357156, transaction &lt;88ba687dc79a0b39e6de6d0763eda8363d33d9f58ec9a096171bd9a7f1dae873&gt;, received 0.100000000000
Height 1357161, transaction &lt;d6ac845b9400759525519cdc5d514eb8f5b1d265b24d1c016e75b20ed3b4b7da&gt;, received 0.100000000000
Multisig info imported

#### Step 2 Preparing Spending Transaction

Either person A or person B can do this, it doesn't matter. To avoid 
weird things from happening only do it for 1 transaction at a time.

**Person A** performs the usual 

transfer command:

`[wallet 47HSuD]: transfer 47wbKEXBGnyHohezMGpD6y2SFNczrSpeSfQgFW5cMxMziFuHpBWM9yjBLJ1iTv31AwN6daPg1QXfRKBJGq2XZDekNqv8gsP 0.15`

The output will look like:

Unsigned transaction(s) successfully written to file: multisig_arqma_tx*

Check in the folder where you started 

arqma-wallet-cli from*. There should be a file named 

multisig_arqma_tx.

Send the file multisig_arqma_tx to the person B.

**Person B** must finish the signature. Person B copies the file to the same folder from where he started (or will start) 

arqma-wallet-cli*.

Then, Person B commands:

`[wallet 48e86K]: sign_multisig multisig_arqma_tx and a prompt will be displayed to allow person B to check the transaction before signing:`

Loaded 1 transactions, for 0.200000000000, fee 0.015570240000, sending 0.150000000000 to 47wbKEXBGnyHohezMGpD6y2SFNczrSpeSfQgFW5cMxMziFuHpBWM9yjBLJ1iTv31AwN6daPg1QXfRKBJGq2XZDekNqv8gsP, 0.034429760000 change to 47RGRFeLPT51qvDWuw7SGf57JK7AziAVqYucct8z5yEDQ1XqU8zKEjidWjqPXk7PuHP3MJDN2AJATKy9PH7zaGV7MB8X6CH, with min mixin 4. Is this okay? (Y/Yes/N/No):

If ok, answer 

Y, and the output will look like:

Transaction successfully signed to file multisig_arqma_tx, txid bb998b00dad0c245b45b975277d9b685592b412fd5fb58b2c1805091418c8b49.

Finally, person B submits the transaction to the network by commanding:

`[wallet 48e86K]: submit_multisig multisig_arqma_tx and there will be a confirmation prompt: `

Loaded 1 transactions, for 0.200000000000, fee 0.015570240000, sending 0.150000000000 to 47wbKEXBGnyHohezMGpD6y2SFNczrSpeSfQgFW5cMxMziFuHpBWM9yjBLJ1iTv31AwN6daPg1QXfRKBJGq2XZDekNqv8gsP, 0.034429760000 change to 47RGRFeLPT51qvDWuw7SGf57JK7AziAVqYucct8z5yEDQ1XqU8zKEjidWjqPXk7PuHP3MJDN2AJATKy9PH7zaGV7MB8X6CH, with min mixin 4. Is this okay? (Y/Yes/N/No):

If ok, answer 

Y, and the transaction will be sent. The output will look like:

Money successfully sent, transaction: 
&lt;bb998b00dad0c245b45b975277d9b685592b412fd5fb58b2c1805091418c8b49&gt;

The person B could also send the signed TX to person A, who could then submit it to the network himself.

If you want to make another one, you have to go back to step 1 of spending (sync the key images again).

*Note on folders and file locations, as it could create some confusions. The wallet will look for the files and export them to the 
folder from where it was started, ie where your command prompt / shell was when you called arqma-wallet-cli. It may or may not be the same 
folder as your actual wallet files or arqma-wallet-cli, depending on how you go about it.

For example, your wallet could be on some USB drive like 

f:\temp\, and your wallet software on 

c:\arqma\ and your shell working folder could be 

c:\.

If you remain in 

c:\ with the shell, you could start the wallet by its full path and specify the wallet file location: 

c:\arqma\arqma-wallet-cli.exe --wallet-file f:\temp\mywallet. In this case, all the import/export stuff would be read/written to 

c:\ because that's still your shell's working folder.

It would be probably feel more natural to 

cd into the wallet folder. Do 

f: to change drive and then 

cd f:\temp\. Then, simply start the wallet from that location by its full path again: 

c:\arqma\arqma-wallet-cli.exe --wallet-file mywallet.
 Notice how you don't have to write the full wallet path now as you're already there with your shell. In this case, all the files mentioned above would be written or read from the same folder as the wallet files.


Based on stackexchange.com
