## Nexus Prover Node 
Ce site Web dispose d'un fichier CLI qui utilise Chromium pour le système écosystémique Nexus et l'ampoule NEX.  

### Système de gestion des déchets  
- **Minimum**  
  - **Processeur** : 4  
  - **Mémoire (RAM)** : 8 Go  
  - **Stockage** : Disque SSD de 50 Go  
  - **Réseau** : 100 Mbps  

---

### Création d'un compte Nexus  
- Rendez-vous sur le site : https://app.nexus.xyz/  
- Envoyez un e-mail.  
- Connectons-vous.  
- Si vous le souhaitez, vous pouvez configurer le portefeuille ouvert par e-mail depuis les paramètres et le déplacer dans votre propre portefeuille.  

### Contribution via le Site Web  
Vous avez également la possibilité de vous connecter à Nexus sur le Web pour l'activer.  

### Contribution avec Chromium  
En installant Chrome et via l'onglet, c'est-à-dire via le Web, vous pouvez également contribuer. Si votre système le permet, vous pouvez le faire.  

### Installation  

---

### Contribution via la CLI  
#### Docker  
```bash  
sudo apt update & sudo apt upgrade -y  
sudo apt install screen curl libssl-dev pkg-config build-essential git-all protobuf-compiler -y  
sudo apt update  
```  

#### Rust  
```bash  
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh  
rustup target add riscv32i-unknown-none-elf  
```  

#### Lien  
```bash  
curl https://cli.nexus.xyz/ | sh  
```  

Après cela, acceptons les invites à l'écran (répondre par Y). Le Node ID est disponible sur le site https://app.nexus.xyz/.  

### Remarque  
Vous pouvez ensuite augmenter la RAM encore et encore.
