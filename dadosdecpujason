import psutil
import json

# coletando os dados da CPU
cpu_percent = psutil.cpu_percent()
cpu_temp = psutil.sensors_temperatures()['coretemp'][0].current

# estruturando os dados em um dicionário
cpu_data = {'cpu_percent': cpu_percent, 'cpu_temp': cpu_temp}

# convertendo em JSON
cpu_json = json.dumps(cpu_data)

print(cpu_json)
