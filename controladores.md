El circuito está formado por 4 controladores (subcircuitos).

**Controlador auto**

Se encarga de manejar las luces del semáforo para autos.

- Entradas
  - Clock
  - Restet
  - Boton peaton
- Salidas
  - Rojo
  - Amarillo
  - Verde
  - Ctrl Peaton

**Controlador peaton**

Se encarga de manejar las luces del semáforo para peatones.

- Entradas
  - Clock
  - Reset
  - Ctrl Auto
- Salidas
  - Rojo
  - Verde
  - Filtro

**Controlador digitos**

Se encarga de manejar los dígitos del contador de tiempo de verde del semáforo de peatones

- Entradas
  - Clock
  - Ctrl Auto
- Salidas
  - 1-14 (pins de los dígitos)

**Filtro**

Deja pasar la señal del botón de peatones sólamente cuando el semáforo de peatones está en rojo.

- Entradas
  - Boton Peatones
  - Ctrl Peaton
- Salidas
  - Ctrl Auto
