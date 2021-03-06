# Практическое руководство. Настройка договоров с клиентами и поставщиками

Функция соглашений с поставщиками и клиентами включает в себя следующие компоненты:

- список соглашений для клиентов и поставщиков;
- карточка соглашения, в которой хранятся все нужные сведения о соглашениях;
- синхронизация между соглашениями и измерениями, которая обеспечивает использование существующих отчетов и анализов измерений. 

Приведенная ниже процедура показывает, как настроить договор для клиента, но процедура для поставщика аналогична и начинается из окна **Покупки и расчеты с кредиторами**.

 

## Настройка договора

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Настройка модуля "Продажи"**, затем выберите связанную ссылку.

2. Чтобы настроить договор, на экспресс-вкладке **Измерения** и экспресс-вкладках **Нумерация** заполните поля, перечисленные в таблице ниже.

   | Поле                                    | Описанием                                                    |
   | :-------------------------------------- | :----------------------------------------------------------- |
   | **Измерение Договор**                   | Выберите код измерения для соглашений.                       |
   | **Синхр. измерения договоров**          | Установите этот флажок, чтобы создать код значения измерения после создания соглашения. Коды значений измерений равны кодам соглашений. |
   | **Серия номеров для договоров клиента** | Выберите серию номеров для договора с клиентом.              |

 

## Создание договора с клиентом или поставщиком 

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Клиенты**, а затем выберите связанную ссылку.

2. Выберите клиента из списка и выберите действие **Правка**.

3. Разверните экспресс-вкладку **Договоры** и измените поле **Учет договоров**.

4. Выберите действие **Договора**. В окне **Договора клиентов** выберите действие **Создать**.

5. В карточке **договора с клиентом или поставщиком** заполните поля, перечисленные в таблице ниже.

   | Поле                       | Описанием                                                    |
   | :------------------------- | :----------------------------------------------------------- |
   | **Код**                    | Введите код договора. Введите до 20 буквенно-цифровых знаков. По умолчанию код создается из серии номеров, настроенной в форме "Настройка ГК". |
   | **Описание**               | Введите описание договора. Введите до 250 буквенно-цифровых знаков. |
   | **Номер источника**        | Выберите это поле, чтобы видеть номер поставщика или клиента, для которого создается данное соглашение. |
   | **Источник Название**      | Введите название поставщика или клиента, для которого создается данное соглашение. Название источника автоматически извлекается из таблицы "Поставщик" или "Клиент". |
   | **Код Значения Измерения** | Введите код значения измерения. Укажите функции соглашения и измерения. Код значения измерения равен коду договора, если выбрано поле **Синхр. измерения договоров** в окне **Настройка модуля "Продажи"**. |
   | **Дата начала**            | Введите начальную дату периода, в течение которого предполагается использовать данное соглашение. |
   | **Дата окончания**         | Введите дату окончания срока действия данного соглашения.    |
   | **Заблокировано**          | Установите этот флажок, чтобы избежать учета операций в соглашении. При попытке создания документа с заблокированным соглашением будет выведено сообщение об ошибке. Обычно соглашение блокируется после даты окончания срока действия. |

 

На вкладке **Навигатор** можно найти следующие функции: 

- Список — показать список соглашений с клиентом или поставщиком.
- Книга операций — показать операции книги для клиента или поставщика, учтенные с данным кодом соглашения. 

Соглашения полностью синхронизированы с измерениями. Можно учесть транзакции и выбрать код значения измерения соответствующего соглашения из списка соглашений.

 

## См. также

[Отчеты по расчетам с клиентами (Россия)](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/russian-receivables-reports.md)

[Отчеты по платежам (Россия)](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/russian-payables-reports.md)
