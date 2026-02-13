Вы можете создать простую коллекцию упорядоченных элементов, используя список Python. Например:

`fruits = ["Cherry", "Apple", "Pear"]`

или

`states_of_america = ["Delaware", "Pennsylvania", "New Jersey", "Georgia", "Connecticut", "Massachusetts", "Maryland", "South Carolina", "New Hampshire", "Virginia", "New York", "North Carolina", "Rhode Island", "Vermont", "Kentucky", "Tennessee", "Ohio", "Louisiana", "Indiana", "Mississippi", "Illinois", "Alabama", "Maine", "Missouri", "Arkansas", "Michigan", "Florida", "Texas", "Iowa", "Wisconsin", "California", "Minnesota", "Oregon", "Kansas", "West Virginia", "Nevada", "Nebraska", "Colorado", "North Dakota", "South Dakota", "Montana", "Washington", "Idaho", "Wyoming", "Utah", "Oklahoma", "New Mexico", "Arizona", "Alaska", "Hawaii"]`

### доступ к элементам списков

Вы можете указать имя списка, затем квадратные скобки, а затем индекс элемента, который вы хотите. Например:

`states_of_america[0]`

вернет "Delaware".

Помните, что во всем, что связано с компьютерами, первое число, с которого мы начинаем отсчет, — это 0, а не 1. Поэтому 0, 1, 2, 3 вместо 1, 2, 3, 4.

### отрицательные индексы

Вы можете получить доступ к элементам списка, отсчитывая с конца списка, используя отрицательные целые числа. Например:

```
fruits = ["Cherry", "Apple", "Pear"]
fruits[-1] #это будет "Pear"
```

### изменение элементов
Вы можете использовать тот же синтаксис, чтобы получить доступ к элементам списка и изменить их. Например:

```
fruits = ["Cherry", "Apple", "Pear"]
fruits[0] = "Orange"
# теперь список fruits будет ["Orange", "Apple", "Pear"]
```

### добавление элементов
Вы можете добавить элементы в конец списка, воспользовавшись функцией `append()`. Например:

```
fruits = ["Cherry", "Apple", "Pear"]
fruits.append("Orange")
# теперь список fruits будет ["Cherry", "Apple", "Pear", "Orange"]
```

### документация по спискам
Вы можете найти документацию по спискам Python и другим связанным функциям здесь: https://docs.python.org/3/tutorial/datastructures.html