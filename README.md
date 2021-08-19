# Kuznechik_AES
2 курс, 4 семестр, 2 ЛР
Программа для работы с алгоритмами шифрования Kuznechik и AES

Исполььзован паттерн MVVM, Ioc-контейнер Autofac

Создан интерфейс ICipher, который определяет методы поддержки шифрования строк.
В интерфейсе объявляются два метода Encode() и Decode(), которые используются для
шифрования и дешифрования строк, соответственно. Реализованы 2 класса реализующих
данный интерфейс.
Алгоритмы: Kuznechik, AES 
