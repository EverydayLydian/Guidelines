# Token Snapshot

There are multiple snippets and tools that helps us take snapshot of token holders.

1) https://github.com/halaprix/getHolderSnapshot
2) https://sol-nft.tools/?mode=holders
3) I will be adding more over time.

***
## getHolderSnapshot

First, I will cover getHolderSnapshot in this article.

Step 1:
Create a folder and change directory by running following commands:

```
mkdir Snapshot
cd Snapshot
```

Step 2:
Clone getHolderSnapshot to your newly created folder:

```
git clone https://github.com/halaprix/getHolderSnapshot
```

Step 3: 
Change directory to getHolderSnapshot project:

```
cd getHolderSnapshot
```

Step 4:
Install dependencies:

```
yarn install
```

Step 5:
Now, you can edit input.txt file that is located in the getHolderSnapshot folder to replace sample list of tokens with your list.

Step 6:
Once you are done with input.txt file edit, you can run the following command to take a snapshot of your token holders:

```
node .\getSnapshot.js input.txt output.txt
```

After running this command, an output.txt file should be generated under getHolderSnapshot folder. You can find the list of token holders in JSON format.

***

## sol-nft.tools 

If you feel lazy, you can use @0xAlice_ tool to get token holders. This one is pretty straightforward. 

Step 1: 
Go to https://sol-nft.tools/?mode=holders

Step 2: 
Paste your list of mint id in JSON format 

Sample list:
```
[
  "BZzRwLaqhBNLoXPZ4f3fwiNwfAUJaNm8nsopQTBBxz5F",
  "7HsKK1Cke9uysgZXHDGuHe7sgbaVLDTWZ4Sotd3fgUeT",
  "HTxQsadtKGyAJgM7pMGteKadbUhoVMe8566Qv4QEv5fr"
]
```

Step 3:
Hit "Gib Holders!" button. You should see a JSON file download. You can find the list of holders. If one wallet holds more than 1 token, this tool provides an aggregate list of unlike getHolderSnapshot.

***

Let me know if you have any questions or concerns on Twitter: @EverydayLydian
If you feel generous today, send tips (SOL): 7kft6sap6hpkaSuDcjMgmmjFCqqnXtrYpEvLDZNBPGb6





