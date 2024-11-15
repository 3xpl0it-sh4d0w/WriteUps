# 02 - BINGO

### ENONCE :

> Quel est le **montant en euros** du **contrat signé en mars 2024 par Aeroguard** ?

### FORMAT DU FLAG : `72 000 000` 

### INVESTIGATION :

1. Alors nous devons partir des éléments du challenge précédent ([La Mission](./../01_La_Mission/)).
2. En consultant le **[PDF CONTEXTE](./../01_La_Mission/src/documents/CONTEXTE.pdf)**, notons que le nom complet de la structure est : **Aeroguard Technologies**.
3. Donc nous faisons la recherche **GDorks** : [`"aeroguard technologies"`](https://google.com/search?q=%22aeroguard+technologies%22)
4. Nous trouvons un site dont l'URL est la suivante : https://aeroguard-technologies.eu/
5. Nous y trouvons une section **"news"** dans le header.
6. En cliquant dessus nous pouvons observer un **article datant du 13 Mars 2024**
    - **TITRE :** `Aeroguard Technologies conclut un important contrat d'exportation en Asie`
    - **CONTENU**
      > **Aeroguard Technologies** a annoncé aujourd'hui la **signature d'un contrat de vente stratégique** avec un **partenaire gouvernemental en Asie** pour la **fourniture de systèmes de défense anti-drones**.  

      > **Ce contrat, d'une valeur de 20 millions d'euros**, marque la **première entrée de l'entreprise sur le marché asiatique** et renforce sa position en tant qu'**acteur clé dans la protection des espaces aériens à l'international**
    
      > "Nous sommes ravis de cette opportunité de travailler avec un nouveau partenaire en Asie", a déclaré **Franck DEPARSON, fondateur et CEO d'Aeroguard Technologies**. "Cela confirme la **qualité de nos technologies** et notre capacité à **répondre aux besoins de sécurité des espaces aériens dans le monde entier**."

7. Donc, le montant en euros du contrat est de **20 Millions d'Euros.**

### FLAG VALIDE : `20 000 000`