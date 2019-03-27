# Heedbook. 
# Тестовое задание (C#).

## Установка Microsoft Azure Storage Explorer.
1. Установить [Microsoft Azure Storage Explorer]
2. Подключиться к hbgittest, используя 

| Name | Key |
| ------ | ------ |
| Storage account name  | hbtesttask |
| Key | c314HTO6+7n+zXWVqo8KXZVdZGXvTq7M9J4XWl861TEKuET1SU05yYBVRVBPUItJn6OCE7ULlVD/kyY5oW+nbA==|
| Connection string | DefaultEndpointsProtocol=https;AccountName=hbtesttask;AccountKey=c314HTO6+7n+zXWVqo8KXZVdZGXvTq7M9J4XWl861TEKuET1SU05yYBVRVBPUItJn6OCE7ULlVD/kyY5oW+nbA==;EndpointSuffix=core.windows.net |

В blob storage имеется три контейнера
- videos
- audios
- frames

В контейнере videos находится видео *test.mp4*. 

## Задание 1.
Написать скрипт, который бы извлекал аудио из видео *test.mp4* и сохранял его в контейнер audios в формате wav. 
При этом запрещено сохранять любую информацию о файлах локально (любое локальное сохранение файлов или информации о них в решении будет расцениваться, как неправильное решение). 

## Задание 2.
Написать скрипт, который бы извлекал каждые три секунды кадр из видео *test.mp4* и сохранял их в контейнер frames. 
При этом запрещено сохранять любую информацию о файлах локально (любое локальное сохранение файлов или информации о них в решении будет расцениваться, как неправильное решение). 

### Полезные ссылки
https://docs.microsoft.com/ru-ru/azure/visual-studio/vs-storage-aspnet5-getting-started-blobs

[Microsoft Azure Storage Explorer]: <https://azure.microsoft.com/en-us/features/storage-explorer/>
