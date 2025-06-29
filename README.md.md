# IN CATERING - Onboarding aplikace

Interaktivní onboarding aplikace pro nové zaměstnance IN CATERING Group na pozici Event/Catering Manager.

## 🚀 Živá verze
[https://[váš-username].github.io/incatering-onboarding/](https://[váš-username].github.io/incatering-onboarding/)

## 📋 O aplikaci

Tato webová aplikace provede nové zaměstnance kompletním onboarding procesem a představí:
- Firemní hodnoty a kulturu
- Informace o společnosti a její historii
- Popis pracovní pozice Event/Catering Manager
- Přehled všech provozoven
- Zaměstnanecké benefity
- Důležité kontakty
- Potřebné dokumenty

## ✨ Funkce

- **11 interaktivních obrazovek** pokrývajících celý onboarding proces
- **Progress tracking** s vizuálním ukazatelem postupu
- **Responzivní design** - funguje na všech zařízeních
- **Automatické ukládání** postupu do LocalStorage
- **Podpora dotykových gest** pro mobilní zařízení
- **Klávesové zkratky** (šipky pro navigaci)
- **Interaktivní checklist** pro první den
- **Animace a přechody** pro lepší UX

## 🛠️ Technologie

- HTML5
- CSS3 (s custom properties)
- Vanilla JavaScript
- LocalStorage API
- Responzivní design (mobile-first)

## 📁 Struktura projektu

```
incatering-onboarding/
├── index.html          # Hlavní aplikace (vše v jednom souboru)
├── README.md           # Tento soubor
├── .gitignore         # Git ignorované soubory
└── assets/            # (volitelné)
    ├── logo.png       # Logo společnosti
    └── documents/     # PDF dokumenty pro ke stažení
```

## 🔧 Instalace a spuštění

### Lokální spuštění
1. Stáhněte nebo naklonujte repozitář
2. Otevřete `index.html` v prohlížeči

### Nasazení na GitHub Pages
1. Vytvořte nový repozitář na GitHubu
2. Nahrajte soubory
3. V Settings → Pages aktivujte GitHub Pages
4. Vyberte branch `main` a složku `/ (root)`
5. Počkejte 2-10 minut na deployment

## 📝 Úpravy a customizace

### Změna firemních barev
V souboru `index.html` najděte CSS sekci a upravte:
```css
:root {
    --primary-red: #E31E24;  /* Hlavní firemní barva */
    --dark-gray: #333333;
    --light-gray: #f5f5f5;
}
```

### Přidání dokumentů
1. Vytvořte složku `documents`
2. Nahrajte PDF soubory
3. V sekci Screen 10 upravte odkazy:
```javascript
onclick="window.open('documents/pracovni-rad.pdf', '_blank')"
```

### Úprava kontaktů
V sekci Screen 8 upravte kontaktní údaje:
```html
<p class="contact-info">📧 <a href="mailto:hr@incatering.cz">hr@incatering.cz</a></p>
<p class="contact-info">📱 <a href="tel:+420123456789">+420 123 456 789</a></p>
```

### Personalizace pro zaměstnance
Aplikaci lze spustit s parametry:
```
https://example.com/index.html?name=Jan&position=Event%20Manager
```

## 🎯 Použití

1. **Nový zaměstnanec** obdrží odkaz na aplikaci
2. **Projde všech 11 obrazovek** v vlastním tempu
3. **Může se kdykoliv vrátit** - aplikace si pamatuje postup
4. **Na konci získá** přehled všech důležitých informací

## 🔒 Bezpečnost

- Aplikace neobsahuje žádné citlivé údaje
- Všechna data jsou uložena pouze lokálně v prohlížeči
- Pro interní dokumenty doporučujeme použít zabezpečený intranet

## 📱 Podpora prohlížečů

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- Mobilní prohlížeče (iOS Safari, Chrome Android)

## 🤝 Kontakt

**IN CATERING s.r.o.**
- Web: [www.incatering.cz](https://www.incatering.cz)
- Email: hr@incatering.cz
- Tel: +420 220 560 494
- Adresa: Libocká 10/64, 162 00 Praha 6

## 📄 Licence

© 2024 IN CATERING s.r.o. Všechna práva vyhrazena.

## 🙏 Poděkování

Děkujeme všem členům týmu, kteří přispěli k vytvoření této aplikace a poskytli cenné podklady a zpětnou vazbu.

---

*Vytváříme zážitky a chutě, na které se nezapomíná!* 🍽️