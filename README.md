# Arkanoid
# Для сдачи выбраны пункты 1-4:
1)	Неразрушаемые. От них мяч просто отскакивает.
2)	Блоки могут быть со спрятанными бонусами: при попадании вертикально вниз падает бонус
3)	Блоки, увеличивающие скорость шарика при столкновении
4)	Блоки имеют уровень здоровья = число попаданий, чтобы блок исчез. За каждое попадание +1 очко игроку, -1 очко здоровья блоку.
# А также дополнительные 6,7
6)	Бонус: появляется двигающий блок, не задевающий при движении остальные блоки (надо проверять коллизии), и живущий до 3 ударов
7)	Бонус: появляется второй шарик, способный оттолкнуться и от первого, и от блоков/стенок

# Комментарий: 
Присутствуют все обязательные коллизии:
1) Ракетка - шарики
2) шарик - блоки
3) блок- двигающийся блок
4) двигающийся блок - двигающийся блок
5) шарик - шарик
