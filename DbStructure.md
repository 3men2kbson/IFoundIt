# **Estructura de la Base de Datos IWillFindIt** #
## para ser usada en el Sistema IFoundIt ##

La Base de Datos se llamará **IWillFindIt** y constará de las siguientes tablas:

**Tabla User**

| Column   | Type  | Long  |
| :------- | ----: | :---: |
| IdUser   | Int   |       |
| UserName | Text  |  20   |
| Name     | Text  |  50   |
| PassWd   | Text  |  20   |

**Tabla Vehicle**

| Column   | Type  | Long  |
| :------- | ----: | :---: |
| IdVeh    | Int   |       |
| Name     | Text  |  20   |
| Brand    | Text  |  20   |
| Model    | Text  |  20   |
| Year     | Int   |       |
| PassWd   | Text  |  6    |

**Tabla Parameters**

| Column   | Type  | Long  |
| :------- | ----: | :---: |
| IdParam  | Int   |       |
| Params   | Text  |  30   |
| ParamCod | Text  |  30   |
| Active   | Bool  | T / F |
