# 🚀 Live Betting Analyzer - Gotowy do Deployment

## 📦 Zawartość Pakietu

Ten pakiet zawiera wszystkie pliki potrzebne do uruchomienia systemu analizy live betting na Vercel.

## 📁 Struktura Projektu

Po rozpakowaniu stwórz następującą strukturę:

```
live-betting-vercel/
├── api/
│   └── analyze.py         (skopiuj plik analyze.py tutaj)
├── public/
│   └── index.html         (skopiuj plik index.html tutaj)
├── requirements.txt       (skopiuj do głównego folderu)
└── vercel.json           (skopiuj do głównego folderu)
```

## 🚀 Quick Start

### Opcja 1: GitHub + Vercel (zalecane)

1. Stwórz strukturę folderów jak powyżej
2. Stwórz nowe repozytorium na GitHub
3. Przeciągnij cały folder `live-betting-vercel` do GitHub (drag & drop)
4. Idź na vercel.com
5. Kliknij "New Project" → Import z GitHub
6. Deploy! 🎉

### Opcja 2: Vercel CLI

1. Stwórz strukturę folderów jak powyżej
2. Otwórz terminal w folderze głównym
3. Wykonaj:
```bash
npm install -g vercel
vercel login
vercel
```

### Opcja 3: GitHub Desktop

1. Stwórz strukturę folderów jak powyżej
2. Otwórz GitHub Desktop
3. File → Add Local Repository → wybierz folder
4. Publish repository
5. Połącz z Vercel

## ⚙️ Konfiguracja (opcjonalna)

### Zmiana klucza API

Jeśli chcesz użyć własnego klucza API-Football:

1. Edytuj `api/analyze.py`
2. Znajdź linię: `API_KEY = "ac0417c6e0dcfa236b146b9585892c9a"`
3. Zamień na swój klucz

### Zmiana limitów analizy

W `api/analyze.py` znajdź:
```python
for match in matches[:5]:  # Analizuje pierwsze 5 meczów
```

Zmień `[:5]` na np. `[:10]` aby analizować więcej meczów.

## 🧪 Testowanie

Po deployment:

1. Otwórz: `https://twoj-projekt.vercel.app`
2. Kliknij "Analizuj Mecze Live"
3. System powinien pokazać wyniki

**Najlepsze godziny testowania:**
- Weekendy: 15:00-22:00 CEST (najwięcej meczów)
- Dni powszednie: 18:00-22:00 CEST
- Wtorki/Środy: Liga Mistrzów
- Czwartki: Liga Europy

## 📊 Co System Robi

1. Łączy się z API-Football
2. Pobiera mecze live
3. Analizuje statystyki (xG, momentum)
4. Generuje sygnały typowania
5. Wyświetla wyniki w ładnym interfejsie

## 💰 Koszty

**CAŁKOWICIE DARMOWE!**

Vercel Free Tier obejmuje:
- 100GB bandwidth/miesiąc
- Unlimited requests
- Automatic SSL
- Custom domains

## ⚠️ Limity API-Football

Free tier:
- 100 requests/dzień
- 1 analiza ≈ 6 requests
- ~15-20 analiz dziennie możliwe

## 🐛 Troubleshooting

**Błąd "No matches found":**
- Normalne jeśli nie ma meczów live
- Spróbuj w godzinach wieczornych

**Błąd "API error":**
- Sprawdź klucz API
- Sprawdź limity requestów

**Błąd "Timeout":**
- API-Football może być wolne
- Spróbuj ponownie za chwilę

## 📚 Dokumentacja

- Vercel: https://vercel.com/docs
- API-Football: https://www.api-football.com/documentation-v3

## 💬 Support

Jeśli masz problemy:
1. Sprawdź logi w Vercel Dashboard
2. Upewnij się że struktura folderów jest poprawna
3. Sprawdź czy wszystkie pliki są w odpowiednich miejscach

## 🎉 To wszystko!

System jest gotowy do użycia. Deploy i ciesz się analizą live betting! 🚀⚽💰
