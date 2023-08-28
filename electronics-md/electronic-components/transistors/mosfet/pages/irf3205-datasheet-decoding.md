# Расшифровка даташита на примере полевого транзистора IRF3205
[На главную](../../../../../README.md../../../README.md)
[MOSFET](../mosfet.md)
[Транзисторы](../../transistors.md)
___
## Страница 1
![irf3205-datasheet-page1-img](../images/irf3205-datasheet-decoding/datasheet-pages/irf3205-datasheet-page1-img.jpg)

### Расшифровка страницы 1
__IRF3205__ - название транзистора.
- __HEXFET__
    - В семействе полевых транзисторов есть отдельная группа мощных полупроводниковых приборов называемых __HEXFET__. Их принцип работы основан на весьма оригинальном техническом решении. Их структура представляет собой несколько тысяч МОП ячеек включенных параллельно.

    - Ячеистые структуры образуют шестиугольник. Из-за шестиугольной или по-другому гексагональной структуры данный тип мощных МОП-транзисторов и называют __HEXFET__. Первые три буквы этой аббревиатуры взяты от английского слова __hexagonal__ – «__гексагональный__».

__Power MOSFET__ - силовой MOSFET (полевой) транзистор.

#### Схема транзистора
![irf3205-transistor-scheme.jpg](../images/irf3205-datasheet-decoding/datasheet-pages/page-1-elements/irf3205-transistor-scheme.jpg)

- Где
    - G - Gate - Затвор
    - D - Drain - Сток
    - S - Source - Исток

##### Обозначение перехода, структуры транзистора
![irf3205-p-n-img](../images/irf3205-datasheet-decoding/datasheet-pages/page-1-elements/irf3205-p-n-img.jpg)
- Стрелка указыывает направление P-N перехода. В случае транзистора IRF3205, транзистор имеет структуру P-N-P.

##### Диод в составе транзистора
![irf3205-diode-img.jpg](../images/irf3205-datasheet-decoding/datasheet-pages/page-1-elements/irf3205-diode-img.jpg)
- Выделенное обозначение, является обозначением диода, который находится внутри корпуса транзистора. На схеме видно направление и подключение диода.

##### Изолированный затвор
![irf3205-Insulated-gate-img.jpg](../images/irf3205-datasheet-decoding/datasheet-pages/page-1-elements/irf3205-insulated-gate-img.jpg)
- Выделенная область, является обозначением изолированного затвора.

#### Основные параметры транзистора
![irf3205-main-characteristics-img](../images/irf3205-datasheet-decoding/datasheet-pages/page-1-elements/irf3205-main-characteristics-img.jpg)
- __VDSS__ (55V) - напряжение между стоком __D__ и истоком __S__.
- __RDS(on)__ (8.0mΩ) - сопротивление между стоком __D__ и истоком __S__. Чем сопротивление меьше, тем меньше будет нагреваться транзистор в импульсных и переключающих схемах.
- __ID__ (110A) - ток стока. Это рабочий ток транзистора.

## Полезные ссылки. Источники
- [Параметры MOSFET транзисторов](https://go-radio.ru/parametri-mosfet-transistorov.html)