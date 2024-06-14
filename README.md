## Dateien Struktur

- Dateien die ähnliche Funktionalität / Ziel haben, werden zusammengelegt
- Oft sind dabei
  - src (Source) : wo es entwickelt ist
  - dist : wo es geliefert ist, was entwickelt wurde
  - public : wo fonts, icons & co gespeichert sind

## SASS | SCSS : Welche Dateien / Ordner sollten dabei sein

### Utils

- utils
- reset
- root
- colors
- typography

h1 {
font-size : 5rem;
text-align : center;
}

- mixins

_in der Regel overkill_

- animations
- transition
  $transition: 300ms;
- borderRadius
  $borderRadius : 4px;

### Components

- components
- header (manchmal auf einen Ordner _Layout_)
- footer (manchmal auf einen Ordner _Layout_)
- main (manchmal auf einen Ordner _Layout_)
- image
- nav
- productCard
- contactForm
- hero
- button
- buttonGroup
- accordion
- modal
- CTA Call To Action

### Pages

- pages
- homePage

h1 {
text-align : left;
}

- contactPage
- blogPage
- singlePostPage
- productPage
- aboutUsPage