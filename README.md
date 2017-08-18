# Информация для парсера курсов отделений банка 

### Описание параметров в xml файле

```
<bank license="Номер лицензии банка" xml-version="1.0" encoding="UTF-8">
    <rates unit="Уникальный номер объекта" okato="Классификатор ОКАТО" date="Время последнего обновления курса" city="Название города" name="Название объекта" address="Полный адрес" phone="Телефон" hours="Время работы">
        <rate cur="Трехбуквенный код валюты">
            <type>Тип операции (cash|online)</type>
            <buy>59.00</buy>
            <sell>59.75</sell>
            <quantity>Количество единиц</quantity>
        </rate>
    </rates>
</bank>
```

### Файлы

* docs/rates.xml - пример XML 
* docs/rates.xsd - описания структуры XML