# ВТОРА ЛАБОРАТОРИСКА ВЕЖБА ПО ПРЕДМЕТОТ СОФТВЕРСКО ИНЖЕНЕРСТОВО
# ЈОВАНА ЃУРКОВСКА, БР. НА ИНДЕКС 183160
# Control Flow Graph
![Control Flow Graph](https://github.com/Jovana325/SI_lab2_183160/blob/main/Control%20Flow%20Graph-slika.png?raw=true)
# Цикломатска комплексност
Цикломатската комплексност на овој код изнесува 8. Истата ја добив со помош на формулата P+1. Во овој случај P=7, па следува дека цикломатската комплексност е 8.
# Tест случаи според Multiple condition критериумот
if (hr < 0 || hr > 24){  //7      <br />
    T || X, F|| T, F||F
if (min < 0 || min > 59)  //13
    T || F, F|| T, F||F
if (sec >= 0 && sec <= 59) //16
    T && T , T && F, F && T, F && F
else if (hr == 24 && min == 0 && sec == 0) {  //20
    T && T && T, T && F && F, F && F && T, F && T && F, T && F && T
![Multiple condition](https://github.com/Jovana325/SI_lab2_183160/blob/main/Multiple%20condition.png)
# Tест случаи според Every branch критериумот
