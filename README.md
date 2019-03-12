# lesson_1
задание:
   Разобрать логи, хранящиеся в папке "logs/"

Описание задания:

   Каждый файл логов содержит замеры для всех устройств, произведенные в определенное время, отображаемое в названии файла.
   В любом файле данные для отдельного устройства хранятся в отдельной строке в формате:
        <время замеров>:<название устройства>:<полученое значение>
  
  В файлах могут быть представлены ошибочные данные, которые можно определить по содержанию в названии устройства слова "garbage".
  Так же в файлах могут содержаться пустые строки.
  
  Все Файлы содержат замеры для одних и тех же устройств, но данные в эти файлы заносятся по мере поступления повых значений. В связи с этим в каждом файле устройства располагаются в разном порядке.
  
  Необходимо предоставить пользователю возможность вывод всей информации, относящейся к выбранному пользователем устройству.
  
  Пример:
  >> show device elem_1
  >> elem_1:
               дата          - показания
    Thu 12 Mar 2019 11:25:00 - 401
    Thu 12 Mar 2019 12:25:00 - 432
    Thu 12 Mar 2019 13:25:00 - 123
    Thu 12 Mar 2019 14:25:00 - 111
    Thu 12 Mar 2019 15:25:00 - 123
    Thu 12 Mar 2019 16:25:00 - 111
    Thu 12 Mar 2019 17:25:00 - 123
    Thu 12 Mar 2019 18:25:00 - 111
    Thu 12 Mar 2019 19:25:00 - 111
    Thu 12 Mar 2019 20:25:00 - 123
    Thu 12 Mar 2019 21:25:00 - 111
    
    
   >> 
   
