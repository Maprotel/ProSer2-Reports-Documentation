# MainCallEntry

## callentry_id - llamada_entrante_id
* Número secuencial generado automáticamente por el sistema por cada registro.

## callentry_agent_id - llamada_entrante_agente_id
* Número de identificación del agente asociado al registro. 

## callentry_queue_id - llamada_entrante_cola_id
* Número de identificación de la cola asociada al registro.

## callentry_contact_id - llamada_entrante_contacto_id 
* Número de contacto del llamante.

## callentry_callerid - llamada_entrante_identificador_llamadas_id
* Número de identificación del llamante.

## callentry_datetime_init - llamada_entrante_fecha_hora_inicio
* Fecha y hora de inicio de la llamada en formato YYYY-MM-DD HH:MM:SS

## callentry_datetime_end - llamada_entrante_fecha_hora_final
* Fecha y hora del fin de la llamada en formato YYYY-MM-DD HH:MM:SS

## callentry_duration_sec - llamada_entrante_duracion_sec
* Duración de la llamada entrante en segundos enteros.

## callentry_status - llamada_entrante_estado
* Estado de la llamada entrante: abandonada, terminada, activa, en-cola.

## callentry_transfer - llamada_entrante_transferencia
* Transferencia de la llamada entrante.

## callentry_datetime_entry_queue - llamada_entrante_fecha_hora_entrada_cola
* Fecha y hora de entrada en cola de la llamada.

## callentry_duration_sec_wait - llamada_entrante_duracion_sec_espera
* Duracion, en segundos, de espera de la llamada en la cola.

## callentry_uniqueid - llamada_entrante_unico_id
* Numero único de identificación de cada llamada entrante.

## callentry_campaign_id - llamada_entrante_campaña_id	
* Número de identificación de la campaña asociada al registro.

## callentry_trunk - llamada_entrante_troncal
* Troncal de la llamada.

## callentry_date - llamada_entrante_fecha
* Fecha de la llamada entrante registrada.

## callentry_queue_time_expired - llamada_entrante_cola_tiempo_expiracion
* Registro del tiempo de expiracion en cola de la llamada entrante.

## callentry_type - llamada_entrante_tipo
* Tipos de llamadas entrantes.

## callentry_auto_campaign - llamada_entrante_automatica_campaña
* Campaña automática asociada al registro.

## callentry_queue_number - llamada_entrante_cola_numero
* Número de la cola asociada a la llamada.

__QUEUELOG__

## callentry_who_hung - llamada_entrante_quien_colgo
* Registro de la persona que colgo la llamada entrante.

## callentry_hung_agent - llamada_entrante_colgado_agente   
* Registro de la llamada entrante colgada por un agente.

## callentry_hung_caller - llamada_entrante_colgado_llamador
* Registro de la llamada entrante colgada por el llamante.


__JSON__

## callentry_people_json - llamada_entrante_personas_json
* Campo relacional que asocia el registro con valores de personas de otras tablas. 

## callentry_operation_json - llamada_entrante_operacion_json
* Campo relacional que asocia el registro con valores de operaciones de otras tablas.

## callentry_time_json - llamada_entrante_tiempo_json
* Campo relacional que asocia el registro con valores de tiempo, fecha y día de otras tablas.

