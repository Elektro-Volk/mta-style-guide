
# MTA Lua Style Guide (*rus*)

Этот документ призван унифицировать и навести порядок среди ресурсов MTA. 

## Отступы и форматирование

* Уровни вложенности разделяются с помощью двух пробелов.

```lua
-- Плохо
if condition then
    doSome()
end

-- Хорошо
if condition then
  doSome()
end
```
