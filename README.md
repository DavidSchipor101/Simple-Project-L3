# Simple Webpage

O pagină web simplă, realizată cu HTML5 și CSS3, cu un design modern și adaptabil la diferite dimensiuni de ecran.

## Caracteristici

- Structură semantică HTML5.
- Secțiuni pentru Home, About, Contact și Galerie.
- Galerie foto cu trei imagini placeholder.
- Galerie realizată cu CSS Grid, cu trei coloane pe ecrane mari.
- Pe ecrane cu lățimea de cel mult 600 px, galeria se afișează pe o singură coloană.
- Spațiu de `1rem` între imaginile din galerie.

## Structura proiectului

```text
proiect/
├── index.html
├── styles.css
└── README.md
@media (max-width: 600px) {
    #galerie .galerie-grid {
        grid-template-columns: 1fr;
    }
}