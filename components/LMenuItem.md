# LMenuItem

Элемент меню

## Props

<!-- @vuese:LMenuItem:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|treeview|Нужна ли вложенность элементов|`Boolean`|`false`|-|
|link|Ссылка|`String`|`false`|#|
|name|Текст элемента|`String`|`false`|-|
|icon|Иконка|`String`|`false`|-|
|type|Тип элемента|`String`|`false`|item|
|badge|Уведомления|`String`|`false`|-|
|badgecount|Количество уведомлений|`Number`|`false`|-|
|dropdown|Выпадающее меню|`Object`|`false`|-|

<!-- @vuese:LMenuItem:props:end -->


## Slots

<!-- @vuese:LMenuItem:slots:start -->
|Name|Description|Default Slot Content|
|---|---|---|
|submenu|Slot submenu для формирования вложенности|-|
|dropdown-menu|Слот выпадающего меню|-|

<!-- @vuese:LMenuItem:slots:end -->


