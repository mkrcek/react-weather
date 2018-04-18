# react-weather

- testování Reaktu pro různá prostředí
- formulář
- API google mapy
- API openweathermap.org

## jak na to

1. nahrát obsah do web server
- index.html
- bundle.js
- adresář /style

- Screen-Shot.png (...je jen ilustrační screenshot)


2. spustit index.html na lokálním web serveru

3. zobrazit localhost:8080 (v případě Go Web Serveru)


## ovládání aplikace

- do políčka zadat větší české město
- funguje na Praha, Brno, Vyškov, ...
- zobrazí se mapa z GoogleMaps a předpověď na 5 dní dopředu (teplota, tlak, vlhkost) z openweathermap.org
- když se napíše město, které není v databázi - nastane chyba a je nutné udělat refresh obrazovky (chyba není ošetřena)
