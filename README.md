# Инженерный хакатон ant-lab 2024

### Время и место

- Даты: с 20:00 10 апреля по 20:00 13 апреля 2024 года
- Место объявления задания и подведения итогов: МФТИ, Физтех
- Хакатон проводится в рамках "Фестиваля космонавтики 2024"

### Призы

- 1 место: 3D принтер
- 2 место: паяльник
- 3 место: набор отвёрток

## Задача

### Дано

- Pico-10DOF-IMU, Датчик 10-степеней свободы на основе MPU9250 и LPS22HB для Raspberry Pi Pico: https://www.chipdip.ru/product/pico-10dof-imu
- Raspberry Pi Pico, Программируемый контроллер на базе RP2040 (32-Бит, ARM Cortex-M0+): https://www.chipdip.ru/product/raspberry-pi-pico-2

### Задача

Создать измерительный прибор, который показывает абсолютные значения ускорения, угловой скорости и магнитной индукци.

### Обязательные требования

- прибор должен уметь начинать и заканчивать передачу данных по команде (подробнее о передаче данных в [инструкции](https://github.com/ant-lab-ru/hakathon-2024/blob/master/instruction/instruction_for_participant.pdf))
- прибор должен иметь крепёжные отверстия для фиксации на тестовой платформе в соответствии с [чертежом платформы](https://github.com/ant-lab-ru/hakathon-2024/blob/master/mechanical/device_mounting.pdf)

### Рекомендации

- прибор может питаться по кабелю USB от компьюетра или внешнего аккумулятора
- общение с прибором может вестись по тому же каюелю USB, по которому осуществляется питание

### Полезные материалы

- Python cкрипт для отработки приема-передачи данных в папке [COMReader](https://github.com/ant-lab-ru/hakathon-2024/tree/master/COMReader/COMReader_for_participant)

### Эталонный измерительный прибор

В качестве эталонного измерительного прибора на этапе оценки точности продуктов будет использоваться [цифровой датчик магнитного курса «ЦДМК-1»](https://integral-group.pro/products/magnetometers/cdmk-1/), разработки ООО "Интеграл"

### Критерии оценки

- основной критерий оценки - среднеквадратичное отклонение всех трёх величин от показаний эталонного измерительного прибора (оценка будет проходить на Физтех.Фабрике 13 апреля с 12:00 до 18:00 в порядке готовности приборов)
- по результатам оценки отклонений приборов будут распределены предварительные места команд и порядок выступлений на Финале (презентация не больше, чем на 4 минуты, строго)
- результаты выступлений могут повлиять на предварительное распределение мест, самый точный прибор со слабой презентацией может проиграть среднему прибору с блестящим выступлением (окончательно тройку победителей определяет жюри по точности прибора, результатам общения с командами во время оценки точности и по впечатлениям от готовго прибора и его презентации)
