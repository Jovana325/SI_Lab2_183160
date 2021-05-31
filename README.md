# ВТОРА ЛАБОРАТОРИСКА ВЕЖБА ПО ПРЕДМЕТОТ СОФТВЕРСКО ИНЖЕНЕРСТОВО
# ЈОВАНА ЃУРКОВСКА, БР. НА ИНДЕКС 183160
# Control Flow Graph
![Control Flow Graph](https://github.com/Jovana325/SI_lab2_183160/blob/main/CFG.png)
# Цикломатска комплексност
Цикломатската комплексност на овој код изнесува 9. Истата ја добив со помош на формулата P+1. Во овој случај P=8, па следува дека цикломатската комплексност е 9.
# Tест случаи според Multiple condition критериумот
if (hr < 0 || hr > 24){  //7      <br />
    T || X, F|| T, F||F            <br />
if (min < 0 || min > 59)  //13     <br />
    T || F, F|| T, F||F          <br />
if (sec >= 0 && sec <= 59) //16    <br />
    T && T , T && F, F && T, F && F     <br />
else if (hr == 24 && min == 0 && sec == 0) {  //20   <br />
    T && T && T, T && F && F, F && F && T, F && T && F, T && F && T   <br />
![Multiple condition](https://github.com/Jovana325/SI_lab2_183160/blob/main/Multiple%20condition.png)
# Tест случаи според Every branch критериумот
Ги зедов броевите: <br />
3,1,3 <br />  -1,1,1 <br />  5,0,5 <br />
![Every branch](https://github.com/Jovana325/SI_lab2_183160/blob/main/Every%20Branch.png)
