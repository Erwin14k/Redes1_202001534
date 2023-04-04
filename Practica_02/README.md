<html>
  <head>
    <meta charset="UTF-8">
  </head>
  <body>
    <h2>Erwin Fernando Vásquez Peñate</h2>
    <h2>202001534</h2>
    <h2>Redes De Computadoras 01 Sección N</h2>
    <br>
    <br>
    <h1 style="text-align:center;">Practica 02</h1>
    <h2>Topología</h2>
    <p>
      La topología estará compuesta por 7 áreas, cada una indicada con un color diferente, conformada por 6 routers, R2 y R3 configurados en modo HSRP, los routers R5 y R6 configurados en modo GLBP, los routers R1 Y R4 comunicados mediante un enlace serial, SW7 Y SW8 configurados con PortChannel con PAGP , SW9 y SW10 configurados con PortChannel con LACP, además de las 2 vpcs, que lograr comunicación entre ellas es el objetivo de la práctica.
    </p>
    <br>
    <br>
    <h2 style="text-align:center;">Configuración De VPC11</h2>
    <p>
      Estos fueron los comandos utilizados para la configuración de la VPC11, para la VC12 es similar, solo cambia su ip.
    </p>
    <div style="text-align: center;">
      <img src="./Images/vpc11_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <br>
    <h2 style="text-align:center;">Configuración De SW7 y SW8</h2>
    <p>
      Estos fueron los comandos utilizados para la configuración de los switches SW7 y SW8, los cuales están configurados Portchannel con PAGP.
    </p>
    <div style="text-align: center;">
      <img src="./Images/sw7_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <div style="text-align: center;">
      <img src="./Images/sw8_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <br>
    <h2 style="text-align:center;">Configuración De R2 y R3</h2>
    <p>
      Estos fueron los comandos utilizados para la configuración de los routers R2 y R3, los cuales están configurados en modo HSRP.
    </p>
    <div style="text-align: center;">
      <img src="./Images/r2_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <div style="text-align: center;">
      <img src="./Images/r3_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <br>
    <h2 style="text-align:center;">Configuración De R5 y R6</h2>
    <p>
      Estos fueron los comandos utilizados para la configuración de los routers R2 y R3, los cuales están configurados en modo GLBP.
    </p>
    <div style="text-align: center;">
      <img src="./Images/r5_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <div style="text-align: center;">
      <img src="./Images/r6_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <br>
    <h2 style="text-align:center;">Configuración De R1 y R4</h2>
    <p>
      Estos fueron los comandos utilizados para la configuración de los routers R2 y R3, los cuales están comunicados mediante un enlace serial.
    </p>
    <div style="text-align: center;">
      <img src="./Images/r1_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <div style="text-align: center;">
      <img src="./Images/r4_config.png" alt="Datacenter Network" width="1000" height="auto">
    </div>
    <br>
    <br>
    
  </body>
</html>