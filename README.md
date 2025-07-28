# Microsoft Activation and Remote Desktop Scripts (MARDS)

<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="Logo MAS"></p>

<h1 align="center">Scripts d'Activation Microsoft (MAS)</h1>

<p align="center">Activateur Windows et Office open-source avec les méthodes d'activation HWID, Ohook, TSforge, KMS38 et KMS en ligne, ainsi qu'un dépannage avancé.</p>

<hr>
  
## Comment activer Windows / Office ?

### Méthode 1 - PowerShell (Windows 8 et versions ultérieures) ❤️

1.   **Ouvrez PowerShell**  
	Pour ce faire, appuyez sur la touche Windows + X, puis sélectionnez PowerShell ou Terminal.

2.   **Copiez et collez le code ci-dessous, puis appuyez sur Entrée.**  
```
irm https://get.activated.win | iex
```
Alternativement, vous pouvez utiliser la commande suivante (elle sera dépréciée dans le futur) :  
```
irm https://massgrave.dev/get | iex
```

3.   Vous verrez les options d'activation. Choisissez les options d'activation surlignées en vert.

4.   C'est tout !

---

### Méthode 2 - Traditionnelle (Windows Vista et versions ultérieures)

<details>
  <summary>Cliquez ici pour voir</summary>
  
1.   Téléchargez le fichier en utilisant l'un des liens ci-dessous :  
`https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip`  
ou  
`https://git.activated.win/massgrave/Microsoft-Activation-Scripts/archive/master.zip`
2.   Faites un clic droit sur le fichier zip téléchargé et extrayez-le.
3.   Dans le dossier extrait, trouvez le dossier nommé `All-In-One-Version`.
4.   Exécutez le fichier nommé `MAS_AIO.cmd`.
5.   Vous verrez les options d'activation. Suivez les instructions à l'écran.
6.   C'est tout !

</details>

---

- Pour activer des produits supplémentaires tels qu'**Office pour macOS, Visual Studio, RDS CALs et Windows XP**, consultez [ici](https://massgrave.dev/unsupported_products_activation).
- Pour exécuter les scripts en mode non assisté, consultez [ici](https://massgrave.dev/command_line_switches).

---

## Activation de la connexion Bureau à distance avec un compte Microsoft

Pour utiliser le Bureau à distance avec un compte Microsoft, suivez ces étapes :

1. Ouvrez la boîte de dialogue "Exécuter" (Win+R).
2. Entrez la commande suivante, en remplaçant `username@example.com` par l'adresse e-mail de votre compte Microsoft :

   ```
   runas /u:MicrosoftAccount\username@example.com winver
   ```

3. Appuyez sur Entrée. La boîte de dialogue "À propos de Windows" devrait s'ouvrir, indiquant que la commande a réussi.

Cette commande met en cache les informations d'identification de votre compte Microsoft, permettant ainsi l'utilisation du Bureau à distance avec ce compte.

---

### Ça ne fonctionne pas ❓

- Si vous **ne parvenez pas à lancer MAS** en utilisant la méthode PowerShell, veuillez vous référer à la **Méthode 2** listée ci-dessus.
- Si MAS est lancé et que le script affiche des erreurs, vérifiez les étapes de dépannage mentionnées en bleu et essayez de les suivre.
- Si vous avez des problèmes, n'hésitez pas à nous contacter [ici](https://massgrave.dev/troubleshoot).

---

> [!NOTE]
>
> - La commande IRM dans PowerShell télécharge un script depuis une URL spécifiée, et la commande IEX l'exécute.
> - Vérifiez toujours l'URL avant d'exécuter la commande et vérifiez la source si vous téléchargez manuellement les fichiers.
> - Soyez prudent, car certains diffusent des malwares déguisés en MAS en utilisant des URLs différentes dans la commande IRM.

---

```
Dernière Version : 3.4
Date de sortie : 3-Juin-2025
```

### [Dépannage / Aide](https://massgrave.dev/troubleshoot)
### [Télécharger Windows et Office originaux](https://massgrave.dev/genuine-installation-media)
### Page d'accueil - [https://massgrave.dev/](https://massgrave.dev/)

<div align="center">
  
[![1.1]][1]
[![1.2]][2]
[![1.3]][3]

</div>

<div align="center">
  
[![1.4]][4]
[![1.5]][5]
[![1.6]][6]
[![1.7]][7]

</div>

[1.1]: https://massgrave.dev/img/logo_github.png (GitHub)
[1.2]: https://massgrave.dev/img/logo_azuredevops.png (AzureDevOps)
[1.3]: https://massgrave.dev/img/logo_gitea.png (Self-hosted Git)

[1.4]: https://massgrave.dev/img/logo_discord.png (Chat with us without signup)
[1.5]: https://massgrave.dev/img/logo_reddit.png (Reddit)
[1.6]: https://massgrave.dev/img/logo_bluesky.png (Bluesky)
[1.7]: https://massgrave.dev/img/logo_x.png (Twitter)

[1]: https://github.com/massgravel/Microsoft-Activation-Scripts
[2]: https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts
[3]: https://git.activated.win/massgrave/Microsoft-Activation-Scripts
[4]: https://discord.gg/j2yFsV5ZVC
[5]: https://www.reddit.com/r/MAS_Activator
[6]: https://bsky.app/profile/massgrave.dev
[7]: https://twitter.com/massgravel

---

<p align="center">Fait avec Amour ❤️</p>