# LeadsPro - Landing Page dla Agencji Marketingowej

Landing page dla agencji marketingowej specjalizującej się w pozyskiwaniu leadów dla deweloperów budujących apartamenty w województwie pomorskim, głównie w okolicach Pucka.

## Funkcjonalności

- **Responsywny design** - strona działa na wszystkich urządzeniach (desktop, tablet, mobile)
- **Nowoczesny interfejs** - czytelny i profesjonalny design z gradientami i animacjami
- **Sekcje informacyjne:**
  - Hero z statystykami i CTA
  - Social proof (klienci)
  - Problemy klientów
  - Oferta usług
  - Korzyści ze współpracy
  - Proces współpracy
  - Referencje klientów
  - Formularz kontaktowy
- **Interaktywność:**
  - Responsywne menu mobilne
  - Płynne przewijanie (smooth scroll)
  - Animacje przy scrollowaniu
  - Walidacja formularza
  - System powiadomień
  - Animowane liczniki statystyk

## Technologie

- **HTML5** - semantyczna struktura
- **CSS3** - nowoczesne style z CSS Grid, Flexbox, animacjami
- **JavaScript (Vanilla)** - interaktywność bez dodatkowych bibliotek
- **Google Fonts** - czcionka Inter

## Struktura projektu

```
.
├── index.html      # Główny plik HTML
├── styles.css      # Style CSS
├── script.js       # JavaScript
└── README.md       # Dokumentacja
```

## Uruchomienie

Strona jest gotowa do uruchomienia - wystarczy otworzyć plik `index.html` w przeglądarce.

Dla środowiska deweloperskiego możesz użyć dowolnego serwera HTTP, np.:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve

# PHP
php -S localhost:8000
```

Następnie odwiedź `http://localhost:8000` w przeglądarce.

## Sekcje strony

1. **Nawigacja** - sticky navbar z linkami do sekcji
2. **Hero** - główny przekaz z statystykami i przyciskami CTA
3. **Social Proof** - lista zadowolonych klientów
4. **Problemy** - identyfikacja problemów grupy docelowej
5. **Oferta** - szczegółowy opis usług (Meta Ads, Google Ads, Landing Pages, etc.)
6. **Korzyści** - dlaczego warto współpracować z LeadsPro
7. **Proces** - 4 kroki do pierwszych leadów
8. **Referencje** - opinie zadowolonych klientów
9. **CTA** - sekcja z wezwaniem do działania
10. **Kontakt** - formularz kontaktowy i dane firmy
11. **Footer** - stopka z linkami i informacjami

## Customizacja

### Kolory

Główne kolory są zdefiniowane w CSS jako zmienne w `:root`:

```css
--primary-color: #2563eb;
--primary-dark: #1e40af;
--primary-light: #60a5fa;
```

### Treść

Wszystkie teksty można łatwo edytować w pliku `index.html`. Sekcje są jasno oznaczone komentarzami.

### Formularz kontaktowy

Obecnie formularz wyświetla powiadomienie o sukcesie. Aby podpiąć rzeczywisty backend, zmodyfikuj funkcję w `script.js`:

```javascript
// Contact Form Handling
contactForm.addEventListener('submit', async (e) => {
    // Tutaj dodaj kod do wysyłki na backend
    // np. fetch('/api/contact', { method: 'POST', body: formData })
});
```

## Optymalizacja

Strona jest zoptymalizowana pod kątem:
- ✅ Wydajności (brak zewnętrznych bibliotek)
- ✅ SEO (semantyczny HTML, meta tagi)
- ✅ Responsywności (mobile-first approach)
- ✅ Accessibility (aria-labels, semantic elements)

## Deploy

Strona może być wdrożona na:
- **GitHub Pages**
- **Netlify**
- **Vercel**
- **Hosting tradycyjny** (każdy serwer HTTP)

## Licencja

Projekt stworzony dla LeadsPro Agency.
