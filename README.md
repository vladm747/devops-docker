Moroz Vladyslav IS-03

http://localhost:49160/

port 80


docker build . -t charlie02/node-web-app     створення білду імейджа

docker run -m 100m --cpus="2" -p 49160:80 -d charlie02/node-web-app запуск імейджа  з обмеженнями у пам'яті та використанні процесора

пуш на докерхаб та запуск сервера відбувався з додатку docker desktop)

have a nice day <3