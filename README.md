# date_time

📆 from datetime import datetime 
date = datetime.now()
    print(date)🌡
            💡


## Outro jeito com mais detalhes:

📆from datetime import datetime
data = datetime(2022,5,10)
n = data.strftime("%y, %m, %d")
     print(n)
        💡


 ## EXPLICANDO PASSO A PASSO :

 import datatime 

data = datatime.now()

print(data)

hora neste momento e datas juntas. 


método strftime -- método de formatação de data em string
Esse temo é formatado em string em Texto


data_hora  =  datetime(2022, 05, 11)
data_hora.strsftime(data_hora)




1. Importando o módulo datetime:
   Você pode começar importando o módulo `datetime` da seguinte maneira:

  
   import datetime
 

2. Obtendo a data e hora atual:
   Para obter a data e hora atual, você pode usar a classe `datetime`:

  
   current_datetime = datetime.datetime.now()
   print(current_datetime)
  

3. Trabalhando com datas:
   Você pode criar objetos de data usando a classe `date`:

  
   date_obj = datetime.date(2023, 9, 27)
   print(date_obj)
   

4. Trabalhando com horários:
   Para criar objetos de horário, use a classe `time`:

   time_obj = datetime.time(14, 30, 0)  # Hora:minuto:segundo
   print(time_obj)
 

5. Operações com datas e horários:
   Você pode realizar várias operações com datas e horários, como adição, subtração e cálculos de intervalo de tempo:

   
   from datetime import datetime, timedelta

   today = datetime.now()
   yesterday = today - timedelta(days=1)
   tomorrow = today + timedelta(days=1)

   time_difference = tomorrow - yesterday
   print(time_difference)
   

6. Formatação de datas e horários:
   Você pode formatar datas e horários em uma string usando o método `strftime`:
    
   AS % SÃO AS DIRETIVAS

   EXISTEM DEZENAS:
   VERIFIQUE NO FINAL DA PÁGINA ALGUMAS OUTRAS DIRETIVAS
documentação: 

https://docs.python.org/pt-br/3/library/datetime.html   
 
   formatted_date = today.strftime("%Y-%m-%d")
   formatted_time = today.strftime("%H:%M:%S")
   print(formatted_date)
   print(formatted_time)


7. Analisando datas e horários a partir de strings:
   Você pode converter strings em objetos `datetime` usando `strptime`:

  
   date_str = "2023-09-27"
   parsed_date = datetime.strptime(date_str, "%Y-%m-%d")
   print(parsed_date)

