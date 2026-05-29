<h1 align="center"> Приветствую! </h1>

<p align="center">
  Java Junior Developer 
</p>

---

###  О себе
- Образование:РТУ МИРЭА | Бизнес-аналитик.  
- Карьера: Инженер ПТО (1 категории).
- Два года изучаю Java и backend-разработку.  
- Цель — развиваться как Java Backend Developer.

---

###  Технологический стек
**Языки**
- Java
- SQL

**Фреймворки**
- Spring Boot
- Spring Security
- Spring Data JPA
- Spring MVC
- Spring JDBC

**Базы данных**
- PostgreSQL
- H2
- Flyway

**Очереди и интеграции**
- Kafka
- REST API

**Тестирование**
- JUnit
- Mockito

**Инструменты и инфраструктура**
- Docker
- Docker Compose
- Maven
- Gradle
- Git
- Apache POI 
- Tabula 
- Jsoup 
- OpenCSV 

**Метрики и мониторинг**
- Prometheus
- Grafana

**Прочее**
- Lombok
- MapStruct

---

###  Pet-проекты

#### 🔹[Репозиторий проекта] [ Распределённая система уведомлений](https://github.com/IvanMorozov2000/project-bot-api/tree/master)
https://github.com/IoanMor/project-bot-api/tree/master (дублирующая ссылка)

**> Цель: Проектирование архитектуры, настройка Kafka, реализация логики подписок, интеграция с Telegram Bot API, покрытие тестами.**

Проект состоит из двух микросервисов:

> **scrapper**  
  - Отслеживает изменения по подпискам (StackOverflow).
  - Мониторинг цен акций российских компаний (МосБиржа API).   
  - Взаимодействие c микросервисом (telegram-bot) через Kafka (продюсер/консьюмер).  
 
> **telegram-bot**  
  - Принимает команды от пользователей и отправляет уведомления.
  - Взаимодействие с микросервисом (scrapper) через Kafka (продюсер/консьюмер).  
  
> Общее:
 - Покрытие тестами.
 - Использование метрик, подключение grafana и prometeus.


#### 🔹[Репозиторий проекта] [ File Parser ](https://github.com/IoanMor/parseFilesFromPTO/tree/main)

(https://github.com/IoanMor/parseFilesFromPTO/tree/main) (дублирующая ссылка)

**> Цель: Создание инструмента для пакетного парсинга документов и автоматической генерации отчётов, чтобы ускорить рутинную ручную обработку файлов.**

Проект представляет собой консольное приложение на Spring Boot:

*   Сканирует указанную папку и автоматически обрабатывает файлы форматов **HTML, Excel (XLS/XLSX) и PDF**.
*   Извлекает структурированные данные из документов с помощью **Jsoup, Apache POI и Tabula**.
*   Выполняет необходимые подсчёты и агрегирует результаты.
*   Формирует единый итоговый файл отчёта в формате **CSV**.
*   Реализован как монолит, не требует установки Maven у пользователя (запуск через `.bat`).

**Технологический стек:**

*   **Java 17**, **Spring Boot**.
*   **Apache POI**, **Tabula**, **Jsoup** для парсинга файлов.
*   **OpenCSV** для генерации отчётов.
*   **Lombok**, **SLFJ** для логирования.

   
#### 🔹[Репозиторий проекта] [ Bank Cards Application](https://github.com/IvanMorozov2000/bank-cards-app](https://github.com/IoanMor/bankcard))
(https://github.com/IoanMor/bankcard) (дублирующая ссылка)

**> Цель: Разработка монолитного приложения для управления банковскими картами с безопасной аутентификацией, переводами между картами и хранением данных пользователей.  

**Функциональность проекта:**  
- Регистрация и авторизация пользователей с использованием Spring Security.  
- Создание и управление банковскими картами.  
- Переводы между картами с проверкой баланса и валидацией данных.  
- Безопасная работа с данными пользователей.  
- Покрытие юнит- и интеграционными тестами.  

**Технологический стек:**  
- Java 17+, Spring Boot, Spring MVC, Spring Security, Spring Data JPA.  
- PostgreSQL (основная БД), H2 (тестовая).  
- JUnit 5, Mockito для тестирования.  

---

### 📫 Контакты
- Email: ivan-morozov-yr@mail.ru  
- Telegram: @LordIoan (https://t.me/LordIoan)  

---





