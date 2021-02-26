# Smart-contract-BookStore

Application simple smart contract "BookStore" cette application est basée à la technologie Blockchain qui nous permet de vendre et voir les caracteristiques des livres
à vendre.

Languages : Solidity, Javascript

Framework : Truffle

Utils : Web3, Ganache


Pour compiler et déployer cette application il faut installer les languages et les outils ci-dessus et ouvrir le dossier Test_BookStore 

Ecrire dans le terminal les commandes suivantes:


$ truffle init


$ truffle migrate --compile-all --reset


$ truffle console --network development   // pour travailler dans la console et gerer les fonctions necessaires


NB: vous pouvez changer le nom de network dans notre cas c'est sous le nom development


truffle(development)> BookStore.address


truffle(development)> BookStore.deployed().then(function(instance){app=instance;}) // pour creer une instance de cette application 


truffle(development)> app.getBook()


truffle(development)> web3.eth.getAccounts() // pour renvoyer les comptes dans le ganache 












