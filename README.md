# Проект: Обучение с учителем

<div class="Markdown base-markdown base-markdown_with-gallery markdown markdown_size_normal markdown_type_theory full-markdown"><h1>Описание проекта</h1><div class="paragraph">Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.</div><div class="paragraph">Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. </div><div class="paragraph">Постройте модель с предельно большим значением <em>F1</em>-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте <em>F1</em>-меру на тестовой выборке самостоятельно.</div><div class="paragraph">Дополнительно измеряйте <em>AUC-ROC</em>, сравнивайте её значение с <em>F1</em>-мерой.</div><h3>Инструкция по выполнению проекта</h3><ol start="1"><li>Загрузите и подготовьте данные. Поясните порядок действий.</li><li>Исследуйте баланс классов, обучите модель без учёта дисбаланса. Кратко опишите выводы.</li><li>Улучшите качество модели, учитывая дисбаланс классов. Обучите разные модели и найдите лучшую. Кратко опишите выводы.</li><li>Проведите финальное тестирование.</li></ol><h3>Описание данных</h3><div class="paragraph">Данные находятся в файле <code class="code-inline code-inline_theme_light">/datasets/Churn.csv</code> (англ. «отток клиентов»). <a href="https://code.s3.yandex.net/datasets/Churn.csv" target="_blank">Скачать датасет</a></div><div class="paragraph"><strong>Признаки</strong></div><ul><li><em>RowNumber —</em> индекс строки в данных</li><li><em>CustomerId</em> — уникальный идентификатор клиента</li><li><em>Surname —</em> фамилия</li><li><em>CreditScore —</em> кредитный рейтинг</li><li><em>Geography —</em> страна проживания</li><li><em>Gender —</em> пол</li><li><em>Age —</em> возраст</li><li><em>Tenure —</em> сколько лет человек является клиентом банка</li><li><em>Balance —</em> баланс на счёте</li><li><em>NumOfProducts —</em> количество продуктов банка, используемых клиентом</li><li><em>HasCrCard —</em> наличие кредитной карты</li><li><em>IsActiveMember —</em> активность клиента</li><li><em>EstimatedSalary —</em> предполагаемая зарплата</li></ul><div class="paragraph"><strong>Целевой признак</strong></div><ul><li><em>Exited</em> — факт ухода клиента</li></ul> 
