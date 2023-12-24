# Database_Administration_for_DevOps_Engineers_HW_5

Задание 1.

- Dockerfile                     
```
ds
```                       
- docker hub                  
  ![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/11.png)     

Задание 2.

- создание индексов
        
![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/21.png)                                   
![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/22.png)     

- состояние кластера
  
![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/23.png)    

- кластер в состояние yellow так как часть шардов в состояние assigned а часть в unassigned

![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/24.png)

Задание 3.

- внес изменения в Dockerfile               
создание каталога  /opt/elasticsearch-7.14.0/snapshots             
внесем изменение в elasticsearch.yml добавив path.repo: /opt/elasticsearch-7.14.0/snapshot            

![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/31.png)     

- Создание индекса test
  
![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/32.png)

![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/index%20test.png)

- список файлов
  
![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/33.png)

- удаление индекс test и создание test-2
  
![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/index%20test-2.png)

- вышла ошибка при свостановление снапшота из за чего сделал его заного и удалил после индекс test-2 создал test-3 и востановил
  
![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/index%20test-3.png)

![](https://github.com/dAmp1r/Database_Administration_for_DevOps_Engineers_HW_5/blob/main/34.png)
