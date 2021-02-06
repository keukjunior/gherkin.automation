# Gherkin

## Discord

FEATURE: Utilisez Discord pour envoyer un nouveau message

SCENARIO: Se connecter sur Discord  
GIVEN j’ouvre mon navigateur connecter sur la page web de Discord  
AND j’appuie sur entrer pour lancer la connexion au site web  
WHEN je vérifie si c’est bien la page web de Discord en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND je valide mon identité avec le bouton CAPTCHA  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Discord  

SCENARIO: Envoyer un message à mon ami  
GIVEN j’ouvre mon navigateur connecter sur la page web de Discord  
AND j’appuie sur entrer pour lancer la connexion au site web  
THEN je vérifie si c’est bien la page web de Discord en inspectant l’adresse de l’url  
WHEN j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND je valide mon identité avec le bouton CAPTCHA  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Discord  
WHEN je sélectionne "Samba" la personne que je veux envoyer un message sur ma liste d'amis  
AND j'écris mon message  
AND j'appuie sur le bouton "Envoyer"  
THEN je vois que mon message est livré  

SCENARIO: Déconnexion de Discord  
GIVEN je suis sur ma page d'accueil Discord  
AND j'appuie sur le bouton "Déconnexion"  
and j’appuie sur confirmer  
THEN je vois que je suis déconnecté de Discord  

## Notion

FEATURE: Utiliser Notion pour ajouter un nouveau note et le partager

SCENARIO: Se connecter sur Notion  
GIVEN j’ouvre mon navigateur connecter sur la page web de Notion  
AND j’appuie sur entrer pour lancer la connexion au site web  
THEN je vérifie si c’est bien la page web de Notion en inspectant l’adresse de l’url  
WHEN j'appuie sur le bouton "Login"  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j'appuie sur "Continue withe email"  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Continue with email"  
THEN j'ai accés à ma page d'accueil Notion  

SCENARIO: Ajouté un nouveau note  
GIVEN j’ouvre mon navigateur connecter sur la page web de Notion  
AND j’appuie sur entrer pour lancer la connexion au site web  
THEN je vérifie si c’est bien la page web de Notion en inspectant l’adresse de l’url  
WHEN j'appuie sur le bouton "Login"  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j'appuie sur "Continue withe email"  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Continue with email"  
THEN j'ai accés à ma page d'accueil Notion  
WHEN j'appuie sur le bouton "New note"  
And je rajoute "Mon note" dans le champ nom  
AND je rajoute le "contenu" dans le champ note  
AND j'appuie sur le bouton "Save"  
THEN mon note a été ajouté sur la liste  

SCENARIO: Partagé mon note  
GIVEN j’ouvre mon navigateur connecter sur la page web de Notion  
AND j’appuie sur entrer pour lancer la connexion au site web  
THEN je vérifie si c’est bien la page web de Notion en inspectant l’adresse de l’url  
WHEN j'appuie sur le bouton "Login"  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j'appuie sur "Continue withe email"  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Continue with email"  
THEN j'ai accés à ma page d'accueil Notion  
WHEN je sélectionne "Mon note" sur la liste des notes  
AND j'appuie sur le bouton "Share"  
AND j'ajoute "samba2020@gmal.com" dans le champ email  
AND j'appuie sur le bouton "Send"  
THEN mon note a été partagé  
