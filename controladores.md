El circuito está formado por 4 controladores (subcircuitos).

- Controlador auto:
  - Entradas
    - Clock
    - Restet
    - Boton peaton
  - Salidas
    - Rojo
    - Amarillo
    - Verde
    - Ctrl Peaton
  Se encarga de manejar las luces del semáforo para autos.
- Controlador peaton:
  - Entradas
    - Clock
    - Reset
    - Ctrl Auto
  - Salidas
    - Rojo
    - Verde
    - Filtro
  Se encarga de manejar las luces del semáforo para peatones.
- Controlador digitos:
  - Entradas
    -
  - Salidas
    - 1-14 (pins de los dígitos)
  Se encarga de manejar los dígitos del contador de tiempo de verde del semáforo de peatones
- Filtro
  - Entradas
    - Boton Peatones
    - Ctrl Peaton
  - Salidas
    - Ctrl Auto
  Deja pasar la señal del botón de peatones sólamente cuando el semáforo de peatones está en rojo.
