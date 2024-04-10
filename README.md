# Инженерный хакатон ant-lab 2024

### Время и место

- Даты: с 19:00 10 апреля по 19:00 13 апреля 2024 года
- Место объявления задания и подведения итогов: МФТИ, Физтех
- Хакатон проводится в рамках "Фестиваля космонавтики 2024"

### Призы

- 1 место: 3D принтер
- 2 место: паяльная станция
- 3 место: три набора отвёрток

## Задача

### Дано

- Pico-10DOF-IMU, Датчик 10-степеней свободы на основе MPU9250 и LPS22HB для Raspberry Pi Pico: https://www.chipdip.ru/product/pico-10dof-imu?from=suggest_product
- Raspberry Pi Pico, Программируемый контроллер на базе RP2040 (32-Бит, ARM Cortex-M0+): https://www.chipdip.ru/product/raspberry-pi-pico-2

### Задача

Создать портативный измерительный прибор, который показывает абсолютные значения ускорения, угловой скорости и напряжённости магнитного поля.

### Обязательные требования

- прибор должен уметь начинать и заканчивать передачу данных по команде (подробнее о передаче данных в [инструкции](https://github.com/ant-lab-ru/hakathon-2024/blob/master/instruction/instruction_for_participant.pdf))
- крепёжные отверстия в приборе для фиксации на тестовой платформе

### Полезные материалы

- Python cкрипт для отработки приема-передачи данных в папке [COMReader](https://github.com/ant-lab-ru/hakathon-2024/tree/master/COMReader/COMReader_for_participant)

### Критерий оценки

- оцениваться будет среднеквадратичное отклонение всех трёх величин от показаний эталонного измерительного прибора
- победитель будет определён по наименьшему среднеквадратичному отклонению
