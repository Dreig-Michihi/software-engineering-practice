#Диаграмма прецедентов:
- Описывает функциональное назначение системы, т.е. то, что система будет делать в процессе совего функционирования;
- Является исходной концептуальной моделью системы в процессе её проектирования и разработки.

#Основные компоненты:
- актёры;
- прецеденты (use case);
- отношения

#Виды отношений:
- ассоциативное отношение (assotiation relationship)
- отношение расширения (extend relationship)
- отношение обобщения (generalization relationship)
- отношение включения (include relationship)

#Отношение ассоциации:
- Отношение между вариантом использования и актёром, отражающее связь между ними.
- Оно устанавливает, какую конкретную роль играет актёр при взаимодействии с экземпляром варианта использования.
(Обычная стрелка от актёра к прецеденту)

#Отношение расширения:
- Определяет взаимосвязь базового варианта использования с некоторым другим вариантом использования, функциональное поведение которого задействуется базовым не всегда, а только при выполнении некоторых дополнительных условий.
(Сдать зачёт)<------<<extend>>------(Взять индивидуальную ведомость)
(Стрелка указывает на базовый вариант использования)

#Отношение обобщения:
- Служит для указания того факта. что некоторый вариант использования А может быть обобщён до варианта использования Б (или актёр А может быть обобщён до актёра Б).

Показывается полой стрелочкой, идущей от ребёнка к родителю, т.е. от варианта использования или актёра к их обобщению.

Пример:
(Сдать зачёт по системному моделированию)------|>(Сдать зачёт по предмету)
(Студент второго курса)--------------|>(Студент)

#Отношение включения
- Указывает, что некоторое заданное поведение для одного варианта использования включается в качестве составного компонента в последовательность поведения другого варианта использования.

Показывает обычной стрелочкой с пунктирной линией и подписью <<include>>.

(Сдать все лабораторные работы)--<<include>>-->(Получить автомат по программной инженерии)<--<<include>>--(Сдать на отлично все тесты и контрольную)

#Заключение
Диаграмма прецедентов (use case diagram, вариантов использования) в UML - диаграмма, отражающая отношения между актёрами и прецедентами и являющаяся составной частью модели прецедентов, позволяющей описать ситсему на концептуальном уровне.