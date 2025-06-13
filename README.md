# **"Kolobok"**

Это увлекательный 3D шутер-платформер, вдохновлённый игрой "My Friend Pedro", с видом сбоку в стилистике "Киберпанка", который перенесет игроков в мир русской народной сказки в новом исполнении. В этой игре вам предстоит взять на себя роль Колобка, который, сбежав от бабушки и дедушки, отправляется в захватывающее путешествие по городу будущего, полное опасностей и ВЕСЕЛЬЯ.

## Содержание 

1. [Функционал к реализации](#функционал-проекта)
2. [Реализованный функционал](#реализованный-функционал)
3. [Использованный инструментарий](#использованный-инструментарий)
4. [Правила обновления](#правила-обновления)
5. [Техническое задание](#техническое-задание)

## Функционал проекта
- [x] Передвижение персонажа по уровню (перекатывание по плоскости как колесо)
- [x] Стрельба персонажа (projectile с отдачей и стрельбой из определенной точки персонажа)
- [x] Противники и их ИИ (патрулирование и стрельба)
- [x] Карта и окружение (уровни, декорации)
- [x] Графика (свет, постобработка, текстуры)
- [x] Звук (музыка, звуковые эффекты, обработка)
- [x] Система уровней и игровые уровни (сцены, локации)

**[Референсы](https://docs.google.com/document/d/1YPO16_oO2tin3Nsrrw6C98iEF-mBPWFx7zZ9FfArYOs/edit?usp=sharing)**

---

## Реализованный функционал

### Передвижение персонажа

Персонаж движется как колесо - влево и вправо. Есть возможность прыгать с места и со стены на стену при помощи ракет. 

*(WASD/Левый джойстик геймпада)*

### Стрельба

Персонаж выпускает два вида ракет - медленную дуговой троекторией и быструю по прямой.

*(ЛКМ/Правый триггер геймпада/Нижняя функциональная кнопка геймпада)*

---

Вращение пушки на 360 градусов вокруг персонажа.

*(Мышь/Правый джойстик геймпада)*

### Противники

Противники патрулируют зону от стены до стены (столкновение со стеной или любым другим объектом, преграждающим дорогу, разварачивает противника в противоположную сторону)

## Использованный инструментарий

* **Unreal Engine**
  
> Я выбрал **Unreal Engine**, потому что он предлагает больший инструментарий для создания красивых реалистичных миров, чем Unity и для того, чтобы научиться чему-то новому имея опыт в **Unity**

* **FL Studio**
  
> Я выбрал **FL Studio**, потому что он имеет интуитивную систему паттернов и гибкость в создании музыки, что делает его удобным лично для меня.

* **JetBrains Rider**
  
> Я выбрал **JetBrains Rider**, потому что он обеспечивает высокую производительность и умные инструменты для редактирования, исправления и оптимизации кода и хорошо зарекомендовал себя в сфере разработки игр.

* **C++**
  
> **C++** является основным языком программирования для разработки игр в Unreal Engine.

## Правила обновления 

* Не обновлять по приколу
* Не обновлять без значительных изменений (либо в случае исправления критических багов)

## Техническое задание
### Общие сведения:
* Наименование системы: "Kolobok".
* Заказчик: Top | Компьютерная академия
* Разработчик: PillDevTeam ([@ineedmypills](https://github.com/ineedmypills), [@TlyTla](https://github.com/TlyTla))
* Основание для разработки: Студенческий проект

### Назначение и цели создания системы:
* Назначение: Удовольвствие и чистый кайф
* Цели: Понравиться пользователю

### Характеристики объекта автоматизации:
* Игра будет представлять собой шутер-платформер с видом сбоку, где игрок управляет колобком, избегая ловушек и взаимодействуя с различными персонажами и объектами.

### Требования к системе:
* Функциональные требования: [Реализованный функционал](#реализованный-функционал)
* Нефункциональные требования: Поддержка различных платформ (ПК, мобильные устройства). Высокая производительность и стабильность работы.

### Состав и содержание работ по созданию системы:
[Функционал к реализации](#функционал-проекта)

### Требования к документированию:
* -

### Порядок контроля и приёмки системы:
* Проведение тестирования на различных этапах разработки.
* Определение критериев успешности игры, таких как отзывчивость управления и интересность игрового процесса.
