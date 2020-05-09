# PHP-lvl-1
Education

# Заметки
## Простые высказывания
### Логические выражения
```==```
```> <```


## Сложные высказывания
### Логические операции  
  

**Коньюкция** - логическое умножение  
Когда оба выражения/высказывания истины! Если хотя бы одно ложное, то все высказывание - ложно!  
[Операторы:
```and```
```&&```]

**Дизьюнкция** - логическое сложение  
Когда **Хотя бы одно** выражения/высказывания истино!  
[Операторы:
```||```
```or```]

**Инверсия** - отрицание  
**инвертинование логического** выражения/высказывания    
[Операторы:
```!```]  

```
$res = 2>3; //лож
$res = !$res; // теперь исрина  
```
## Условные конструкции  
- это витвление дальнейших действий. Выход из линейного программирования.  
**Конструкции**
``` 
**if** ( var1 ) {  
    code1
}  
**else if** (var2) {  
    code2
}  
**else** {  
    code3
}  
```

Альтернативный синтаксис  
<?php if (): ?>
<p>text1</p> 
<?php elseif (): ?>
<p>text2</p> 
<?php else: ?>
<p>text3</p> 
<?php endif; ?>

Шорт теги:
Старый: <?php print($var); ?>
Shot teg: <?=$var; ?>  
точку в конце ставить не обязательно, но желательно