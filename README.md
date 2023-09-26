[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/PsEVU437)
# Comment faire? 

1. une fois vous aurez le lien github classroom, vous acceptez l'invitation
2. Après cela, actualiser la page
3. Copier l'URL que vous voyez sur la page
4. Aller sur votre vsCode puis taper cette commande git

```git clone <URL>```

# De quoi il s’agit? 
=> Il s’agit de visiter ce site https://parabank.parasoft.com/ pour effectuer certains cas de test en Cypress

Quels sont les objectifs? 
- Se familiariser certaines commandes avec Cypress
- Se familiariser avec le cas réel du test e2e
- Se familiariser avec l’outil de versioning Github

# Ennoncés de l’exercice: 
1. Visiter le site https://parabank.parasoft.com/ 
2. Vérifier si l’URL affiché dans la barre d’adresse est bien https://parabank.parasoft.com/parabank/index.htm 
3. Vérifier si le texte “Customer Login” est bien visible sur la page
4. Cliquer sur le bouton Register et vérifier si l’URL https://parabank.parasoft.com/parabank/register.htm est bien affichée sur la barre d’adresse 
5. Remplir les champs pour le signup en utilisant le “cy.type” puis cliquer le bouton REGISTER tout en bas en utilisant le “cy.clic”

# Rendu de l’exercice attendu;
Fichier cypress nommé “test.cy.js”