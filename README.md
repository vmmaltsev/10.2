# Домашнее задание к занятию 10.2 «Кластеризация» - `Мальцев Виктор`

---

### Задание 1

`В чём различие между SMP- и MPP-системами?

Приведите ответ в свободной форме.`

Ответ:
SMP системы имеют общую физическую память, которая делится между всеми процессорами.
В MPP системах физическая память делится между процессорами.

---

### Задание 2

`В чём отличие сильно связанных и слабо связанных систем?

Приведите ответ в свободной форме.`

Ответ:
В сильно связанных системах процессоры имеют общие модули памяти, в слабо связанных системах каждый процессор
имеет свой собственный модуль памяти.


---

### Задание 3

`Какие преимущества отличают кластерные системы от обычных серверов?

Приведите ответ в свободной форме.`

Ответ:
Высокая доступность, отказоустояивость, балансировка нагрузки, увеличенные вычеслительные мощности.


---

### Задание 4

`Приведите примеры типов современных кластерных систем.

Приведите ответ в свободной форме.`

Ответ:
Кластеры высокой доступности.
Кластеры распределения нагрузки (Network Load Balancing, NLB).
Вычислительные кластеры.
Системы распределенных вычислений (grid)

---

### Задание 5

`Где используют сервис Kafka, rabitMQ?

Приведите ответ в свободной форме.`

Ответ:
Kafka лучше всего подходит для потоковой передачи от А к Б без сложной маршрутизации, 
но с максимальной пропускной способностью. Инструмент 
справляется с event sourcing, потоковой обработкой и моделированием изменений 
в системе в качестве последовательности событий. 
Кафку также можно использовать для обработки данных при многоэтапной конвейерной обработке.

RabbitMQ идеально подходит для веб-серверов, которым требуется быстрый запрос-ответ. 
Этот инструмент распределяет нагрузку между рабочими приложениями при высокой нагрузке 
и может обрабатывать фоновые задания или длительные задачи, 
такие как преобразование PDF, сканирование файлов или масштабирование изображений.
