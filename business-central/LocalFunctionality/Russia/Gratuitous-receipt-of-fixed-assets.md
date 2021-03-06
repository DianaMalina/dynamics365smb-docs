# Безвозмездное поступление основных средств.

Учет безвозмездного получения ОС осуществляется в Журнале ГК для основных средств. 

1. На основании первичных документов в системе регистрируется операция в одном из разделов Журнала ГК для основных средств:  **Финансовый менеджмент > Основные Средства > Журналы > Журналы ГК для ОС**

2. Заполнить строки журнала:

| Поле                  | Описание                                                     |
| --------------------- | ------------------------------------------------------------ |
| Дата учета            | Введите дату операции. Этой же датой будут сформированы финансовые проводки и операции с ОС |
| Номер документа       | В зависимости от настроек раздела журнала, номер документа вводится вручную или заполняется автоматически |
| Тип документа         | Пусто                                                        |
| Тип счета             | Основное средство                                            |
| Номер счета           | Код ОС из Справочника основных средств                       |
| Код книги амортизации | Указывается код книги амортизации, в которой ведется учет приобретения ОС |
| Тип учета             | Стоимость приобретения                                       |
| Описание              | Необходимо ввести краткое описание хозяйственной операции. Данное описание будет отражаться во всех книгах операций и отчетности по операциям |
| Сумма                 | Введите сумму операции со знаком «+»                         |
| Тип баланс. счета     | Счет ГК                                                      |
| Номер баланс.счета    | Счет ГК для учета доходов будущих периодов в качестве безвозмездных поступлений |
| Код налоговой разницы | Код налоговой разницы при приобретении ОС.                   |

3. Учесть строки.

> :speech_balloon: **Примечание** 
>
> Поскольку ОС не приобреталось организацией, то у нее отсутствует право на применение амортизационной премии для такого ОС. Поэтому, если компания пользуется правом применения амортизационной премии, следует исключить стоимость приобретения ОС из расчетной базы для амортизационной премии. 

4. Если в настройках **Настройка налоговых регистров** выключена опция **Создавать приобр. ОС в НУ**, то оформленная таким образом стоимость ОС не отражается в книге амортизации по налоговому учету. Поэтому необходимо сформировать дополнительную проводку в **Журнале ОС**.

5. Заполнить строки **Журнала ОС**:

| Поле                  | Описание                                                     |
| --------------------- | ------------------------------------------------------------ |
| Дата учета            | Введите дату операции. Дата операция должна соответствовать дате принятия ОС к налоговому учету (чаще всего эта дата совпадает с датой ввода ОС в эксплуатацию) |
| Номер документа       | В зависимости от настроек раздела журнала, номер документа вводиться вручную или заполняется автоматически |
| Тип документа         | Пусто                                                        |
| Тип счета             | Основное  средство                                           |
| Номер ОС              | Код ОС из Справочника основных средств                       |
| Код книги амортизации | Указывается код книги амортизации, в которой ведется налоговый учет ОС |
| Тип учета             | Стоимость приобретения                                       |
| Описание              | Необходимо ввести краткое описание хозяйственной операции. Данное описание будет отражаться во всех книгах операций и отчетности по операциям |
| Сумма                 | Введите сумму операции со знаком "+"                         |

6. В результате учета строки **Журнала ОС** формируется операция приобретения в Книге операций по ОС для книги амортизации для налогового учета.

## См. также

[Основные средства](fixed-assets.md)
