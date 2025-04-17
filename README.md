# Подсистема Инвентаризации Оборудования в 1С

## Цель
Разработка простой подсистемы инвентаризации оборудования в среде 1С (платформа 8.3, конфигуратор).

## Основные объекты

1. **Справочник «Оборудование»**
   - Поля:
     - Наименование
     - Инвентарный номер
     - Ответственный
     - Местоположение

2. **Документ «Инвентаризация»**
   - Поля:
     - Дата
     - Список оборудования
     - Состояние

3. **Отчет «Оборудование по местоположению»**

## Интерфейс
- Стандартные формы для работы с объектами.
- Кнопка для запуска отчета.

## Отчет
- Описание созданных объектов конфигурации.
- Скриншоты форм.
- Сценарий: как внести данные и получить отчет.

## Установка конфигурации

1. **Открыть конфигуратор 1С**.
2. **Создать новую конфигурацию** или открыть существующую.
3. **Скопировать код конфигурации** из файла `InventorySystem.epf` в конфигуратор.
4. **Сохранить и загрузить конфигурацию**.
5. **Запустить 1С в режиме предприятия**.

## Сценарий использования

1. **Внесение данных**:
   - Открыть справочник «Оборудование».
   - Нажать кнопку «Создать» и заполнить поля (Наименование, Инвентарный номер, Ответственный, Местоположение).
   - Сохранить запись.

2. **Создание инвентаризации**:
   - Открыть документ «Инвентаризация».
   - Заполнить дату и выбрать оборудование из справочника.
   - Сохранить документ.

3. **Получение отчета**:
   - Нажать кнопку для запуска отчета «Оборудование по местоположению».
   - Просмотреть отчет.

