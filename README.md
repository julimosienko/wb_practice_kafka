# wb_practice_kafka
1) поднять в docker-compose, из репозитория + sasl. выложить в свой git </br>
   ![image](https://github.com/julimosienko/wb_practice_kafka/assets/152617308/f83f0b6b-d9aa-4ebd-a713-959d02eecb7c)
2) создать топик, создаётся автоматически при записи данных</br>
![image](https://github.com/julimosienko/wb_practice_kafka/assets/152617308/eec8cf2d-5e1b-424c-b807-506740d0e626)</br>
3) написать python скрипт для заливки данных из небольшой таблицы клика (пегас) в топик кафка в формате json. Всю таблицу не нужно пушить, достаточно limit 100. выложить скрипт в свой git
   https://github.com/julimosienko/wb_practice_kafka/blob/main/to_kafka.py
4) программа Offset Explorer, просмотреть данные в топике. выложить скрины с результатами в свой git</br>
   ![image](https://github.com/julimosienko/wb_practice_kafka/assets/152617308/f91a0cb8-69af-475a-89f5-df7cfe0d7ef2)</br>
5) чтение из топика питоном. выложить в свой git</br>
   https://github.com/julimosienko/wb_practice_kafka/blob/main/topic_reader.py </br>
![image](https://github.com/julimosienko/wb_practice_kafka/assets/152617308/e94a4016-062b-482d-aba3-fec32ea51891)
