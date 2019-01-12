![](https://javascript30.com/images/JS3-social-share.png)

 ### [Day 1: Drum Kit](https://cyberspacedk.github.io/JavaScript30/01%20-%20JavaScript%20Drum%20Kit/index-START.html)
 - привязка к event.keykode и data атрибуту тега <audio>
 
 ### [Day 2: JS & CSS clock](https://cyberspacedk.github.io/JavaScript30/02%20-%20JS%20and%20CSS%20Clock/index-START.html)
 - получаем текщую дату с помощью new Date
 - заводим в переменные час, мин, сек
 - рассчитываем текущее полoжение
 ```javascriptlet 
секунды = ((secondsNow / 60) * 360) + 90;
минуты = ((minutesNow / 60) * 360) + ((secondsNow/60)*6) + 90;
часы = ((hoursNow / 12) * 360) + ((minutesNow/60)*30) + 90;
 ```
 - меняем CSS свойство rotate() для каждой стрелки
 
 ### [Day 3: CSS Variables](https://cyberspacedk.github.io/JavaScript30/03%20-%20CSS%20Variables/index-START.html)
 
 - задаем переменные в : root
 - задаем атрибут name для инпутов соответсвующий имени переменной
 - вешаем событие на каждый инпут
 - с помощью js свойства обращаемся к корневому елементу и устанавливаем новое значение переменной основанной на текущем значении инпута
 ```javascript
 document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);
```
### [Day 4: Array Methods 1](https://cyberspacedk.github.io/JavaScript30/04%20-%20Array%20Cardio%20Day%201/index-START.html)
- Интересные задания № 7, 8
