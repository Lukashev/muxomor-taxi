# Мухомор-такси.

## Идея.

Создать мобильное приложение с бекендом позволяющее.

1. Регистрация пользователя.

1.2 Через соцсети.

1.3 Подтверждение телефона через код в смс.

2. Роли.

**Перевозчик.**

Регистрация транспортного средства с фото (тачка, морда водителя, паспорт)

Создание поездки.

- от куда (адрес, координаты)

- куда (адрес, координаты)

- когда (дата время)

Лимит на будущее время поездки (от 2-3 часов до 3-4 суток).

Получение предложений от пассажиров.

Реакция на предложение.

**Пассажир.**

Создание поездки.

- от куда (адрес, координаты)

- куда (адрес, координаты)

- когда (дата время)

Лимит на будущее время поездки (от 2-3 часов до 3-4 суток).

Получение предложений от водителей с возможностью принять.



## Концепция.

Пассажир создает заказ на поездку с указанием стоимости и обязательным или нет наличием попутчиков и их количества.

При достижении этого количества попутчиков водителям отправляется уведомление с ценой и кол-вом человек.

Водитель при создании будущей поездки указывает минимальную ее стоимость для одного пассажира.


## Интеграция с телеграм месенжером.

При заходе на канал бота регистрируем человека и предлагаем выбор пассажир, перевозчик либо то и другое.

После этого регаем человека и тянем его телефон.

Далее уведомляем водителей по появлению нового заказа на подписанный район города.

В последствии монетизируем подписку на раены с помесячной оплатой.









