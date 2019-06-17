# ERC-20
ERC-20 token deployment

Notes:-
https://www.devprovider.com/creating-ethereum-token/
https://medium.com/@JusDev1988/build-your-own-token-81e8eeb94740
https://cointelegraph.com/explained/erc-20-tokens-explained

truffle console
BasicToken.deployed().then(t => token = t)
token.totalSupply().then(s => s.toNumber())
token.balanceOf(web3.eth.accounts[0]).then(b => b.toNumber())
token.balanceOf('0x6392Eb91eE839307b59eFA534FD711771779814C').then(b => b.toNumber());
token.balanceOf('0x79AEd25dA68c92437FCA6C1BD5CA909DD7CF5F98').then(b => b.toNumber());
token.transfer('0x79AEd25dA68c92437FCA6C1BD5CA909DD7CF5F98', 10000)

