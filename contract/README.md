# dice_contract

## testnet

```ps1
near login

near deploy fc1943s.testnet "dist/dice.wasm" --networkId testnet
near call fc1943s.testnet new --networkId testnet --accountId fc1943s.testnet

near call fc1943s.testnet generate_random_number --networkId testnet --accountId fc1943s.testnet --gas 110000000000000 "{\`"key\`": \`"\`", \`"proof\`": \`"\`", \`"max\`": 1}"
```

```txt
testnet
mynearwallet.com
fc1943s.testnet

height message cook awesome coast glide crush flush pave brick size delay
```

## mainnet

```ps1
near login

near deploy luckier.near "dist/dice.wasm" --networkId=mainnet --accountId=fc1943s.near
near call luckier.near new --networkId mainnet --accountId=fc1943s.near

near call luckier.near generate_random_number --accountId=fc1943s.near --networkId=mainnet --gas 110000000000000 "{\`"key\`": \`"\`", \`"proof\`": \`"\`", \`"max\`": 1}"
```
