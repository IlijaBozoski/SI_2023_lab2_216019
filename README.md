# SI_2023_lab2_216019 
Илија Бозоски 216019 
1.Done

2.![grafIlija](https://github.com/IlijaBozoski/SI_2023_lab2_216019/assets/127144144/382ad1b4-d0ca-4abf-bc39-c7901bbd92fc)

Забелешка:Графот ги има сите јазли односно и оние кои се последователни и секако се случуваат еден по друг(пример 5-6) тоа е за подобар преглед и не влијае во  останатите барањња.


3.Цикломатската комплексност на кодот е 11.Ја добив така што ги пребројав бројо на јазли -27,бројот на ребра-36 и се водев по формулата БРОЈ НА РЕБРА - БРОЈ НА ЈАЗЛИ + 2 
па така добив 36 -27 +2=11.Истото се добива доколку се пребројат предикатните јазли -10 и се водиме по формулата БТОЈ НА ПРЕДИКАТНИ ЈАЗЛИ + 1


4.![Screenshot (134)](https://github.com/IlijaBozoski/SI_2023_lab2_216019/assets/127144144/b3cc5df9-c706-4965-abc6-c0662ef43410)


Објаснување:Доволни беа 4 случаи:Првиот -Случај во кој постојат корицници и се внесени коректни информации па така овој случај може да се каже како правилен тек на програмата,Вториот  случај-Измена само во пасвордот -нема празно место па така влегува во тој дел од кодот ,Третиот случај -кога не постои корисник user=null и во овој случај влегува во исклучокот,Четвртиот случај-email кој не содржи @ и . исто така и пасворд кој го содржи името на userot и со ова се опфатени сите случаи.


5.![Screenshot (137)](https://github.com/IlijaBozoski/SI_2023_lab2_216019/assets/127144144/131c29d2-a921-4772-af99-b947903a483a)


Објаснување:Затоа што самиот услов е изграден од 3 подуслови кои се поврзани со OR условвот би бил точен кога батем еден од подусловите е точен .Во општ случај трите подуслови би имале 8 (2^3) сценарја.Но затоа што условот се проверува се додека наиде на Точно се намалува бројот на случаи.Затоа има 3 случаи во кој е точен овој израз-Кога првиот подуслов е точен(не ги прверува 2 и 3),Кога вториот подуслов е точен(не го проверува 3) и кога третиот е точен.Има само еден случај кога овој израз е неточен и тоа кога сите три подуслови се неточни.


6.//
