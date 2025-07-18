# OpenSSLite

🛡️ **OpenSSLite** est un outil en ligne de commande interactif basé sur Bash, qui simplifie l'utilisation des principales fonctionnalités de la suite OpenSSL. Il s'adresse aussi bien aux étudiants, aux pentesters qu'aux passionnés de cybersécurité souhaitant automatiser certaines tâches courantes.

## 📌 Fonctionnalités

- 🔐 **Encodage/Décodage** :
  - Base64
  - Base85
  - Hexadécimal
  - URL

- 📄 **Conversion de formats de certificats** :
  - PEM ↔ DER
  - PEM ↔ PKCS#12
  - DER ↔ PKCS#12

- 🎲 **Génération de nombres aléatoires sécurisés** :
  - En hexadécimal ou en base64
  - Longueur personnalisée

- 🔏 **Chiffrement symétrique** :
  - Tous les algorithmes OpenSSL disponibles (`openssl enc -e`)

- ✍️ **Signature numérique** :
  - Génération de signature
  - Vérification

- 🔑 **Hashing (Empreinte)** :
  - MD5, SHA1, SHA256, SHA512, etc.

## 🚀 Installation

Clone le dépôt :

```bash
git clone https://github.com/YahyaBennani/opensslite.git
cd opensslite
chmod +x opensslite.sh
