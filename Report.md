# Отчёт о тестировании Precision

## Краткое описание

10.08.2021 - 10.08.2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты: [Неверный итоговый бонус в приложении Precision при выполнении расчета в коде](https://github.com/arsi8012/Precision/issues/1#issue-964619434)

## Описание процесса тестирования

В процессе тестирования не использовались артефакты.

В качестве тестовых данных использовались [вводные данные задания 1.2.2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
<code>public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}</code>

Тестирование производилось в следующем окружении:
* Windows 7 32-bit
* JDK 11.0.11
* Intellij IDEA 2019.1.4