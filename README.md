# Тест Angular

## Задание 1.

1. Сгенерировать новый проект при помощи [Angular CLI](https://cli.angular.io). Тип стилей использовать SCSS.
2. Установить и подключить [Angular Material](https://material.angular.io)
3. Сгенерировать компонент app-tabe при помощи [Angular CLI](https://cli.angular.io)
4. В компоненте app-tabe при помощи компонента Table (mat-table) сделать одну таблицу одновременно

и с фильтром:
![enter image description here](Filtering.jpg "Filtering")

и с сортировкой:
![enter image description here](Sorting.jpg "Sorting")

Данные для таблицы:
```ts
const ELEMENT_DATA: PeriodicElement[] = [
  {position: 1, name: 'Hydrogen', weight: 1.0079, symbol: 'H'},
  {position: 2, name: 'Helium', weight: 4.0026, symbol: 'He'},
  {position: 3, name: 'Lithium', weight: 6.941, symbol: 'Li'},
  {position: 4, name: 'Beryllium', weight: 9.0122, symbol: 'Be'},
  {position: 5, name: 'Boron', weight: 10.811, symbol: 'B'},
  {position: 6, name: 'Carbon', weight: 12.0107, symbol: 'C'},
  {position: 7, name: 'Nitrogen', weight: 14.0067, symbol: 'N'},
  {position: 8, name: 'Oxygen', weight: 15.9994, symbol: 'O'},
  {position: 9, name: 'Fluorine', weight: 18.9984, symbol: 'F'},
  {position: 10, name: 'Neon', weight: 20.1797, symbol: 'Ne'},
];
```


### Задание 2.
 
 1. Сгенерировать компонент app-start-page при помощи [Angular CLI](https://cli.angular.io)
 2. В компоненте app-start-page при помощи компонента Button (mat-button) сделать кнопку "Показать таблицу"
 3. При клике по этой кнопки должен появлятся компонент app-tabe поверх страницы в модальном окне. Для этого обязательно использовать CDK Overlay из [Angular Material](https://material.angular.io)
   > Визуально долно выглядеть **примерно** так:
   [Modal Bootstrap](https://getbootstrap.com/docs/4.3/components/modal/)
   > ![enter image description here](Modal.jpg "Modal")
