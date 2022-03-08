[Volver](../README.md)
# Casos de Uso
31 de Mayo del 2021
## Grupo 1
|||
|--|--|
|FR-01|Retirar dinero|
|Versión|1.0|
|Actores|Cliente de Banco|
|Objetivos|OBJ-01 retirar dinero desde cuenta del usuario cliente|
|Requerimientos asociados|RI-02 Información de acceso de usuario cliente|
|Descripción|El sistema deberá comportarse tal como se describe en el siguiente caso de un cliente que solicita dinero de una cuenta en un banco usando un cajero automático|


## Grupo 2
||||
|--|--|--|
|**Precondición**||El solicitante debe ser cliente del banco para poder realizar el procedimiento|
||||
|**Secuencia**|**Pasos**|**Acción**|
|Normal|1|Validar credenciales de acceso|
||2|Ingreso al sistema|
||3|Solicitar retirar dinero|
||||
|**Postcondiciones**||El dinero retirado es disminuido en la cuenta del cliente|
||||
|**Excepciones**|**Pasos**||
||1|No existe acceso a internet|
||2|Las credenciales de usuario no existe en el sistema, no puede ingresar|
||3|no existe dinero en la cuenta de cliente|

## Grupo 3
||||
|--|--|--|
|**Rendimiento**|**Pasos**|**Cota de Tiempo**|
||1|3 segundos|
||3|3 segundos|
||||
|**Frecuencia esperada**|100 veces al día||
|**Comentarios**|No procede||
