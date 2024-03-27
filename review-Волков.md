По названию x не понятно что происходит в коде
```
let x = i * 4 + MathAddon.getRemainder(j, 4); 
                if (x = rndNumbers[0])             
```

Аналогично не понятно что охначает tC, xC
```
let tC = result[i];
            let xC = tC.getValue();
```

Тут добавил уничтожение массивов в массиве и уничтожения рандомайзера
```
method void dispose () {
        var int i;
        let i = 0;
        while(i < 4)
        {
            do board[i].dispose();
            let i = i + 1;
        }  
        do board.dispose();
        do rnd.dispose;
        do Memory.deAlloc(this);
        return;
    }
```

Пробелы можно заменять на moveCursor
```
do Output.moveCursor(0, 10);
        let s = "Game 2048";
```
Задержку поменьше сделал, нам показалось что она неоправдано большая
Ну и вынес в переменную
```
let delay = 100;
```

Игра классная, нам понравилась.
В целом работает и работает хорошо. Все молодцы, всем ставлю 5, кроме Гриши, Грише ставлю 4.
Сегодня плохо вёл себя.