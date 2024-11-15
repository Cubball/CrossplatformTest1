# МКР 1
## Умова
### Варіант 35
Сьогодні в космосі знаходяться сотні супутників, і всі вони обмінюються даними. При цьому система розпізнавання сигналів працює за схемою "Свій-Чужий". Один із супутників відправляє запит іншому супутнику у форматі двох цілих чисел, а другий супутник відповідає першому так само двома цілими числами. Перші два числа першого супутника є сумою цифр і кількість цифр тих двох чисел, якими повинен відповісти другий супутник. При цьому як відповідь повинні вийти числа, що становлять найбільше і найменше можливі значення, які можуть бути сформовані за описаним вище методом.

Ви маєте написати програму, яка формує відповідь для другого супутника за відомими числами, отриманими від першого супутника.

### Вхідні дані
У вхідному файлі INPUT.TXT записані 2 натуральні числа S і K, що представляють суму та кількість цифр відповідно (K ≤ 100). При цьому гарантується, що можна скласти хоча б одне K-значне число, сума цифр якого дорівнює S.

### Вихідні дані
У вихідний файл OUTPUT.TXT виведіть два числа – відповідь другого супутника. При цьому слід пам'ятати, що всі числа не мають нулів, що лідирують.

## Запуск застосунку
Виконати команду з даної папки:
```bash
dotnet run --project App
```
Вхідний файл `INPUT.TXT` знаходиться в даній папці

Вихідний файл `OUTPUT.TXT` записується в дану папці

## Запуск тестів
Виконати команду з даної папки:
```bash
dotnet test
```
Для виведення проміжних результатів:
```bash
dotnet test --logger "console;verbosity=detailed"
```
