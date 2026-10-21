# Identité visuelle

## Palette de couleurs

| Aperçu | Nom suggéré | Hex | RGB |
|---|---|---|---|
| 🟧 | Orange (couleur principale) | `#e89a13` | 232, 154, 19 |
| ⬜ | Crème (fond) | `#fff7e9` | 255, 247, 233 |
| 🟫 | Brun (texte, titres) | `#744b00` | 116, 75, 0 |
| 🟨 | Jaune (accent) | `#ffd146` | 255, 209, 70 |

> Les noms et rôles sont des suggestions déduites de la planche : le brun `#744b00` est utilisé pour tous les textes de la planche typographique.

### Variables CSS

```css
:root {
  --color-orange: #e89a13;
  --color-cream:  #fff7e9;
  --color-brown:  #744b00;
  --color-yellow: #ffd146;
}
```

---

## Typographie

### Chantal — titres / display

Police manuscrite, en capitales, au style dessiné à la main. À réserver aux titres et éléments d'accroche.

- **Graisses :** Regular, Bold
- **Couleur d'usage :** Brun `#744b00`

Spécimen : `Aa Bb Cc Dd Ee Ff Gg Hh Ii Jj Kk Ll Mm Nn Oo Pp Qq Rr Ss Tt Uu Vv Ww Xx Yy Zz 1234567890 &`

### Nunito — texte courant

Police sans-serif arrondie, lisible, pour les paragraphes, sous-titres et contenus.

- **Graisses :** Regular, Bold
- **Couleur d'usage :** Brun `#744b00`
- **Disponibilité :** Google Fonts

Spécimen : `Aa Bb Cc Dd Ee Ff Gg Hh Ii Jj Kk Ll Mm Nn Oo Pp Qq Rr Ss Tt Uu Vv Ww Xx Yy Zz 1234567890 &`

### Variables CSS

```css
:root {
  --font-display: "Chantal", "Comic Neue", cursive;
  --font-body:    "Nunito", system-ui, sans-serif;
}
```

---

## Récapitulatif

| Élément | Police | Graisse | Couleur |
|---|---|---|---|
| Titre principal | Chantal | Bold | `#744b00` |
| Sous-titre | Chantal | Regular | `#744b00` |
| Texte courant | Nunito | Regular | `#744b00` |
| Texte mis en avant | Nunito | Bold | `#744b00` |
| Fond | — | — | `#fff7e9` |
| Accents / boutons | — | — | `#e89a13` / `#ffd146` |
