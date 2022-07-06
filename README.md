# opend

# To Install and Run the Project

1. start local dfx

```
dfx start --clean
```

2. Run NPM server

```
npm start
```

3. Deploy canisters

```
dfx deploy --argument='("Name NFT", principal "Your principal identity", (vec {Nat8 array of Image}))'
```

4. Head to localhost

http://localhost:8080/
