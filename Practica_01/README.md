<html>
  <head>
    <meta charset="UTF-8">
  </head>
  <body>
    <h2>**Erwin Fernando Vásquez Peñate</h2>
    <h2>**202001534</h2>
    <h2>**Redes De Computadoras 01 Sección N</h2>
    <h1>Práctica 01</h1>
    <h2>BackBone</h2>
    <p>
      El Backbone de la red, estará configurado por 2 Switches, que simularán los niveles de la red.
    </p>
    <div style="text-align: center;">
      <img src="./Images/backbone.png" alt="Backbone Network">
    </div>
    <h2>Nivel 1</h2>
    <p>
      El primer nivel contará con equipo (VPC) para la recepción, otro más para la gerencia junto
      con su secretaria, 2 para la atención al cliente y 6 para uso de oficina.
    </p>
    <div style="text-align: center;">
      <img src="./Images/level01.png" alt="Backbone Network" width="1000" height="auto">
    </div>
    <h2>Nivel 2</h2>
    <p>
      El segundo nivel contará con 10 equipos en total repartidos en las distintas oficinas que lo
      componen (2 en la oficina A, 3 en la B y el resto en la C).
    </p>
    <div style="text-align: center;">
      <img src="./Images/level02.png" alt="Backbone Network" width="1000" height="auto">
    </div>
    <h2>Ip De La Red</h2>
    <div style="text-align: center;">
      <img src="./Images/ipNetwork.png" alt="Backbone Network" width="1000" height="auto">
    </div>
    <h2>Topología</h2>
    <div style="text-align: center;">
      <img src="./Images/topology.png" alt="Backbone Network" >
    </div>
    <h1>Configuración VPCS</h1>
    <h3>Recepción:</h3>
    <div style="text-align: center;">
      <img src="./Images/reception.png" alt="Backbone Network" >
    </div>
    <h3>Gerencia:</h3>
    <div style="text-align: center;">
      <img src="./Images/management.png" alt="Backbone Network" >
    </div>
    <h3>Atención Al Cliente:</h3>
    <div style="text-align: center;">
      <img src="./Images/clientAttention.png" alt="Backbone Network" >
    </div>
    <h3>Oficina:</h3>
    <div style="text-align: center;">
      <img src="./Images/office.png" alt="Backbone Network" >
    </div>
  </body>
  <h3>Oficina A:</h3>
    <div style="text-align: center;">
      <img src="./Images/officeA.png" alt="Backbone Network" >
    </div>
  </body>
  <h3>Oficina B:</h3>
    <div style="text-align: center;">
      <img src="./Images/officeB.png" alt="Backbone Network" >
    </div>
  </body>
  <h3>Oficina C:</h3>
    <div style="text-align: center;">
      <img src="./Images/officeC.png" alt="Backbone Network" >
    </div>
  <h1>Pings Entre Hosts</h1>
  <h3>Recpeción -> Atención Al Cliente: </h3>
  <p>
    192.168.34.1 ---> 192.168.34.3
  </p>
  <div style="text-align: center;">
    <img src="./Images/ping1.png" alt="Backbone Network" >
  </div>
  <div style="text-align: center;">
    <img src="./Images/ping11.png" alt="Backbone Network" >
  </div>
  <h3>Oficina A -> Oficina C: </h3>
  <p>
    192.168.34.11 ---> 192.168.34.16
  </p>
  <div style="text-align: center;">
    <img src="./Images/ping2.png" alt="Backbone Network" >
  </div>
  <div style="text-align: center;">
    <img src="./Images/ping22.png" alt="Backbone Network" >
  </div>
  <h3>Gerencia -> Oficina B: </h3>
  <p>
    192.168.34.2 ---> 192.168.34.13
  </p>
  <div style="text-align: center;">
    <img src="./Images/ping3.png" alt="Backbone Network" >
  </div>
  <h1>Capturas De Paquetes ARP</h1>
  <h2>Gerencia -> Oficina B: </h2>
  <p>
    Enviar desde 192.168.34.2 ---> Capturar En 192.168.34.13
  </p>
  <div style="text-align: center;">
    <img src="./Images/arp1.png" alt="Backbone Network" >
  </div>
  <div style="text-align: center;">
    <img src="./Images/arp2.png" alt="Backbone Network" >
  </div>
  </body>
</html>

