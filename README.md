# EcoCharger
## ¿Qué es EcoCharger y en qué consiste? 
El principal problema que limita el crecimiento de las energías renovables hoy es su almacenamiento, ya que si no se almacena hay que consumirla en el momento en el que se genera, sobre todo cuando hablamos de la principal fuente de energía renovable que es el eólica ya que el viento sopla a su antojo de manera bastante impredecible.

EcoCharger es mi aplicación creada para solucionar este problema y que de esa manera entre todos podamos tener una energía sostenible sin que se tiren los excedentes. Esta aplicación gestiona la de carga tu vehículo eléctrico o acumulador doméstico de manera sostenible y eficiente.

El funcionamiento es el siguiente: si no hay excedentes de generación de energías renovables en la red cargarás tu coche lo mínimo que necesitas para el día siguiente establecido en tu tabla de configuraciones, en caso de que haya excedentes de energías renovables entonces cargaremos la totalidad de la batería.

¿Cómo sabemos si se está generando más energía renovable de la que se está consumiendo? Conectando mi aplicación con la API REST disponible de Red Eléctrica Española comprueba que la generación sea mayor que la demanda y realiza el proceso correspondiente.

¿Y cómo actúo sobre el cargador de mi vehículo o el acumulador doméstico? Mediante un enchufe IOT de TP-Link de precio inferior a 25 euros y conectado a través de la plataforma IFTTT la cual puedo interactuar desde mi app inventor.
