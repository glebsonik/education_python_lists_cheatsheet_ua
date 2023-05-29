
Шпаргалка по Python
===============================

Lists
----
```python
names = ["Andrii", "Jack", "Bob"] # Наш список імен
len(names)                        # Поверне 3, кількість елементів
names.index("Jack")               # Поверне 1, тобто порядковий номер
names[2]                          # Поверне Bob, тобто третій елемент з нульового
names[-1]                         # Поверне Bob (рахуємо з кінця)
names[-2]                         # Поверне Jack (рахуємо з кінця)
names.insert(1, "John")           # Додасть імʼя John на вказаний індекс
print(names)                      # Виведе ["Andrii", "John", "Jack", "Bob"]

names = ["Andrii", "Jack", "Bob"]
names.append("Billy") # Додасть Billy у кінець списка
print(names)          # Виведе ["Andrii", "Jack", "Bob", "Billy"]

names = ["Andrii", "Jack", "Bob"]
names.reverse() # Розверне список
print(names)    # Виведе ["Bob", "Jack", "Andrii"]

names = ["Jack", "John", "Billy", "Bob", "Andrii"]
names.sort() # Відсортує масив, у алфавітному порядку
print(names) # Виведе ["Andrii", "Billy", "Bob", "Jack", "John"]

names = ["Jack", "Bob", "Billy", "Bob"]
names.count("Bob") # поверне 2, порахує кількість імен "Bob"

names = ["Jack", "Bob", "Billy", "Bob"]
names.remove("Bob") # видалить перше знайдене імʼя Bob
print(names)        # Виведе ["Jack", "Billy", "Bob"]

names = ["Jack", "Bob"]
print("Jack" in names) # поверне True, in перевіряє чи є елемент у списку

names = ["Jack", "Bob"]
names.extend(["Olya", "Serge"]) # Розширить список ще двома іменами Olya і Serge
print(names) # поверне ["Jack", "Bob", "Olya", "Serge"]

# Або extend можна замінити використовуючи додавання
names_1 = ["Andrii", "Billy"]
names_2 = names_1 + ["Olya", "Serge"]
print(names_2) # поверне ["Andrii", "Billy", "Olya", "Serge"]

names = ["Jack", "Bob"]
names.clear() # Повністю очистить список
print(names)  # Поверне [], тобто порожній список
```

```python
# Список з числами
numbers = [1,2,25,3] # Cписок з числами
min(numbers) # поверне 1
max(numbers) # Поверне 25
sum(numbers) # Поверне 31
```
