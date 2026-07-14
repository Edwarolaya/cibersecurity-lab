# Lección 01: Fundamentos de Redes

### 1. ¿Qué es una red?
Imagina una red como un grupo de personas en una sala que hablan el mismo idioma para compartir información. En el mundo digital es exactamente lo mismo, pero con dispositivos (computadoras, celulares, servidores) conectados entre sí mediante cables o Wi-Fi para intercambiar datos, recursos y servicios.

### 2. ¿Qué diferencia hay entre una IP pública y una privada?
*   **IP Privada:** Es la identificación que tiene tu dispositivo dentro de tu casa u oficina (tu red local). Solo sirve para que tus dispositivos se hablen entre sí (como la numeración de los cuartos dentro de un hotel).
*   **IP Pública:** Es la identificación única que te asigna tu proveedor de internet para salir al mundo exterior. Es visible desde cualquier parte de internet (como la dirección postal de la fachada del hotel).

### 3. ¿Qué hace un router?
Es el "director de tráfico" de la red. Su trabajo es conectar redes distintas (como tu red doméstica con la inmensa red de internet) y decidir cuál es el camino más rápido y eficiente para que los datos viajen de un punto A a un punto B.

### 4. ¿Qué es un paquete?
En internet las cosas no viajan completas porque serían muy pesadas. Si envías una foto, el sistema la "desarma" en fragmentos pequeños llamados **paquetes**. Cada paquete lleva una parte de la foto, la dirección de origen, la de destino y el orden en que debe reensamblarse al llegar.

### 5. ¿Qué diferencia hay entre TCP y UDP?
*   **TCP:** Es el protocolo "obsesivo y seguro". Se asegura de que cada paquete llegue completo, en orden y sin errores. Si algo se pierde, lo vuelve a pedir. Se usa para páginas web o correos donde no puede faltar ni una letra.
*   **UDP:** Es el protocolo "veloz y sin rodeos". Envía los paquetes lo más rápido posible sin confirmar si llegaron bien o no. Se usa para streaming de video o videojuegos online, donde un pequeño corte es preferible a retrasar toda la transmisión.

### 6. ¿Qué es DNS?
Es la "agenda telefónica" de internet. Los humanos recordamos nombres (como google.com), pero las computadoras solo entienden números (direcciones IP). El DNS traduce esos nombres de dominio a las IPs correspondientes para que tu navegador sepa a dónde ir.

### 7. ¿Qué es DHCP?
Es el "repartidor automático" de la red. En lugar de que tengas que configurar manualmente la dirección IP, máscara y puerta de enlace en cada dispositivo que conectas a tu red local, el servidor DHCP les asigna una IP automáticamente apenas se conectan.

### 8. ¿Qué es NAT?
Es el "traductor" que hace magia con las IPs. Como las IPs públicas son limitadas y costosas, NAT permite que decenas de dispositivos en tu casa (con IPs privadas diferentes) salgan a internet usando una única IP pública compartida. Cuando la información regresa, NAT sabe exactamente a qué dispositivo interno entregarle la respuesta.
