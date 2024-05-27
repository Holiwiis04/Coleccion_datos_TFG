Los archivos con los datos de las distintas instancias han sido nombrados de la forma a_b.txt donde
"a" es el número de periodos de tiempo, T, y "b" es el número de tareas, J, establecidos para esa
prueba determinada.

Además, los parámetros son los siguientes:
	J = numero de tareas a ser planificadas
	T = numero de periodos de tiempo

	u = importancia de cada tarea
	q = cantidad de energia empleada en tarea
	min_statup = tiempo mínimo de veces que una tarea se puede iniciar
	max_statup = tiempo máximo de veces que una tarea puede iniciar
	min_cpu_time = tiempo mínimo de unidades de tiempo que una tarea puede consumir en secuencia
	max_cpu_time = tiempo máximo de unidades de tiempo que una tarea puede consumir en secuencia
	min_periodo_job = tiempo mínimo que una tarea debe esperar para repetirse
	max_periodo_job = tiempo máximo que una tarea puede esperar para repetirse
	win_min = inicio de la ventana de ejecucion de cada tarea
	win_max = final de la ventana de ejecucion de cada tarea
	r = cantidad de energia recibida en cada periodo de tiempo