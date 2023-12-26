<p align="center"><img src="https://lookimg.com/images/2023/09/25/QY5RTR.png" alt="Logo de MARD" height="128"></p>

<h1 align="center">Scripts d'Activation Microsoft et de Bureau à Distance (MARDS)</h1>

<p align="center">Un activateur Windows et Office utilisant les méthodes d'activation HWID / Ohook / KMS38 / Online KMS, avec un accent sur le code open-source et moins de détections d'antivirus.</p>
<hr>

## Téléchargement / Comment l'utiliser ?

### Méthode 1 - PowerShell (Recommandé)

- Sur Windows 8.1/10/11, faites un clic droit sur le menu de démarrage de Windows et sélectionnez PowerShell ou Terminal (Pas CMD).
- Copiez-collez le code ci-dessous et appuyez sur Entrée\
  `irm https://massgrave.dev/get | iex`
- Vous verrez les options d'activation, et suivez les instructions à l'écran.
- C'est tout.

### Méthode 2 - Traditionnelle

- Téléchargez le fichier depuis [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip) ou [Bitbucket](https://bitbucket.org/WindowsAddict/microsoft-activation-scripts/get/master.zip)
- Faites un clic droit sur le fichier zip téléchargé et extrayez-le
- Dans le dossier extrait, trouvez le dossier nommé `All-In-One-Version`
- Exécutez le fichier nommé `MAS_AIO.cmd`
- Vous verrez les options d'activation, et suivez les instructions à l'écran.
- C'est tout.

Pour exécuter les scripts en mode non assisté, vérifiez [ici](https://massgrave.dev/command_line_switches.html)

## Utilisation du RDP avec un compte Microsoft

Pour utiliser le Bureau à distance avec un compte Microsoft, vous devez exécuter une commande spécifique sur le PC qui héberge la session de bureau à distance (doit exécuter Windows Pro ou une version supérieure). Voici comment faire :

1. Ouvrez la boîte de dialogue Exécuter (appuyez sur Win+R).
2. Tapez la commande suivante, en remplaçant `username@example.com` par l'adresse e-mail de votre compte Microsoft que vous utilisez pour vous connecter à l'ordinateur :

    ```
    runas /u:MicrosoftAccount\username@example.com winver
    ```

3. Tapez la commande exactement comme indiqué, en ne changeant que l'adresse e-mail qui vient après le symbole `\`.

Cette commande exécute le programme "winver" sous les informations d'identification du compte utilisateur spécifié. Cela met en cache vos informations d'identification de compte Microsoft. Comme votre compte utilisateur local n'avait pas de mot de passe, il n'était pas éligible pour l'utilisation de RDP même s'il avait les permissions appropriées. Après avoir fourni le mot de passe et appuyé sur Entrée, vous saurez que cela a fonctionné si vous voyez la boîte de dialogue À propos de Windows s'ouvrir. Vous pouvez la fermer ainsi que la fenêtre du terminal - vous avez terminé.

---

<p align="center">Remixé </p>
