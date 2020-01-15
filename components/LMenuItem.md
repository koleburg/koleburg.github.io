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


## Methods

<!-- @vuese:LMenuItem:methods:start -->
|Method|Description|Parameters|
|---|---|---|
|openDropdown|Открытие выпадающего меню|-|
|closeDropDown|Закрытие выпадающего меню|-|

<!-- @vuese:LMenuItem:methods:end -->


## Data

<!-- @vuese:LMenuItem:data:start -->
|Name|Type|Description|Default|
|---|---|---|---|
|drop|`Object`|Состояние "Открытие выпадающего меню"|-|

<!-- @vuese:LMenuItem:data:end -->


