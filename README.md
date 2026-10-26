# Quemarueda

Simulador de drag (1/4 de milla) para móvil. Prepara el coche pieza a pieza, ajusta el reglaje en el banco y gana la liga nocturna de 10 rondas.

## Cómo se corre
- **Embrague** (izquierda): mantén para entrar en stage. Suéltalo cuando se encienda el verde. Si lo sueltas antes, luz roja.
- **Gas** (derecha): sube vueltas antes de salir (o 2-step con centralita programable). En carrera es el **cambio**: cambia cuando las luces se pongan azules.
- Gana quien cruza antes contando reacción + tiempo (R/T + ET).
- Teclado: ↓ o C = embrague, espacio = gas/cambio, N = nitroso.

## Lo técnico
- Piezas: motor, sobrealimentación, centralita, combustible, neumáticos, suspensión, transmisión, aligeramiento, nitroso y aerodinámica.
- Reglaje: grupo final, relaciones por marcha, presión de turbo, avance de encendido, 2-step, presión de neumáticos y ángulo del alerón.
- Detonación: avance + presión contra octanaje e interiores. Si detona, la centralita quita potencia.
- Banco: curvas de potencia y par, tabla de marchas y ficha técnica.
- Hoja de tiempos con R/T, 60 ft, 330 ft, 1/8, 1000 ft, 1/4 y velocidades.

Todo va en `index.html` (HTML + CSS + JS, sin librerías). La partida se guarda en el navegador.
