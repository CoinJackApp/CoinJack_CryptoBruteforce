
<img width="843" height="338" alt="Screenshot 2025-07-26 063352" src="https://github.com/user-attachments/assets/a77399d8-7956-415b-ac4e-a339d3b86cd8" />

Version 0.3 is available!

Any crypto wallet is basically just a combination of 12 or 24 words. 
The amount of combinations is so vast that to randomly generate the same word phrase twice is almost impossible. 
However, there's still a slim chance of creating a wallet that has already been created, used, and has funds on it.

CoinJack is a Windows application developed to test this theory in practice.
It generates random seed phrases and checks if corresponding wallets have funds.

![gif](https://github.com/user-attachments/assets/da23d7b5-c449-47fe-b017-61d6d32b6873)

CoinJack has a vast functionality:
1) Supports Bitcoin, Ethereum, Ethereum-based tokens (like USDT, etc), Solana;
2) Supports various seed lengths (12/24);
3) Allows to adjust request intervals (not to flood the servers and get your IP banned);
4) Allows to check the balances of a specific wallet;
5) Allows to calculate the checksum of the given 11/23 word combinations (Just a fun feature to play around with);
6) Supports offline BTC search (Full version contains the database with ALL bitcoin addresses with over 1 BTC);
7) Hardware acceleration for P2PKH addresses reaching the speed of hundreds of millions of addresses per second on high-end GPU's.
   Use "Info" button in the app to learn more.

CoinJack uses either offline database or online third-party blockchain explorers to check balances (hence requires internet connection).
You can test CoinJack by checking the balance of any known wallet (like "abandon x 11, about") and compare the generated addresses and balances to any other crypto wallet apps (like TrustWallet).

Developers of CoinJack do not condone stealing! Creating wallets and looking up balances is not a crime. Stealing funds is!
When a non-zero balance wallet is found, we advise not to spend the funds but merely appreciate the unbelievably low odds of this event and share your story online. 
This program was created for research purposes only!
