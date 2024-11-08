# Microsoft Activation and Remote Desktop Scripts (MARDS)

<p align="center"><img src="https://lookimg.com/images/2023/09/25/QY5RTR.png" alt="Logo de MARD" height="128"></p>

**MARDS** est un fork en français du projet [Microsoft Activation Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts) original, avec une petite option supplémentaire. C'est un ensemble de scripts PowerShell permettant d'activer de manière simple et sécurisée vos installations Windows et Office 365. Il utilise des méthodes d'activation modernes comme HWID, Ohook, KMS38 et KMS en ligne, tout en mettant l'accent sur l'open-source et une détection antivirus réduite.

## Installation et utilisation

### Méthode 1 : Installation via PowerShell (recommandée)

1. Ouvrez PowerShell en faisant un clic droit sur le menu Démarrer de Windows et sélectionnez "PowerShell".
2. Exécutez la commande suivante :

   ```powershell
   irm https://get.activated.win | iex
   ```

3. Suivez les instructions à l'écran pour activer vos produits Microsoft.

### Méthode 2 : Installation manuelle

1. Téléchargez le script depuis [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip) ou [Bitbucket](https://bitbucket.org/WindowsAddict/microsoft-activation-scripts/get/master.zip).
2. Décompressez l'archive téléchargée.
3. Ouvrez le dossier `All-In-One-Version` et exécutez le fichier `MAS_AIO.cmd`.
4. Suivez les instructions à l'écran pour activer vos produits Microsoft.

## Activation de la connexion Bureau à distance avec un compte Microsoft

Pour utiliser le Bureau à distance avec un compte Microsoft, suivez ces étapes :

1. Ouvrez la boîte de dialogue "Exécuter" (Win+R).
2. Entrez la commande suivante, en remplaçant `username@example.com` par l'adresse e-mail de votre compte Microsoft :

   ```
   runas /u:MicrosoftAccount\username@example.com winver
   ```

3. Appuyez sur Entrée. La boîte de dialogue "À propos de Windows" devrait s'ouvrir, indiquant que la commande a réussi.

Cette commande met en cache les informations d'identification de votre compte Microsoft, permettant ainsi l'utilisation du Bureau à distance avec ce compte.

## Options en ligne de commande

Pour exécuter les scripts en mode non assisté, consultez la [documentation des commandes en ligne de commande](https://massgrave.dev/command_line_switches.html).
