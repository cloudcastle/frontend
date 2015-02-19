## Файловая структура

Todo, а пока смотри [демо проект] (https://github.com/a-frolovsky/demoapp)


## Правила именования:

`.block`

`.block_element`

`.-modifier`


**Примеры:**
```sass
.menu // блок
  position: relative
  width: 100%
  height: 40px
  
  &.-compact // модификатор блока
    height: 20px

.menu_item // элемент 
  float: left
  margin: 0 10px
  background: #ccc

  &.-active // модификатор элемента
  background: #000
  .menu_link
    color: #fff

.menu_link // элемент 
  font-size: 1.2rem
  color: #000
```




