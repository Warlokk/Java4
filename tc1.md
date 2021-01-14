# Test-case 1 "Ввод исходных данных"

**Priority:** Very High

**Precondition:**
* на рабочей машине установлена Java не ниже версии 8.0
* установлен IDE
* Test-Data: balance = `2_000_000_000`; transaction = `500_000_000`

**Steps**

1. Установить на 3 и 4 строке main.class значения `balance` и `transaction`
1. Запустить код на исполнение CTRL+SHIFT+F10

**Ожидаемый результат:** в логе выводится сумма значений balance и transaction `2_500_000_000`