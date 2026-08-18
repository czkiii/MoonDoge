MOON DOGE — LAUNCH / SETTINGS STRUCTURE FIX

Javítva:
- Settings event listenerek már nem a Settings click handlerén belül vannak
- LAUNCH nem vár a gyro permission befejezésére
- a játék azonnal elindul a gombnyomásra
- gyro permission ugyanabból a user gesture-ből indul, de nem tudja blokkolni a játékot
- dupla touchend/click indítás megszüntetve
- starting guard megakadályozza a dupla launchot
- teljes JavaScript Node syntax checkkel ellenőrizve
- service worker cache frissítve

Az alap fájlnevek változatlanok.
