<h1 align="center">Шаблон описания архитектуры программного обеспечения</h1>

> ### Шаблон поможет:
>-	собрать и систематизировать информацию об архитектуре, основных функциях и качественных характеристиках информационной системы; 
>-	спроектировать решение с учетом требований заинтересованных лиц и обеспечить функциональную полноту и надежность системы; 
>-	снизить вероятность сбоев, нарушений безопасности и рисков незапланированных затрат при развитии и эволюции системы. 

# Содержание

#### Введение
- ##### Цель и сфера применения
- ##### Аудитория
- ##### Статус
- ##### Архитектурный подход к проектированию
#### Глоссарий
#### Заинтересованные стороны системы и требования
- ##### Заинтересованные стороны
- ##### Обзор требований
- ##### Сценарии системы
   -  ###### Функциональные сценарии
   -  ###### Нефункциональные сценарии
#### Архитектурные факторы
 - ##### Цели
 - ##### Ограничения
 - ##### Архитектурные принципы
#### Архитектурные представления
 - ##### Представление контекста
     -  ###### Контекстная диаграмма
     -  ###### Сценарии взаимодействия
 - ##### Функциональное представление
     -  ###### Функциональные элементы
     -  ###### Функциональные сценарии
     -  ###### Общесистемная обработка событий
 - ##### Представления информации
     -  ###### Структура данных
     -  ###### Потоки данных
     -  ###### Право владения данными
     -  ###### Жизненный цикл информации
     -  ###### Своевременность, латентность и возраст данных
     -  ###### Архив и хранение информации
 - ##### Параллельное представление
     -  ###### Параллельная модель
     -  ###### Модель состояния
 - ##### Представление развертывания
     -  ###### Модель платформы во время исполнения (runtime)
     -  ###### Программные зависимости
     -  ###### Сетевая модель
 - ##### Представление разработки
     -  ###### Представление модуля
     -  ###### Общее проектирование
     -  ###### Стандарты проектирования, кодирования и тестирования
     -  ###### Организация кодирования
 - ##### Операционное представление
     -  ###### Установка и миграция
     -  ###### Управление эксплуатационной конфигурацией
     -  ###### Системное администрирование
     -  ###### Предоставление поддержки
#### Качества системы
 - ##### Производительность и масштабируемость
 - ##### Безопасность
 - ##### Доступность и устойчивость
 - ##### Эволюция
-  ##### Другие качества
     -  ###### Доступность
     -  ###### Интернационализация
     -  ###### Место расположения
     -  ###### Нормативные требования
     -  ###### Удобство использования

#### Введение
- ##### Цель и сфера применения
Объясните цель и объем документа.
Рекомендуется избегать представления большого количества материалов, доступных в другом месте, также может быть полезно выполнить некоторые или все из следующих действий:
1. Обобщите контекст, цели и задачи проекта
2. Подтвердите объем и исключения
3. Представьте обзор целей и драйверов, требований и т.д.
4. Запишите важные принятые решения и их обоснование
5. Представьте альтернативы и причины их отклонения


