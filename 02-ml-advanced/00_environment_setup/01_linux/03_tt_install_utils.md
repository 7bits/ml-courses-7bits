# Установка ПО в Ubuntu

[Видео: Установка программ в ubuntu](https://www.youtube.com/watch?v=M8jUdCUV5oE&t=0s&list=PLLyuiBK_HOLNm8T5Xtl7dDquJey917TXy&index=2).

Программы можно ставить через терминал с помощью утилиты `apt`:

- `apt update` обовление индексов и базы даных пакетов
- `apt upgrade` обновление установленных пакетов
- `apt install PACKAGE_NAME` установка пакета `PACKAGE_NAME` и его зависимостей

Перед установкой пакетов рекомендуется сделать обновление индексов `apt update`, если вы давно это не делали(неделя).

## Базовые программы

В курсе мы используем python и разные библиотеки для него. Чтобы они установились, нам необходимо поставить следующие программы:

```bash
sudo apt install gcc g++ make cmake build-essential clang # для компиляции библиотек
sudo apt install git curl mc # вспомогательные программы
```
