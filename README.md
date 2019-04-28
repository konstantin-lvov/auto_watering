# auto_watering
##Система автополива растений на плате Ардуино.
######Датчики:
- фоторезистор (датчик освещенности)
- две металлические пластины 10х50мм (датчик влажности)
- компрессор для осуществления полива
######Возможности системы:
1. Полив не включится ночью благодаря мониторингу уровня освещенности 
в течении суток
2. Реализована возможность отладки через Serial командами
	- "а" - запустить компрессор
	- "с" - очистить внутреннюю память контроллера
	- "g" - получить значения влажности и освещенности в данный момент времени
	- "р" - напечатать в Serial значения освещенности хранящиеся в памяти
3. Реализован режим максимального энергосбережения Ардуино

>В планах добавление контроля исскуственного освещения
