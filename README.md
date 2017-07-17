# Training HTML/CSS

## 1. Fichiers

**HTML/.html** : (HyperText Markup Language) Contient toute la structure et le contenu

**CSS/.css** : (Cascading Style Sheets) Contient tout le code "cosmétique"


## 2. Editeur

* Notepad++
* Sublime Text
* IntelliJ
* **VSCode**
* WebStorm
* ...


## 3. Structure d'une page HTML5

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8" />
            <title>Titre</title>
        </head>

        <body>
        
        </body>
    </html>

Une balise est toujours composée d'une partie "ouvrante" et une partie fermante. C'est entre ces deux parties qu'on place d'autres balises "enfants".

**html** : Balise principale du code. Elle inclut TOUT le contenu de la page (hormis la doctype).

**head** : Balise contenant toutes les informations générales sur la page. Comme son titre, son encodage, l'import de sources externes, etc.

**body** : Balise contenant la partie principale de la page. Contient toute la partie directement visible du site.


## 4. Les commentaires
    <!-- Ceci est un commentaire -->


## 5. Apprendre à inspecter le code

Tout le contenu HTML et CSS de n'importe quel site web est entièrement visible par n'importe qui. 

Pour cela il suffit d'"inspecter" le code avec un browser. Au hasard... Chrome :) 

Shortcut : F12 > Html


## 6. Balises principales

* div : block/section
* span : group inline
* p : paragraphe
* h1,h2,h3,h4,h5,h6 : titres
* ul > li : liste non ordonnée
* ol > li : liste ordonné


## 7. Balises secondaires (souvent remplacées par du CSS)
* em : italique
* strong : gras
* mark : surligner


## 8. Attributs principaux

* id
* class


## 9. Liens

### Types de liens

Vers un autre site :

    <a href="https://monsite.com">Mon Site</a>

Vers une autre page du même site : 

    <a href="page2.html"> (même dossier)
    <a href="../page2.html"> (dossier parent)
    <a href="contenu/page2.html"> (sous-dossier)

Vers une partie de la page (ancre)

    <h2 id="mon_ancre">Titre</h2>

    <a href="#mon_ancre">Aller vers l'ancre</a>

### Attributs

* title 
* target 


## 10. Images

### Formats

* jpg : photos
* png : graphiques et besoin de transparence
* gif : animations mais c'est tellement has been ... :p


### Balise

    <img src="images/ma_photo.jpg" alt="Ma photo" />


### Figure

    <figure>
        <img src="images/ma_photo.jpg" alt="Ma photo" />
        <figcaption>Voici ma photo</figcaption>
    </figure>