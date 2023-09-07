# MexcSpot
trading bot for exchange MEXC 


Бот для спот торговли на криптобирже MEXC (аналог BinSpot-17).

Запуск бота на VPS с ubuntu
1. Подключаемся к серверу и по умолчанию находимся в корневом каталоге.
2. Создаем новую папку (например, с именем MexcSpot) командой:  
mkdir MexcSpot
3. Создаём новую screen-сессию (назовем, например, тоже MexcSpot) для  бота командой:  
screen -S MexcSpot
4. Заходим в папку MexcSpot командой:  
cd MexcSpot
5. Скачиваем бота в папку ebot командой:  
wget https://github.com/ebot732/MexcSpot/releases/download/MexcSpot-17/MexcSpot-17
6. Даём права на запуск бота командой:  
chmod 755 MexcSpot-17
7. Запускаем  бота командой:  
./MexcSpot-17  
и следуем подсказкам.
8. Выходим из работающего screen, не прерывая его работу, командой:  
ctrl+a, d (при нажатой ctrl жмем а, отпускаем их, и затем жмем d)

Далее, чтобы зайти в screen работающего бота, введите команду:  
screen -x MexcSpot  
То есть, второй раз вводить  
screen -S MexcSpot  
не нужно, а то создастся еще одна screen-сессия.
