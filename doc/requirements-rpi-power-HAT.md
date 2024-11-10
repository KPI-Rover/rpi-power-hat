# Вимоги до друкованої плати живлення Raspberry PI

1. Плата має бути виконана у вигляді HAT (Hardware Attached on Top) модуля. Плата має відповідати усім вимогам, окрім наявності EEPROM. Вимоги: [https://github.com/raspberrypi/hats/blob/master/designguide.md](https://github.com/raspberrypi/hats/blob/master/designguide.md)
2. Плата має бути побудована на основі DC-DC перетворювача AP64500SP ([https://www.diodes.com/assets/Datasheets/AP64500.pdf](https://www.diodes.com/assets/Datasheets/AP64500.pdf))
3. Плата має забезпечити вихідну напругу 5.1 В і струм 5 А.
4. Живлення на Raspberry Pi має подаватись через 40-піновий роз'єм. Усі контакти GND мають бути об'єднані. Обидва контакти +5 В мають бути використані.
5. Плата має мати додатковий роз'єм вихідної напруги +5 В, щоб забезпечити можливість її використання окремо для живлення інших пристроїв.
6. Клемники з гвинтовими затискачами повинні використовуватися для підключення живлення і для додаткового виходу +5 В.
7. Плата має мати захист від неправильного підключення полярності джерела живлення.
8. Плата має мати додатковий захист від перевищення вихідної напруги.
9. Плата має мати роз'єм послідовного інтерфейсу на рівнях TTL. Він буде використовуватись для підключення до контролера шасі. Тип роз'єму: JST PH.
10. Плата має мати роз'єм послідовного інтерфейсу і інтерфейсу I2C для підключення GPS сенсора з компасом. Тип роз'ємів: JST PH.
11. Плата має мати світлодіод зеленого кольору, підключений до +5 В для індикації наявності живлення.
12. Друкована плата має бути розроблена з використанням KiCad EDA (https://www.kicad.org/).
13. Усі компоненти плати мають бути доступні для замовлення на сайті: https://www.lcsc.com/