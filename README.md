# restaurant-servlet

Ресторан

Існують ролі: Клієнт, Менеджер.
Клієнт (авторизований користувач) здійснює замовлення із меню — каталогу страв, а також має можливість переглядати каталог з врахуванням сортування:
- за назвою страви;
- за вартістю;
- категорією
  та робити фільтрацію списку страв за категоріями. Клієнт, в рамках одного замовлення, може замовити декілька однакових страв.
  Менеджер керує замовленнями: після отримання нового замовлення, відправляє його на готування. Після приготування Менеджер передає замовлення на доставку. Після  доставки і отримання оплати Менеджер переводить статус замовлення у «виконано».