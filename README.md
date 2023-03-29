# розыгрыш игрушек в магазине детских товаров

## необходимый функционал

* в программе должен быть минимум один класс со следующими свойствами:
   * id игрушки,
   * текстовое название,
   * количество
   * частота выпадения игрушки (вес в % от 100)
 
* Метод добавление новых игрушек и возможность изменения веса (частоты выпадения игрушки)
* Возможность организовать розыгрыш игрушек.

### __примечание:__ 
С помощью метода выбора призовой игрушки – мы получаем эту призовую игрушку и записываем в список\массив.
Это список призовых игрушек, которые ожидают выдачи.
Еще у нас должен быть метод – получения призовой игрушки.
После его вызова – мы удаляем из списка\массива первую игрушку и сдвигаем массив. А эту игрушку записываем в текстовый файл.
Не забываем уменьшить количество игрушек
