# Recovery using Etherscan

This guide will walk you through the process of repaying and claiming a repaid credit or defaulted collateral in case of the main interface being down.

## Claiming a repaid loan or defaulted collateral

1. Go to the Etherscan page for the [Loan contract](https://etherscan.io/address/0x719A69d0dc67bd3Aa7648D4694081B3c87952797#writeContract). You can find the address of the Loan contract on [PWNDAO GitHub](https://github.com/PWNDAO/pwn_protocol).
2. Connect your wallet with the `Connect to Web3` button.
3. Open the `claimLOAN` function.
4. Enter the LOAN ID to claim. The LOAN ID is the ID of the LOAN token representing the loan in your wallet. You can view your NFTs on [OpenSea](https://opensea.io/).
4. Click on the `Write` button.
5. Confirm the transaction in your wallet.
6. Once the transaction is confirmed, you will receive the repayment or collateral in your wallet.

## Repaying a loan

Before repaying a loan, you need to have enough of the credit asset in your wallet to repay the loan. 
Additionally, you'll have to approve the Loan contract to spend your credit asset on your behalf by calling the `approve` function on the credit asset contract with the Loan contract address as the spender and the amount of credit asset to repay as the amount.

1. Go to the Etherscan page for the [Loan contract](https://etherscan.io/address/0x719A69d0dc67bd3Aa7648D4694081B3c87952797#writeContract). You can find the address of the Loan contract on [PWNDAO GitHub](https://github.com/PWNDAO/pwn_protocol).
2. Connect your wallet with the `Connect to Web3` button.
3. Open the `repayLOAN` function.
4. Enter the LOAN ID to repay. The LOAN ID is the ID of the LOAN token representing the loan in your wallet. You can view your NFTs on [OpenSea](https://opensea.io/).
6. Click on the `Write` button.
7. Confirm the transaction in your wallet.
8. Once the transaction is confirmed, you will receive the collateral in your wallet.
