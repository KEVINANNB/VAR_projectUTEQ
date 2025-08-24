Chessboard params usados en calibración intrínseca (p. ej. 9×6 squares, square_size en mm).

Puntos reales a usar para homografía: por ejemplo, postes (x=0, y=0) y esquina área pequeña en metros. Lista exacta de coordenadas reales.

Requerimiento de verificación: proyección de 6 puntos de control distintos con error máximo permitido (ej. RMS < 0.05 m).

Ubica una plantilla para el homography_check.csv con columnas: img_pt_u,img_pt_v,real_X,real_Y,error_m.