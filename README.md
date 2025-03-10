# FullHouse
Наш проект - система бонусов студентам за успехи в учебе. Студенты будут получать баллы за успеваемость во время учебного процесса или участие во внеучебной активности и смогут тратить эти баллы на предложенные в нашей системе бонусы. Бонусами являются купоны, акции, промокоды и т.д. от компаний-партнеров.

### Участники
- Аксенов Иван - главный программист
- Костина Полина - главный дизайнер
- Кочетков Кирилл - программист
- Бусыгин Андрей - тимлид
- Горюнов Александр - программист
- Соколова Арина - дизайнер
- Аминов Никита - программист

### Бизнес-цели
- Привлечь новых партнеров для учебного заведения
- Привлечь абитуриентов в учебное заведение

### Бизнес-процессы
**Начисление бонусов за успеваемость.** 
1. Каждый раз при наступлении КТ с сайта вуза получается успеваемость студентов
2. Когда получены данные об успеваемости баллы рейтинга конвертируются в бонусы системы.
$k_{усп} = \frac{\text{Баллы за КТ} - \text{Баллы за предыдущую КТ}}{\text{Максимальные баллы за КТ} - \text{Максимальные баллы за предыдущую КТ}}$
$100 * k_{усп}$

### Заинтересованные лица
| Заинтересованное лицо | Потребности, интересы | Задачи |
| --- | --- | --- |
| Студент | Заинтересован в получении бонусов за хорошую успеваемость, и последующей их трате на представленный в приложении ассортимент | Поддерживать хорошую успеваемость в вузе |
| Преподаватель | Мотивировать студентов к более активному участию в учебном процессе и внеучебных активностях | Добавление задач для студентов через приложение |
| Компания-партнер | Реклама своей компании, продукции и предоставляемых услуг | Партнерское взаимодействие с вузом и предоставление предложений для внутреннего магазина приложения |
| Администрация вуза | Мотивация студентов к активному участию в учебном процессе, привлечение компаний-партнеров и как следствие повышение рейтинга вуза | Предоставление доступа к данным системы рейтинга студентов |

### Функции и свойства
1. Начисление бонусов за успеваемость
2. Использование бонусов на покупки во внутреннем магазине
3. Сбор статистики об обороте бонусов в системе
4. Предоставление информации о мероприятиях в вузе
5. Составление таблицы лидеров среди студентов по успеваемости
6. Создание преподавателями заданий для студентов
7. Обновление ассортимента внутреннего магазина
8. Предоставление информации об успеваемости студента
9. Ведение учета посещаемости меропрятий вуза студентом
10. Авторизация студента по студенческому билету и паролю

### Качественные характеристики
1. Удобство использования
2. Безопасность
3. Расширяемость
4. Надежность
5. Качество технической поддержки

### Диаграмма вариантов использования
![alt text](resources/images/Iteration2_UseCase.png)