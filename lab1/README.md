# Системы аутентификации и защиты от несанкционированного доступа

Лабораторная работа №1

## Цель

Вывести информацию о системе

## Исходные данные

1.  ОС Windows 10
2.  RStudio Desktop
3.  Интерпретатор языка R 4.3.0.

## План

1.  Выполнить команду uname -r
2.  Выполнить команду cat /proc/cpuinfo | grep “model name”
3.  Выполнить команду journalctl -q -b | tail -n 30

1\.  Сначала выполним команду uname -r для вывода информации о системе

``` bash
uname -r
```

    3.1.7-340.x86_64
    
2\. Далее команда cat /proc/cpuinfo \| grep "model name" для вывода информации о процессоре, строки которой содержат "model name"

```{bash}
cat /proc/cpuinfo | grep "model name"
```
	
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	model name  : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz


