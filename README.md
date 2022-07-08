# PyBebra
Беброчный язык программирования

Создан по рофлу, не воспринимайте его всерьёз!

# Использование
**Создай файл - `test.bbr`**
```py
bebra("Привет, бебромир!")
```
**Запуск**

```py
python shell.py
> run("test.bbr")
```

# Беброчная документация

**Главное**

`python shell.py` открывает консоль. Команда запуска `run("test.bbr")`

**Переменные**

Переменные создаются с помощью ключевого слова `beb`

```py
beb a = 100
beb b = 50
beb v = a + b
beb g = v * b

bebra(v)
bebra(g)
```

Вывод:
```
150
7500
```

**Условия**

Если - bif, или - belif, иначе - belse

```py
beb a = 100

bif a == 100 bthen bebra("a = 100") belse bebra("a не = 100")
```

Вывод:
```
а = 100
```

**Циклы**

```py
for i = 0 to 5 bthen
    bebra("привет")
bend
```

Вывод:
```
привет
привет
привет
привет
привет
```

**Функции**

```py
bfunc pybebra(a) -> a + "Bebra"

bebra(pybebra("Это Py"))
```

Вывод:
```
Это PyBebra
```

# Конец
Это беброчный конец файла ридми! Удачного беброиспользования!
