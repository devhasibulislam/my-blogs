# *Chrome Dino* unlimited life
Paste following code on *browser console*
```bash
Runner.instance_.gameOver=() => { }
```

# Node package manager operation
1. Update npm
   ```sh
   npm install npm@latest -g
   ```
2. Clear npm cache
   ```sh
   npm cache clean -f
   ```
3. Install n as node
   ```sh
   npm install -g n
   ```
4. Update node to latest version
   ```sh
   n latest
   ```
# Yarn package manager operation
1. Install yarn
   ```sh
   npm install -g yarn
   ```
2. Update yarn
   ```sh
   yarn set version latest

# *Node* Random Bytes Generator Code
Type `node` on the *terminal* then *paste* following code
```bash
require('crypto').randomBytes(64).toString('hex')
```
