# Проект «Планировщик задач» в приложении Т-Банка

## 1. Цель проекта  
Создать удобный **планировщик задач**, который позволит пользователям управлять повседневными делами в одном приложении.  
Банк предложит **интегрированные сервисы** для выполнения задач и начислит **5% кэшбэка** за их использование.  

---

## 2. Метрики эффективности  

###  Качественные метрики:
- Удовлетворённость пользователей (**NPS**, **CSAT**, опросы).  
- Количество созданных задач.  
- Процент пользователей, воспользовавшихся рекомендациями банка.  

###  Количественные метрики:
- Количество пользователей, использующих планировщик.  
- Рост числа заказов через сервисы.  
- Увеличение выручки от продажи сервисов.  
- Общая сумма начисленного кэшбэка.  

---

## 3. Целевая аудитория (User Personas)  

###  Обычный пользователь (casual user)  
**Цель:** упростить управление повседневными делами.  
**Проблемы:**  
- Использование нескольких приложений для планирования.  
- Поиск подходящих сервисов.  
- Желание экономить.  
**Решение:**  
- Планировщик объединяет все задачи в одном месте.  
- Автоматические рекомендации сервисов.  
- 5% кэшбэк за использование сервисов банка.  

###  Бизнес-пользователь (business user)  
**Цель:** организовать рабочие задачи и бронирования.  
**Проблемы:**  
- Управление встречами и делами.  
- Контроль расходов компании.  
- Поиск корпоративных скидок.  
**Решение:**  
- Интеграция с партнёрскими сервисами.  
- Аналитика расходов и начисление кэшбэка.  

---

## 4. Функциональные требования  

###  Основные функции:  
- Добавление, редактирование, удаление задач.  
- Просмотр рекомендаций от банка.  
- Начисление и отображение кэшбэка.  
- Отметка задач как выполненных.  
- Прикрепление документов (например, билетов).  
- Отправка задач другим пользователям.  

###  Дополнительные функции:  
- Избранные задачи.  
- Интеграция с календарём.  
- Поделиться задачей в мессенджерах.  

---

## 5. Нефункциональные требования  
- **Безопасность**: шифрование данных задач.  
- **Производительность**: загрузка <1 сек.  
- **Масштабируемость**: поддержка 1M+ пользователей.  
- **Кроссплатформенность**: работа на iOS, Android, Web.  
- **Интеграция**: API-подключение к сервисам.  

---

## 6. Бизнес-процессы (User Flow)  

###  Создание задачи  
1. Пользователь выбирает категорию задачи (например, "Покупка билетов").  
2. Вводит детали (дата, место, комментарий).  
3. Получает рекомендации сервисов.  
4. Подтверждает заказ → получает кэшбэк.  

###  Выполнение задачи  
1. Пользователь завершает задачу.  
2. Система начисляет кэшбэк.  

###  Напоминания  
1. Автоматическое напоминание о задаче.  
2. Уведомление о начисленном кэшбэке.  

---

## 7. Статусная модель задач  

###  Статусы  
- Запланировано  
- Ожидание выполнения  
- Выполнено  
- Отменено  

###  Переходы  
- Запланировано → Выполнено  
- Запланировано → Ожидание выполнения  
- Запланировано → Отменено  
- Ожидание выполнения → Выполнено  

---

## 8. Прототип интерфейса  
- **Главный экран**: список задач и быстрые кнопки.  
- **Экран задачи**: описание, рекомендации, статус.  
- **Экран аналитики**: сумма потраченных денег, кэшбэк.  

---

## 9. Расстановка приоритетов (MVP)  

###  Этап 1 (MVP)  
- Добавление, редактирование, удаление задач.  
- Интеграция с каталогом сервисов.  
- Начисление 5% кэшбэка.  
- Напоминания.  

###  Этап 2  
- Закрепление документов.  
- Поделиться задачей.  
- Аналитика расходов.  

###  Этап 3  
- Интеграция с календарём.  
- Интеллектуальные рекомендации.  

---

## 10. Итог и следующие шаги  

###  Итог  
- Повышение вовлечённости пользователей в приложение.  
- Рост выручки от сервисов за счёт интеграции.  
- Гибкость планировщика для разных типов пользователей.  