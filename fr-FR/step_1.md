Utilise la classe 'transparent' pour rendre un élément partiellement transparent afin de voir le contenu derrière lui.

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

<div class="transparent">
    <p>Ajoute du texte ici</p>
</div>

\--- /code ---

**Astuce :** Ajuste la valeur 'opacity' pour la classe 'transparent' dans 'style.css' : '0' est complètement transparent et '1' n'est pas du tout transparent.

## --- code ---

language: CSS
filename: style.css
line_numbers: false
--------------------------------------------------------

/\* Ajouter un effet de transparence \*/

.transparent {
opacity: 0.95;
}
\--- /code ---
