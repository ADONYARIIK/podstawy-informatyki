# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus) : jest to jedna z topologii fizycznych sieci komputerowych charakteryzująca się tym, że wszystkie elementy sieci są podłączone do jednej magistrali (zazwyczaj w postaci kabla koncentrycznego).
  - Wady: 
		- Awaria w jednym miejscu może spowodować przerwanie działania całej sieci.
		- Zwiększona liczba urządzeń obniża wydajność.
  - Zalety:
		- Niska koszt instalacji, ponieważ wymaga tylko jednego przewodu.
		- Prosta w rozbudowie.
  - Gdzie stosowane: Zwykle w małych sieciach, takich jak starsze sieci Ethernet.
  
- **Topologia pierścienia** (Ring): jest to jedna z fizycznych topologii sieci komputerowych. Komputery połączone są za pomocą jednego nośnika informacji w układzie zamkniętym – okablowanie nie ma żadnych zakończeń (tworzy krąg). W ramach jednego pierścienia można stosować różnego rodzaju łącza.
  - Wady: 
		- Awaria jednego urządzenia może sparaliżować całą sieć.
		- Trudności w rozbudowie.
  - Zalety: 
		- Dobrze radzi sobie z dużymi obciążeniami i zapewnia równomierne rozłożenie danych.
		- Prosta do implementacji w małych systemach.
  - Gdzie stosowane: W sieciach MAN (Metropolitan Area Network) i niektórych sieciach LAN.
  
- **Topologia gwiazdy** (Star): jest to sposób połączenia urządzeń w sieci komputerowej charakteryzujący się tym, że kable sieciowe od wszystkich urządzeń końcowych zbiegają się w jednym wspólnym punkcie, zwanym punktem dostępu, w którym znajduje się koncentrator lub przełącznik sieciowy.
  - Wady:
		- Awaria centralnego urządzenia powoduje całkowite zablokowanie sieci.
		- Wymaga więcej kabli niż topologia magistrali.
  - Zalety: 
		- Łatwość w zarządzaniu i rozbudowie sieci.
		- Usterki są łatwiejsze do zlokalizowania i naprawienia.
  - Gdzie stosowane: W większości współczesnych sieci LAN, np. w biurach, szkołach.


## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point): jest to bezpośrednie połączenie dwóch urządzeń.
  - Wady: 
		- Ograniczona liczba urządzeń, do których można się podłączyć.
  - Zalety: 
		- Prosta konfiguracja i niski koszt utrzymania.
  - Zastosowanie: Używana w połączeniach między dwoma urządzeniami, np. łącze internetowe między routerami.
  
- **Przekazywanie żetonu** (Token Passing): jest to metoda transmisji w której dane są przekazywane w postaci "żetonu" (symbolu), który porusza się po sieci i upoważnia do wysyłania danych urządzenie, które go posiada.
  - Wady: 
		- Możliwość utraty żetonu w sieci, co może zatrzymać transmisję.
  - Zalety: 
		- Zapewnia kontrolę dostępu do medium i eliminuje kolizje.
  - Zastosowanie: Używana w sieciach, takich jak Token Ring, w których ważna jest kontrola dostępu.
  
- **Wielodostępowa** (Multiple Access): jest to metoda wielodostępu pozwalająca wielu urządzeniom na jednoczesny dostęp do tego samego medium transmisyjnego, z odpowiednimi protokołami, które zarządzają dostępem do medium.
  - Wady: 
		- Możliwość wystąpienia kolizji, które mogą obniżyć wydajność.
  - Zalety: 
		- Pozwala na efektywne dzielenie zasobów między wiele urządzeń.
  - Zastosowanie: Wykorzystywana w sieciach Ethernet (z protokołem CSMA/CD) i w Wi-Fi.