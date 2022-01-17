
// https://dispex.org/api/vtest/docs/swagger/index.html

// https://docs.google.com/document/d/1R6S-aQYzXQUVpTl3mi9lEUNQ0b89s72k6NKgKAo48_E/edit

// Срок выполнения - 2 дня 

// Важно. Технические вопросы по номеру телефона , указанному в приглашении не задавать - только организационные. Все работает корректно - если что то не получается , значит вам не хватает знаний 

// Разработать SPA

// Описание:
// Поиск адреса и список жильцов должны быть на одном экране
// Добавление/изменение/удаление данных - в модальных диалогах

// стэк: javaScript react/hooks/redux/redux-thunk 
// можно использовать: axios, antd или material ui
// TypeScript не использовать 

// API BASE URL : https://dispex.org/api/vtest

// https://dispex.org/api/vtest/docs/swagger/index.html

// Функционал:

// 1) Выбор адреса
// Улица -> Дом -> Квартира
// (возможность поиска)

// API:
// GET /Request/streets
// GET /Request/houses/{id}
// GET /Request/house_flats/{id}

// можно использовать только улицы где cityId = 1.
// для тестирования использовать дома Федюнинского 30 (все корпуса)  + привязываться к квартирам, а не к подъездам и домам

// 2.a) Добавление и Привязка жильца к выбранной квартире
// (Номер телефона , email, ФИО),  
// Обязательный параметр - Номер телефона
// 2.b) Изменение данных жильца
// 2.c) Отвязка жильца от квартиры

// API:
// POST ​  /HousingStock​/client
// PUT    /HousingStock/bind_client
// DELETE ​/HousingStock​/bind_client​/{id}

// 3) Отображение всех жильцов в квартире

// API:
// GET /HousingStock/clients

// Результат отправлять в telegram на номер телефона , указанный в ответе на вакансию в виде - ссылка на GitHub или Архив + ссылка на резюме 
