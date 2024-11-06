# WeatherApp
Simple Python weather app with GUI using PyQt5 and OpenWeatherMap API

## Opis Projektu

Weather App to aplikacja graficzna stworzona w Pythonie, która umożliwia użytkownikom sprawdzanie aktualnej pogody w dowolnym mieście. Użytkownik wprowadza nazwę miasta, a aplikacja wyświetla temperaturę, opis pogody oraz ikonę odpowiadającą aktualnym warunkom atmosferycznym. Dane są pobierane za pomocą API OpenWeatherMap.

## Technologie

- **Python** – główny język programowania
- **PyQt5** – używany do budowy graficznego interfejsu użytkownika (GUI)
- **requests** – do wykonywania zapytań HTTP i komunikacji z API OpenWeatherMap
- **OpenWeatherMap API** – źródło danych pogodowych

## Funkcje

- Wprowadzanie nazwy miasta i uzyskanie prognozy pogody.
- Wyświetlanie temperatury w stopniach Celsjusza, opisu pogody i ikony.
- Obsługa różnych błędów, takich jak niepoprawna nazwa miasta, problemy z połączeniem, błędy serwera itp.

## Instrukcja Instalacji

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/twoj-uzytkownik/weather-app.git
   cd weather-app

2.Zainstaluj wymagane biblioteki:

  pip install -r requirements.txt

3.Uzyskaj klucz API z OpenWeatherMap (https://openweathermap.org/) i dodaj go do kodu projektu w miejscu api_key.

4.Uruchom aplikację:
python main.py



Przykład Użycia:
-Wprowadź nazwę miasta w polu tekstowym.
-Kliknij przycisk "Get Weather", aby uzyskać prognozę pogody.

Autor
Projekt stworzony przez JC.
