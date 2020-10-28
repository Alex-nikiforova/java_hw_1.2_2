# Отчёт о тестировании приложения "Extra bonus"

## Краткое описание

28.10.2020 проведено тестирование приложения "Extra bonus" на получение итоговой суммы бонуса для клиента, в ходе которого были выявлены следующие дефекты:

* [Выводится неверная итоговая сумма бонуса при реализации кода "extra bonus"](https://github.com/Alex-nikiforova/java_hw_1.2_2/issues/1)

На тестирование затрачено: 5 минут

## Описание тестов

Было проведено функциональное тестирование кода "money transfer":
```
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
 ```
, где `regularBonus` - текущий размер скидки клиента клиента;
`specialBonus` - дополнительный размер скидки клиента;
`totalBonus` - итоговая сумма скидки клиента.

При реализации кода выводится неверная итоговая сумма скидки: "0.8999999999999999".

## Результаты

* [Выводится неверная итоговая сумма бонуса при реализации кода "extra bonus"](https://github.com/Alex-nikiforova/java_hw_1.2_2/issues/1)

## Общие рекомендации

Внести коррективы в код "Extra bonus" с целью правильного расчета размера скидки клиента.