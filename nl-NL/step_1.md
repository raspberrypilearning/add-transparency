Gebruik de `transparant` klasse om een element gedeeltelijk transparant te maken, zodat je de inhoud erachter kunt zien.

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="transparent">
    <p>Voeg hier tekst toe</p>
</div>

--- /code ---

**Tip:** Pas de `opacity` waarde aan voor de `transparent` klasse in `style.css`: `0` is volledig transparant en `1` is helemaal niet transparant.

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---
/* Voeg een transparantie-effect toe */

.transparent {
  opacity: 0.95;
}
--- /code ---
