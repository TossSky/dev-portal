# Initiating Conversion

### Algorithm for Working with the Ethereum-Cardano Bridge

Bridging tokens from one chain to another involves the following steps:

---

### 1. Set Up the Token Pair  
Select the token and the direction of the transfer (e.g., Ethereum to Cardano or Cardano to Ethereum).  

::: warning
Claiming tokens on the Ethereum network is a paid operation. Ensure you have at least **0.005 ETH** in your wallet to cover the gas fee for the claim transaction.
:::

---

### 2. Enter the Amount of Tokens  
Input the number of tokens you wish to transfer.  

<ImageViewer src="/assets/images/products/Bridge/input-tokens.webp" alt="InputTokens"/>

---

### 3. Conversion Steps  

#### **For Ethereum to Cardano**  

- Click on the ‘Approve’ button that appears

<ImageViewer src="/assets/images/products/Bridge/approve-button.webp" alt="ApproveButton"/>

1. **Approve Tokens:**  
   - A **Metamask** wallet prompt will appear requesting approval for the specified amount of tokens.  
   - You must approve at least the amount you intend to transfer.  
   - This step is mandatory, as it allows the bridge to interact with your specified tokens.

<ImageViewer src="/assets/images/products/Bridge/metamask-approve.webp" alt="MetamaskApprove"/>

> Approve in MetaMask is required for the smart contract of our bridge to manage a specified token in a specified amount and facilitate its transfer between networks. You can learn more about it [here](https://support.metamask.io/transactions-and-gas/transactions/what-is-a-token-approval/).

2. **Convert Tokens:**  
   - Once the approval is complete, the **"Convert"** button will appear.  
   - Click **"Convert"** and follow the wallet prompts to sign the transaction.  
   - Tokens will be **burned** on the Ethereum network, and an equivalent amount will be **minted** on the Cardano network.  

<ImageViewer src="/assets/images/products/Bridge/convert-button.webp" alt="ConvertButton"/>

---

#### **For Cardano to Ethereum**  
- There is no approval step required.  
- Simply click the **"Convert"** button and follow the wallet prompts to sign the transaction.  
- Tokens will be **burned** on the Cardano network, and an equivalent amount will be **minted** on the Ethereum network.  

> **Important:**  
> Claiming tokens on the Ethereum network is a paid operation. Ensure you have at least **0.005 ETH** in your wallet to cover the gas fee for the claim transaction.

---

### Additional Notes  
- Transactions are **irreversible**, so verify all details before confirming.  
- Make sure you have enough funds to cover any applicable fees.  
