# Инвентаризация основных средств

​				 

Функция инвентаризации основных средств позволяет: 

- выполнять инвентаризацию основных средств в соответствии с требованиями законодательства;
- создавать электронные инвентарные списки основных средств, подлежащих инвентаризации, с учетом расчетных количеств и сумм;
- разделять инвентарные списки по физическому местоположению основных средств (по коду местоположения основного средства);
- фильтровать инвентарные списки по другим аналитикам (например, по подотчетнику);
- печатать формы с инвентарными списками, в которых показаны все основные средства, прошедшие инвентаризацию, а также со списками, в которых перечислены основные средства с разницей только в количестве или сумме;
- печатать стандартные формы основных средств.

 

## Инвентарные списки основных средств

Для проведения инвентаризации необходимо создать инвентарные списки основных средств с расчетными количествами и суммами. Такие списки разделены по аналитике: например, по физическому местоположению или сотруднику, ответственному за определенные основные средства.

Можно создать специальные шаблоны в окне **Журнал учета основных средств**. 

Ниже показано, как создать список основных средств, подлежащих инвентаризации.

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Журналы основных средств**, а затем выберите связанную ссылку.

2. Выберите действие **Расчет ОС**. Откроется форма запроса отчета для создания инвентарных списков основных средств.

3. На экспресс-вкладке **Основные средства** отфильтруйте основные средства.

   

   > :speech_balloon: Примечание
   >
   > Фильтрацию можно выполнять по любому параметру из карточки основного средства, например по местоположению основного средства или по подотчетнику.

 

Параметры, перечисленные в таблице ниже, можно найти на экспресс-вкладке **Параметры**.

 

| Параметр                                          | Описанием                                                    |
| :------------------------------------------------ | :----------------------------------------------------------- |
| **Шаблон журнала ОС**                             | Выберите шаблон журнала основных средств, который будет использоваться для работы со списком основных средств в ходе инвентаризации. По умолчанию указывается шаблон журнала основных средств. |
| **Код Книги Амортизации**                         | Выберите книгу амортизации с записями, для которых будет выполнен расчет по количеству и сумме. |
| **Номер начального документа**                    | Укажите номер документа, применявшийся при создании строк в журнале основных средств. |
| **Дата Документа**                                | Укажите дату документа.                                      |
| **Дата учета**                                    | Укажите дату учета. Количества и суммы рассчитываются на эту дату. В поле **Дата Учета** тоже заносится это значение. |
| **Показывать ОС с нулевой остаточной стоимостью** | Установите этот флажок, чтобы создать в журнале основных средств строки для ОС с нулевой остаточной стоимостью. |

Отчет создает один раздел в шаблоне журнала основных средств для каждого местоположения основных средств, отфильтрованного в форме запроса. Для каждого отфильтрованного основного средства создается одна строка журнала в разделе, соответствующем местоположению этого ОС. Раздел журнала создается для основных средств в каждом местоположении ОС. 

Ниже показано, как начать инвентаризацию по местоположению основных средств. 

1. Выберите раздел, соответствующий местоположению основных средств, а затем выберите **ОК**.

   > :speech_balloon: Примечание
   >
   > Можно просмотреть строки основных средств, отфильтрованные в отчете, и строки для данного местоположения ОС.

2. Расположите столбцы журнала основных средств таким образом, чтобы можно было просматривать расчетные и фактические количества и суммы. Они указаны в следующих полях:

   - **Факт. Кол-во**;
   - **Расчет. Кол-во**;
   - **Факт. Сумма**;
   - **Расчет. Сумма**.

 

> :speech_balloon: Примечание
>
> Значение суммы — это остаточная стоимость основного средства.

 

 

## См. также

[ОС: местоположения и ответственные сотрудники](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/fixed-asset-locations-and-employees.md)
