# MainCdr

## cdr_id - cdr_id
* Número secuencial generado automáticamente por el sistema por cada registro. 

## cdr_calldate - cdr_llamada_fecha
* Fecha de la llamada registrada en el cdr.

## cdr_clid - cdr_clid
* Identificación, en texto, del llamante asociado a la llamada perteneciente a ese registro.

## cdr_src - cdr_src
* Número de identificación del llamante asociado a la llamada perteneciente a ese registro

## cdr_dst - cdr_dst
* Extensión de destino de la llamada asociada a ese registro.

## cdr_dcontext - cdr_dcontexto
* Contexto de destino de la llamada asociada a ese registro.

## cdr_channel - cdr_canal
* Nombre del canal utilizado por la llamada asociada a ese registro.

## cdr_dstchannel - cdr_dstcanal
* Nombre del canal de destino de la llamada asociada a ese registro.
	
## cdr_lastapp - cdr_ultima_aplicacion
* Última aplicación que ejecutó el canal de la llamada asociada a ese registro.

## cdr_lastdata - cdr_ultima_data
* Los datos de la aplicación para la última aplicación que ejecutó el canal de la llamada asociada a ese registro.

## cdr_duration_sec - cdr_duracion_sec
* Duración, en segundos, de la llamada asociada a ese registro.

## cdr_billsec_sec - cdr_cuentasec_sec
* Cantidad de segundos facturables para la llamada asociada a ese registro.

## cdr_disposition - cdr_disposicion
* Estado final de la llamada asociada a ese registro.

## cdr_amaflags - cdr_amaflags
* Clasificación del CDR para una sistema externo

## cdr_accountcode - cdr_cuenta_codigo
* Código de cuenta (en caso de existir) asociado al canal de la llamada.

## cdr_uniqueid - cdr_unico_id
* Código único de identificación de la llamada asociada a ese registro.

## cdr_userfield - cdr_usuario_campo
* Campo asociado al usuario configurado previamente en el canal. 

## cdr_recordingfile - cdr_grabacion_archivo
* Directorio en el que se encuentra almacenada la grabación de la llamada asociada a ese registro.
	
## cdr_cnum - cdr_cnum
* xxx

## cdr_cnam - cdr_cnam
* xxx

## cdr_outbound_cnum - cdr_saliente_cnum
* xxx
	
## cdr_outbound_cnam - cdr_saliente_cnam
* xxx

## cdr_dst_cnam - cdr_dst_cnam
* xxx

## cdr_did - cdr_hizo
* xxx

__CALLCENTER__	

## cdr_callcenter_name - cdr_centro_llamadas_nombre
* Nombre del call center.

## cdr_call_type - cdr_llamada_tipo
* Tipo de llamadas en cdr.

## cdr_call_class - cdr_llamada_clase
* Clase de llamadas en cdr.

## cdr_agent_extension - cdr_agente_extension
* Extensión del agente asociado al registro.

## cdr_queue_number - cdr_cola_numero
* Número de la cola asociada al registro.

## cdr_agent_id - cdr_agente_id
* Número de identificación del agente asociado al registro.

## cdr_queue_id - cdr_cola_clase
* Número de identificación de la cola asociada al registro.


__DATE__	

## cdr_date - cdr_fecha
* Fecha de cada registro del cdr.


__MADE__	

## cdr_call_made - cdr_llamada_hecho
* Registro de cada llamada saliente en cdr.

## cdr_call_fail - cdr_llamada_fallida
* Registro de cada llamada fallida en cdr.

## cdr_call_answered - cdr_llamada_contestadas
* Registro de cada llamada contestada en cdr.

## cdr_call_efective - cdr_llamada_eficaz
* Registro de cada llamada efectiva en cdr.

## cdr_call_hungout - cdr_llamada_colgar
* Registro de cada llamada colgada en cdr.

__JSON__	

## cdr_people_json - cdr_personas_json
* Campo relacional que asocia el registro con valores de personas de otras tablas. 

## cdr_operation_json - cdr_operacion_json
* Campo relacional que asocia el registro con valores de operaciones de otras tablas.

## cdr_time_json - cdr_tiempo_json
* Campo relacional que asocia el registro con valores de tiempo, fecha y día de otras tablas.


