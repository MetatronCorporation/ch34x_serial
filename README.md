Чтение последовательного Type-C порта на смартфоне под управлением Андроид с выводом строки на дисплей смартфона. г. Красноярск. 
Нормер 24 сборки SDK, Андроид 7 версии. 
Проект обкатан на целевом устрйостве Xiaomi Redmi 9. Полностью исправен.

В функции onReceivedData анализ байт от 0 до  255.
По байту 0хС0 анализ наличия пакета начинающихся с байта 0xC0 и заканчивающихся байтом 0xC0.
При приеме такого пакета удалить эти байты 0хС0 из буфера. Произвести преобразование пакета байт в шестнадцатеричную строку и вывести эту строку на экран
