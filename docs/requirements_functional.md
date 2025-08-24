Cada requisito debe ser verificable. Ejemplos claros:

RF-01 El sistema debe detectar y marcar en el frame el bounding box del balón cuando es visible.

RF-02 El sistema debe convertir centro y radio del balón a coordenadas del campo (metros) usando homografía.

RF-03 El sistema debe emitir “GOL” si todo el balón (centro ± radio) cruza la línea de gol en la referencia de homografía.

RF-04 El sistema debe registrar cada evento en CSV con: frame_id, timestamp, decision, conf, cx_m, cy_m, r_m, image_path.

RF-05 La UI debe mostrar el video en vivo con overlay y permitíre marcar la decisión manualmente.