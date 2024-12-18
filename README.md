# Домашнее задание к занятию "`redis and memcached`" - `Nikonov D.A.`

##Задание 1. Кеширование 

**Приведите примеры проблем, которые может решить кеширование.** 

## Ответ 1.

```
1. Ускорение работы приложений
2. Оптимизация затрат
3. Отказоустойчивость
4. Снижение нагрузки на базу 
5. Ускорение загрузки страниц
```
 
##Задание 2. Memcached 

**Установите и запустите memcached.**  
**Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.**

## Ответ 2.

![memcached](5409249767734764514.jpg)
 
 
##Задание 3. Удаление по TTL в Memcached 

**Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.**
**Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.**

![key5sec](5409249767734764528.jpg)
 
##Задание 4. Запись данных в Redis 

**Запишите в Redis несколько ключей с любыми именами и значениями.** 

**Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.**

![redis](5409249767734764605.jpg)


##Задание 5*.Работа с числами 


**Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10. **

**Приведите скриншот, где будут проделаны все операции и будет видно, что значение key5 стало равно 10.** 

![key5](5409249767734764614.jpg)
