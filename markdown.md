# Markdown CheatSheet

=======

## Images

Pour ajouter une image, il faut ajouter un point d'exclamation ( ! ), suivi du text alternatif entre crochets, ainsi que le chemin ou URL de l'image entre parenthèses. Un titre peut être ajouté entre guillemets après l'URL dans les parenthèses.

```
![The Shining, a Stanley Kubrick film](/assets/images/shining.gif "The Shining")
```

Voici le résultat:

![The Shining, a Stanley Kubrick film](/assets/images/shining.gif "The Shining")

## Liens imagés

Pour ajouter un lien à une image, englobez le Markdown de l'image dans des crochets, ensuite ajoutez le lien entre parenthèses.

```
[![How to be an unicorn](/assets/images/unicorn.gif "How to be an unicorn")](https://lmgtfy.com/?q=How+to+be+a+unicorn)
```

Voici le résultat:

[![How to be an unicorn](/assets/images/unicorn.gif "How to be an unicorn")](https://lmgtfy.com/?q=How+to+be+a+unicorn)

## Caractères d'échappement

Pour afficher un caractère qui est normalement utilisé pour formatter du texte dans un fichier Markdown, ajoutez un backslash ( \\ ) avant celui-ci.

```
\* Sans le backslash, ceci est un élément d'une liste non-ordonnée
```

Voici le résultat:

\* Sans le backslash, ceci est un élément d'une liste non-ordonnée

## Liste des caractères échappables

Vous pouvez utiliser le backslash ( \\ ) pour échapper les caractères suivants.

| Caractère | Nom                 |
| :-------: | :------------------ |
|    \\     | backslash           |
|    \`     | backtick            |
|    \*     | astérisque          |
|    \_     | underscore          |
|    \{}    | accolades           |
|    \[]    | crochets            |
|    \()    | parenthèses         |
|    \#     | dièse               |
|    \+     | signe plus          |
|    \-     | signe moins         |
|    \.     | point               |
|    \!     | point d'exclamation |
|    \|     | pipe                |
