# Отчёт о тестировании приложения "Ticket"

## Краткое описание
Проведено тестирование на ПО IntelliJ IDEA Community, для проверки работоспособности кода по расчёту бонусной программы.

## Описание тестов
На ПО IntelliJ IDEA Community, было создано базовое приложение, для тестирования работоспособности кода
```
public class Main {
    public static void main(String[] args) {
        long amount = 10000;
        long bonus = amount / 20; {
        }
        System.out.println(bonus);
    }
}
```

Проводилось позитивное тестирование функционала выполнения заданной операции.

1. Задаём переменную "long amount" любым значением
2. Выполняем команду "Run"
3. Видим результат расчёта, количество милей за покупку билета

## Результаты
1. 100% успешных тестов
2. Issue: Отсутствуют

## Общие рекомендации
* Задаём переменную "long amount" любым значением и получаем результат