﻿# rc5_chiper
## Описание RC5
RC5 — это симметричный блочный шифр, разработанный Роном Ривестом в 1994 году. Он известен своей простотой и эффективностью, а также поддержкой различных размеров блоков, ключей и количества раундов. RC5 использует операции сдвига, XOR, сложение и вычитание.

## Основные характеристики RC5:
  Размер блока: 32, 64 или 128 бит.
  Размер ключа: от 0 до 2040 бит.
  Количество раундов: от 0 до 255.

## Как пользоваться приложением
#### Запуск приложения:
python .\main.py
### Ввод данных:
Сообщение: Введите сообщение, которое хотите зашифровать или расшифровать.
Ключ: Введите ключ длиной 16 символов. Ключ должен быть одинаковым для шифрования и дешифрования.
### Шифрование:
1) Введите сообщение и ключ.
2) Нажмите кнопку "Зашифровать".
3) Результат будет отображен в поле результата в виде шестнадцатеричной строки.
### Дешифрование:
1) Введите зашифрованное сообщение в виде шестнадцатеричной строки и ключ.
2) Нажмите кнопку "Расшифровать".
3) Результат будет отображен в поле результата в виде расшифрованного текста.
### Копирование результата:
Нажмите кнопку "Копировать результат", чтобы скопировать результат в буфер обмена.

## Особенности использования
Дополнение сообщения: Сообщение автоматически дополняется пробелами до кратного 8 байтам перед шифрованием. При дешифровании эти пробелы удаляются.
Ограничение на ключ: Ключ должен быть ровно 16 символов. Если ключ не соответствует этому требованию, приложение выдаст предупреждение.
Шестнадцатеричный формат: Зашифрованное сообщение отображается в шестнадцатеричном формате для удобства хранения и передачи.

## Пример использования

Введите сообщение: "Hello, World!"

Введите ключ: "1234567890abcdef"

Зашифрованное сообщение: 0f284c2ef9a5d67c61fb094bdd669973

Расшифрованное  сообщение: "Hello, World!"
