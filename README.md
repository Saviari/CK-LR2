# CK-LR2
Сокрытие информации в растровых изображениях с использованием стегоключей.

В наименее значащие биты (метод LSB) цветовых каналов RGB растрового изображения при помощи стегоключа записывается скрытое сообщение, закодированное в двоичный код.
Интерфейс программы предполагает выбор изображения-контейнера, выбор скрываемого сообщения, ввод ключа, шифрование, сохранение стеганоконтейнера, выбор стеганоконтейнера, дешифровку.
![1](https://user-images.githubusercontent.com/51208839/198058477-4d383207-57ab-4174-9676-6f295c65557b.png)
Метод сокрытия информации предполагает, что изменения в изображении не будут видны для человеческого глаза. Для того, чтобы проверить, что пиксели действительно меняются, выведем во второй pictureBox вместо картинки с результатом шифрования картинку, где контрастным цветом будут выделены изменяемые пиксели.
![2](https://user-images.githubusercontent.com/51208839/198058773-dcea44f4-ca90-4565-90b4-aaba284b0f97.png)
![3](https://user-images.githubusercontent.com/51208839/198058803-db25fd30-6856-41dc-bd6f-4b010266dc60.png)

Дешифрование:
![4](https://user-images.githubusercontent.com/51208839/198059349-fe4eaa12-9e3f-44f8-83f5-3e1cc72a5dc8.png)
