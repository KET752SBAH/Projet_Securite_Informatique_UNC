# ROUTERSPLOIT
![logo](/images/routersploit/routersploit.png)
RouterSploit est un framework open-source dédié à l'exploitation de vulnérabilités dans les routeurs et les dispositifs embarqués. Il est conçu pour simplifier le processus d'exploitation des failles de sécurité présentes dans les équipements réseau. RouterSploit est écrit en Python et propose une interface en ligne de commande.

### Voici quelques-unes des fonctionnalités courantes de RouterSploit :
1. **Scanning des vulnérabilités :** RouterSploit peut scanner les réseaux pour détecter les dispositifs actifs et identifier les vulnérabilités potentielles.
2. **Exploitation des vulnérabilités :** Une fois les vulnérabilités détectées, RouterSploit permet d'exploiter ces failles pour accéder à des fonctionnalités non autorisées, contourner les mesures de sécurité, ou prendre le contrôle du dispositif cible.
3. **Attaques par force brute :** Le framework peut également être utilisé pour mener des attaques par force brute, notamment des attaques de mots de passe, afin de compromettre les dispositifs qui utilisent des identifiants faibles.
4. **Injection de payloads :** RouterSploit prend en charge l'injection de payloads, qui sont des morceaux de code malveillant, pour exécuter des actions spécifiques sur le dispositif cible.

## Installation sur Kali 
Pour l'installer cliquez [ici](https://github.com/threat9/routersploit) ou suivez les étapes:
```
install python3-pip
git clone https://www.github.com/threat9/routersploit
cd routersploit
python3 -m pip install -r requirements.txt
python3 rsf.py
```
![](/images/routersploit/1.png)

## Demo sur Tryhackme 
Nous allons faire une attaque par brute force voici le lien de la room ([https://tryhackme.com/room/hydra
](https://tryhackme.com/room/hydra)).
 Imaginez que vous essayiez de deviner manuellement le mot de passe de quelqu’un sur un service particulier (SSH, Web Application Form, FTP ou SNMP) - nous pouvons utiliser *routersploit* de parcourir une liste de mots de passe ou d'utilisateur et d’accélérer ce processus pour nous, déterminer le mot de passe correct.

### Etape 1:
![](/images/routersploit/1.png)

### Etape 2:
![](/images/routersploit/2.png)

### Etape 3:
![](/images/routersploit/3.png)

### Etape 4:
![](/images/routersploit/4.png)

