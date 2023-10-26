# My_collection_swagger_petstore
This repository contains requests for working with the petstore collection in swagger

Collection in swagger with which the work was done: https://petstore.swagger.io/

A collection in Postman was created based on this collection.
The collection contains 4 queries:
POST request to add a new pet,
PUT request to update the data about the pet,
GET request to retrieve information about the pet,
DELETE request to delete pet data.

An environment variable (petID) was created for the pet ID, as well as the base URL (baseURL).
A script was written that takes the id of the created pet from the response body and writes it to the environment (petID)
Tests were written to test 200 responses.

-------------------------------------------------------------------------------

Коллекция в Swagger, с которой выполнялась работа: https://petstore.swagger.io/

На основе этой коллекции была создана коллекция в Postman.
Коллекция содержит 4 запроса:
POST-запрос для добавления нового питомца,
PUT-запрос для обновления данных о питомце,
GET-запрос для получения информации о питомце,
DELETE-запрос для удаления данных о питомце.

Для ID питомца была создана переменная для окружения (petID), также как и для основного URL (baseURL).
Был прописан скрипт, который берет из тела ответа ID созданного питомца и записывает в окружение (petID)
Были написаны тесты для проверки 200 ответа.
