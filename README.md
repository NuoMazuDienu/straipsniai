# Kaip įkelti blogą

## Sukūriamas naujas failas turinys direktorijoje

Failo struktūrą turi būti HTML formatu.
Galima rašyti ir paprastą tekstą.

Apie HTML formatą galima paskaityti plačiau čia https://www.learn-html.org/en/Basic_Elements

Jeigu rašoma paprastu tekstu, galima pasitelkt kokį ChatGPT, kuris galėtų sustylint.
Turimą HTML dokumentą galima įkelti į https://jsfiddle.net/ HTML sekciją ir paspausti Run.
![image](https://github.com/user-attachments/assets/a7706e54-3ae7-4163-ad11-640d194a6bb3)


## Pridėti naujas eilutes į Straipsniai.json failą

### Naujos eilutės turi būti tokiu formatu:

```json
[
  {
    "title": "Pirmas straipsnis",
    "page": "pirmas-straipsnis",
    "category": "Mokymai",
    "imageUrl": "https://nuomazudienu.lt/assets/images/pink-nmd.jpg",
    "shortDescription": "Greitu metu įkelsime informacinius, edukacinius straipsnius.",
    "fileName": "pirmas-straipsnis",
    "date": "2025-01-25"
  }
  // Naujai sukūriamas įrašas
  {
    "title": "Naujas blogas!",
    "page": "naujas-straipsnis",
    "category": "Kategorija",
    "imageUrl": "https://example.com/image.jpg",
    "shortDescription": "This is a brief description of the article or content that gives the user an idea of what it's about.",
    "fileName": "sample-article2.html",
    "date": "2025-01-28"
  },
]
```
### Patikrinti ar formatas validus po pakeitimo galima čia https://jsonlint.com/ įkėlus visą Straipsniai.json failą



# Pavyzdys

## Sukuriu naują failą PirmasBlogas.html turinys direktorijoje

```html
<h1>Mano blogo pavadinimas!</h1>

<p>Pirmas paragrafas.</p>
<p>Antras paragrafas.</p>
<img src="https://example.com/cloud-image.jpg" alt="Nuotraukyte">
<a href="https://example.com">Taip pat čia galite pažiūrėti nuorodą</a>
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
<ul>
  <li>First bullet point</li>
  <li>Second bullet point</li>
  <li>Third bullet point</li>
</ul>
```

## Pridedu įrašą Straipsniai.json faile

(// simbolis reiškia ne struktūrą, o komentarą (iki eilutės galo))

```json
[
  {
    "title": "Pirmas straipsnis",
    "page": "pirmas-straipsnis",
    "category": "Mokymai",
    "imageUrl": "https://nuomazudienu.lt/assets/images/pink-nmd.jpg",
    "shortDescription": "Greitu metu įkelsime informacinius, edukacinius straipsnius.",
    "fileName": "pirmas-straipsnis",
    "date": "2025-01-25"
  }
  // Naujai sukūriamas įrašas
  {
    "title": "Naujas blogas!",
    "page": "naujas-straipsnis",
    "category": "Kategorija",
    "imageUrl": "https://example.com/image.jpg",
    "shortDescription": "This is a brief description of the article or content that gives the user an idea of what it's about.",
    "fileName": "sample-article2.html",
    "date": "2025-01-28"
  },
  {
    "title": "Mano blogo pavadinimas!",
    "page": "naujas-straipsnis",
    "category": "Kategorija",
    "imageUrl": "https://example.com/image.jpg",
    "shortDescription": "This is a brief description of the article or content that gives the user an idea of what it's about.",
    "fileName": "PirmasBlogas.html", //Naujai sukurto failo pavadinimas
    "date": "2025-01-28"
  },
]
```

## Patikrinu ar formatas validus po pakeitimo https://jsonlint.com/
