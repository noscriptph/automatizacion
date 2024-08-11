# Sistema de Control para Llenado e Irrigación de Estanque

## Descripción del Proyecto

Este proyecto consiste en un sistema automatizado para el control de llenado de un estanque de 5400 litros, y la irrigación de una plantación. El sistema utiliza dos bombas de agua y está controlado por flotadores de nivel que aseguran el funcionamiento eficiente y seguro del equipo.

### Componentes Principales

1. **Bomba de Agua (Profundidad de 20 metros)**: Extrae agua desde una fuente subterránea.
2. **Estanque de 5400 litros**: Almacena el agua extraída por la bomba.
3. **Bomba de Irrigación**: Utiliza el agua del estanque para regar la plantación.
4. **Flotadores de Nivel**:
   - **Flotador de Nivel Bajo**: Evita que la bomba de riego funcione si el estanque está vacío.
   - **Flotador de Nivel Alto**: Detiene la bomba de llenado para evitar el sobrellenado del estanque.

### Funcionamiento del Sistema

#### Llenado del Estanque

- **Inicio del Ciclo**: El sistema se activa cuando el nivel de agua en el estanque baja y el **Flotador de Nivel Bajo** activa la bomba de agua.
- **Proceso de Llenado**: La bomba extrae agua desde una profundidad de 20 metros y la envía al estanque.
- **Corte de la Bomba**: Cuando el estanque alcanza su capacidad máxima, el **Flotador de Nivel Alto** apaga la bomba para prevenir el sobrellenado.

#### Irrigación de la Plantación

- **Condiciones Iniciales**: La bomba de riego solo se activa si el **Flotador de Nivel Bajo** indica que hay suficiente agua en el estanque.
- **Riego Activo**: La bomba de riego se enciende y utiliza el agua del estanque para regar la plantación.
- **Prevención de Funcionamiento en Vacío**: Si el nivel de agua es insuficiente, la bomba de riego se apaga automáticamente para evitar daños.

## Diagrama del Sistema

![Diagrama del Sistema](<diagrama tablero.bmp>)

## Licencia de Uso y Autoria

Este proyecto está protegido por derechos de autor. Se permite su uso únicamente con fines educativos, y está prohibido su uso comercial sin la debida autorización. **Todos los diagramas y proyectos deben ser realizados por electricistas certificados** según la normativa del país correspondiente. Respetar la autoría y dar crédito a los creadores es fundamental.

## Donaciones

Si este proyecto te ha sido útil y deseas apoyar mi trabajo, puedes hacerlo a través de **PayPal**. ¡Gracias por tu apoyo!
