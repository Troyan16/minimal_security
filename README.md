# Sécurité minimale

## Mot de passe
- Avoir un mot de passe complexe :
    - Pas d'information personnelle (nom d'un animal, date ou autre donnée sur votre personne)
    - Avoir des majuscules (**PAS UNIQUEMENT LA PREMIÈRE LETTRE**)
    - Caractères spéciaux (**PAS UNIQUEMENT UN . ou ! À LA FIN**)
    - Des chiffres (**PAS JUSTE APRÈS LE TEXTE**)
    - ~~Boby2019.~~ ou ~~Boby2019!~~
    - Un mot de passe avec plus de 16 caractères
    - Un mot de passe totalement aléatoire est toujours mieux
- Un mot de passe différent pour chaque site
    - Gestionnaire de mots de passe (**LOGICIEL AVEC CHIFFREMENT, PAS WORD**)
        - Stocké sur le PC (local)
            - Linux
                - [KeePassXC](https://keepassxc.org/)
            - Windows
                - [KeePass](https://keepass.info/)
        - En ligne
            - [1Password](https://1password.com/)
            - [Dashlane](https://www.dashlane.com/)
            - [LastPass](https://www.lastpass.com/)
            - ...
        - Physique
            - [Mooltipass](https://www.themooltipass.com/)
- Activer l'authentification à facteurs multiples (MFA)
    - Application
        - [Google Authenticator](https://support.google.com/accounts/answer/1066447?co=GENIE.Platform%3DAndroid&hl=fr)
        - [Microsoft Authenticator](https://www.microsoft.com/fr-fr/account/authenticator)
    - Physique
        - [Yubico](https://www.yubico.com/)
- Changer régulièrement votre mot de passe
    - Si [ces entreprises](https://en.wikipedia.org/wiki/List_of_data_breaches) se sont fait hacker, personne n'est en sécurité

## Lien/URL
- **TOUJOURS** considérer un lien comme malveillant
- Contrôler l'orthographe du lien (ex: /facebouk.com/)
- Contrôler si l'affichage et l'hyperlien sont différents (ex: [Facebook](https://google.com))
- Contrôler la légitimité du lien
    - [VirusTotal](https://virustotal.com/)
    - [urlscan.io](https://urlscan.io)
    - [any.run](https://any.run)
    - [Talos Intelligence](https://talosintelligence.com)
- Contrôler le cadenas à côté de l'URL (inutile si toutes les étapes précédentes n'ont pas été effectuées)

## Hôte (smartphone, ordinateur, ...)
- Avoir un antivirus à jour et actif
    - [Windows Defender](https://www.microsoft.com/fr-ch/windows/comprehensive-security) (largement suffisant pour la majorité des gens et gratuit)
    - ...
- Faire les mises à jour dès que possible
    - Logiciels
    - OS

## Fichier
### Exécutable
- Contrôler la source (site officiel)
- Contrôle avec antivirus
    - [VirusTotal](https://virustotal.com/)
    - [Stinger](https://www.mcafee.com/enterprise/fr-fr/downloads/free-tools/stinger.html)
    - ...
- Contrôler le comportement
    - [any.run](https://any.run)
    - [Hybrid Analysis](https://www.hybrid-analysis.com)
- Éviter les logiciels piratés

### Word/Excel/PowerPoint
- Désactiver les macros/VBA
- Contrôler la source
- Contrôle avec antivirus
    - [VirusTotal](https://virustotal.com/)
    - [Stinger](https://www.mcafee.com/enterprise/fr-fr/downloads/free-tools/stinger.html)
    - ...
- Contrôler les hyperliens et ne pas cliquer dessus sans effectuer les contrôles mentionnés dans la rubrique "Lien/URL"
- Ne pas activer les macros/VBS même si le fichier le demande
- Contrôler le comportement
    - [any.run](https://any.run/)
    - [JOEsandbox](https://www.joesandbox.com/#windows)

### PDF
- Contrôler la source
- Contrôle avec antivirus
    - [VirusTotal](https://virustotal.com/)
    - [Stinger](https://www.mcafee.com/enterprise/fr-fr/downloads/free-tools/stinger.html)
    - ...
- Contrôler les hyperliens et ne pas cliquer dessus sans effectuer les contrôles mentionnés dans la rubrique "Lien/URL"

## WiFi public
- Vérifier que le pare-feu du PC soit bien activé
- Utiliser un VPN
    - [ProtonVPN](https://protonvpn.com)
    - ...
- Limiter les accès à des sites sensibles (banque, ...)

