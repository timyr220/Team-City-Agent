# Team-City-Agent
Что изменилось:

    Добавлена проверка agent_name != 'AggregatedDevice' перед отправкой телеметрии и созданием тревоги. Это гарантирует, что данные online и offline отправляются на все устройства, кроме AggregatedDevice.

Этот код будет корректно обрабатывать устройства, отправляя на них телеметрию online и offline, исключая AggregatedDevice.
