pixels_per_ball: promedio de píxeles de diámetro del balón en imágenes (debe ser ≥ 40 px para buena precisión).

homography_error_m: promedio del error de proyección (metros) usando puntos de verificación. Objetivo < 0.05 m.

precision, recall, f1 en decisión GOL/NO_GOL.

latency_ms : tiempo medio desde captura hasta veredicto.

false_positive_rate y false_negative_rate por evento.

frames_confirm: número de frames consecutivos requeridos para confirmar un gol (parametrizable).