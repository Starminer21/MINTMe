# MINTMe
FOLLOW ME GO TO https://github.com/mintme-com/miner/releases
How to make minning mintme
In order to mine on this pool you need to execute Mintme.com-coin-miner with the following parameters:
-o pool.webchain.network:3333 -u <address> -p x

<address> is your address for payouts, generate one with webchaind.

In case you have doubts on how to create a wallet, follow the steps Create or manage account(s) on github.

Full example: webchain-miner -o pool.webchain.network:3333 -u 0x296A405D436Ad4D43edD1746306d4E9f001C555f -p x
Prefix 0x must be added to generated address.

To mine on lower difficulty (12500), instead of pool.webchain.network:3333, use address pool.webchain.network:2222
