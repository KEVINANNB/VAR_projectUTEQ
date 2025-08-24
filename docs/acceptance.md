Para cada req funcional incluye la prueba que lo valida:

Ejemplo RF-03 (decisión GOL):

Condición: Se suministran 50 videos de prueba con anotaciones GT.

Aceptación: El sistema debe alcanzar F1 ≥ 0.9 en la clasificación por frame GOL/NO_GOL.

Prueba: ejecutar script evaluation.py para calcular confusion matrix.

Incluye también umbrales de calibración aceptables (error homografía < 0.05 m, ver más abajo).