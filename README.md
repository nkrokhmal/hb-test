# Heedbook. 
# Тестовое задание (C#).

## Установка Microsoft Azure Storage Explorer.
1. Установить [Microsoft Azure Storage Explorer]
2. Подключиться к hbgittest, используя 

| Name | Key |
| ------ | ------ |
| Storage account name  | hbgittest |
| Key | up4w+hjVi6jo+yXPrwi1t16G8sBPWZEocCqRMSzlaaJ2nntWfXvd3Ondk9J52FlxSLOm21fZRe26w14UcMQjLA==|
| Connection string | DefaultEndpointsProtocol=https;AccountName=hbgittest;AccountKey=up4w+hjVi6jo+yXPrwi1t16G8sBPWZEocCqRMSzlaaJ2nntWfXvd3Ondk9J52FlxSLOm21fZRe26w14UcMQjLA==;EndpointSuffix=core.windows.net |

В blob storage имеется три контейнера
- videos
- audios
- frames

В контейнере videos находится видео *test.mkv*. 

## Задание 1.
Написать скрипт, который бы извлекал аудио из видео *test.mkv* и сохранял его в контейнер audios в формате wav. 
При этом запрещено сохранять любую информацию о файлах локально (любое локальное сохранение файлов или информации о них в решении будет расцениваться, как неправильное решение). 

## Задание 2.
Написать скрипт, который бы извлекал каждые три секунды кадр из видео *test.mkv* и сохранял их в контейнер frames. 
При этом запрещено сохранять любую информацию о файлах локально (любое локальное сохранение файлов или информации о них в решении будет расцениваться, как неправильное решение). 

### Полезные ссылки
https://docs.microsoft.com/ru-ru/azure/visual-studio/vs-storage-aspnet5-getting-started-blobs

[Microsoft Azure Storage Explorer]: <https://azure.microsoft.com/en-us/features/storage-explorer/>
