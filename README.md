# 🚗 Kalkulator Importu PRO

Profesjonalne narzędzie do analizy kosztów importu pojazdów z UE.

## 🎯 Funkcje

### 🧮 Prosty Kalkulator
- Szybkie obliczenia bez API
- Ręczne wprowadzanie danych
- Natychmiastowe wyniki

### 🤖 Analiza AI
- Automatyczne rozpoznawanie z AUTO1.com
- Upload wielu zdjęć (telefon lub desktop)
- Pełna analiza rynku
- Strategia sprzedaży
- Szacowanie ceny i marży

## 📦 Instalacja na GitHub Pages

### Krok 1: Utwórz nowe repozytorium
1. Wejdź na https://github.com
2. Kliknij **"New"** (zielony przycisk)
3. Nazwa: `kalkulator-importu` (lub dowolna)
4. Zaznacz: **☑ Public**
5. Kliknij **"Create repository"**

### Krok 2: Wgraj plik
1. Kliknij **"uploading an existing file"**
2. Przeciągnij plik **`index.html`**
3. Kliknij **"Commit changes"**

### Krok 3: Włącz GitHub Pages
1. Kliknij **"Settings"** (górny pasek)
2. Z lewego menu wybierz **"Pages"**
3. W sekcji **"Source"**:
   - Branch: **`main`**
   - Folder: **`/ (root)`**
4. Kliknij **"Save"**
5. Poczekaj 1-2 minuty

### Krok 4: Gotowe! 🎉
Twoja aplikacja będzie dostępna pod:
```
https://twoja-nazwa.github.io/kalkulator-importu/
```

## 🔑 Konfiguracja

### Klucz API OpenAI
Aby używać trybu **Analiza AI**, potrzebujesz klucza API:

1. Wejdź na https://platform.openai.com/api-keys
2. Zaloguj się lub załóż konto
3. Kliknij **"Create new secret key"**
4. Skopiuj klucz (zaczyna się od `sk-proj-...`)
5. Wklej w aplikacji w pole "Klucz API OpenAI"

**Klucz zapisuje się lokalnie w przeglądarce - jest bezpieczny.**

## 📱 Instalacja na telefonie (iOS)

1. Otwórz aplikację w **Safari** (nie Chrome!)
2. Kliknij przycisk **Udostępnij** ⬆️ (na dole)
3. Przewiń w dół i wybierz **"Dodaj do ekranu początkowego"**
4. Nazwij: **"Import Pro"**
5. Kliknij **"Dodaj"**

Gotowe! Ikona pojawi się na ekranie głównym.

## 🎮 Jak używać

### Tryb: Prosty Kalkulator
1. Wybierz zakładkę **"🧮 Prosty Kalkulator"**
2. Wpisz dane pojazdu
3. Kliknij **"Oblicz koszty"**
4. Zobacz wyniki

### Tryb: Analiza AI
1. Wybierz zakładkę **"🤖 Analiza AI"**
2. Wpisz klucz API OpenAI (tylko raz)
3. Dodaj zdjęcia z AUTO1.com:
   - **Telefon**: 2-5 screenów
   - **Desktop**: 1 screenshot
4. Kliknij **"Analizuj pojazd (AI)"**
5. Poczekaj 10-15 sekund
6. Zobacz pełną analizę:
   - Koszty importu
   - Dane pojazdu
   - Szacowana cena sprzedaży
   - Potencjalny zysk
   - Plusy i minusy
   - Strategia sprzedaży

## 💡 Wskazówki

### Najlepsze wyniki z AI:
- **Telefon**: Zrób 3-4 screeny (cena, dane techniczne, transport, zdjęcia)
- **Desktop**: Jeden pełny screenshot ze wszystkimi danymi
- Upewnij się, że widoczne są: model, rok, przebieg, silnik, cena, transport

### Analiza uwzględnia:
- ✅ Wersję wyposażenia (Comfortline, Highline, etc.)
- ✅ Polski rynek (Otomoto, OLX)
- ✅ Typowe problemy modelu
- ✅ Popularność i rotację
- ✅ Docelowego kupującego

## 🔧 Koszty obliczane automatycznie

- **Kurs EUR/PLN**: 4.22 (AUTO1 standard)
- **Akcyza**: 
  - 3.1% dla silników ≤ 1999 ccm
  - 18.5% dla silników > 1999 ccm
- **Dokumenty**: według kraju (DE: 448 EUR, IT: 628 EUR, etc.)
- **Dodatkowe koszty**: 660 PLN (przegląd, ubezpieczenie, rejestracja, etc.)

## 📊 Przykład użycia

```
Volkswagen Polo 1.4 FSI Comfortline (2009)
├─ Cena: 1 611 EUR
├─ Transport: 454 EUR (najtańszy)
├─ Przebieg: 224 328 km
└─ Silnik: 1 390 ccm

💰 KOSZTY IMPORTU: ~11 500 PLN
📈 SZACOWANA SPRZEDAŻ: 12 500 PLN
💵 ZYSK: ~1 000 PLN (9%)
⏱️ ROTACJA: Średnia (1-2 miesiące)
```

## ❓ Rozwiązywanie problemów

**Problem**: Nie działa przełączanie trybów
- Odśwież stronę (F5)
- Wyczyść cache przeglądarki

**Problem**: AI nie rozpoznaje danych
- Sprawdź jakość zdjęć
- Dodaj więcej screenów z różnymi danymi
- Upewnij się, że tekst jest czytelny

**Problem**: Błąd API
- Sprawdź klucz API (czy poprawnie skopiowany)
- Sprawdź saldo na koncie OpenAI
- Poczekaj chwilę i spróbuj ponownie

## 📞 Wsparcie

Masz pytania lub sugestie? Otwórz **Issue** na GitHubie!

## 📄 Licencja

MIT License - wolne do użytku osobistego i komercyjnego.

---

**Wersja**: 1.0 PRO  
**Data**: 2026-01-28  
**Autor**: Twoje dane

🚗 Udanych importów! 💰
