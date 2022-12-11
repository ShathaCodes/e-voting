# E-Voting DApp using Blockchain technology

## Installation :

### 1. npm
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.3/install.sh | bash
nvm install node
n=$(which node)
n=${n%/bin/node}
chmod -R 755 $n/bin/* 
sudo cp -r $n/{bin,lib,share} /usr/local 
```

### 2.  truffle
```
npm install -g truffle
```

### 3.  ganache
```
npm install ganache --global
```
### 4.  MetaMask for your browser
```
https://metamask.io/download/
```

### Verify everything is working 
```
truffle version
```

---

## Execute :

1. Open a terminal and run
```
truffle migrate 
```

if you've edited the Election.sol file
```
truffle migrate --reset
```

2. Then run
```
npm run dev
```

3. Create wallet in metamask plugin

4. Import accounts from Ganache

![import1](https://raw.githubusercontent.com/ShathaCodes/e-voting/main/exec/import1.PNG)

![import2](https://raw.githubusercontent.com/ShathaCodes/e-voting/main/exec/import2.PNG)

![import3](https://raw.githubusercontent.com/ShathaCodes/e-voting/main/exec/import3.PNG)

5. Vote away!

![vote1](https://raw.githubusercontent.com/ShathaCodes/e-voting/main/exec/vote1.PNG)

![vote2](https://raw.githubusercontent.com/ShathaCodes/e-voting/main/exec/vote2.PNG)