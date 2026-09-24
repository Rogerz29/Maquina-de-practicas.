1. La Fundación: VirtualBox y Red Aislada

Para la configuración del laboratorio se seleccionó el modo NAT ya que permite que la máquina virtual tenga acceso a Internet utilizando la conexión de red de la máquina real (Host), pero sin estar conectada directamente a la red local como un dispositivo independiente. Esto proporciona un nivel de aislamiento que ayuda a reducir la exposición de la máquina virtual y del Host frente a otros dispositivos de la red. A diferencia del modo Red Interna, que permite la comunicación únicamente entre las máquinas virtuales que pertenecen a esa misma red interna y normalmente no proporciona acceso directo a Internet, el modo NAT sí permite que la máquina virtual navegue por Internet y descargue actualizaciones o herramientas necesarias para realizar las prácticas. Por este motivo se eligió NAT, ya que ofrece un equilibrio entre conectividad y aislamiento, permitiendo trabajar con la máquina virtual y acceder a Internet sin exponerla directamente a la red física donde se encuentra el equipo Host.

<img width="824" height="518" alt="NAT" src="https://github.com/user-attachments/assets/ee058008-2eb0-49a0-82c8-50ba91b99c9f" />

2. Capa Windows: Usuarios y Actualizaciones

Para la capa de Windows se crearon 2 usuarios, 1 como administrador y otro sin permisos de administrador para mas seguridad

<img width="1078" height="855" alt="USUARIO ESTANDAN WINDOWS" src="https://github.com/user-attachments/assets/6a9e95c1-6e4d-4fed-abf6-026f9b853e71" />
<img width="1278" height="937" alt="USUARIOSSS" src="https://github.com/user-attachments/assets/e4d68479-4b2c-4460-9567-169e7675ded8" />


Y la maquina virtual de Windows posee sus respectivas actualizaciones 
<img width="1033" height="853" alt="update windows" src="https://github.com/user-attachments/assets/ae90aec9-a61b-4c7c-bff7-4806b564837c" />


3. Capa Linux: Permisos y Gestión

Aca tenemos creacion de usuarios para mas seguridad 
<img width="2047" height="1274" alt="USUARIO NUEVO KALI" src="https://github.com/user-attachments/assets/fb3b8133-8245-4bca-b18b-8e389ed054e0" />
<img width="2043" height="1279" alt="Screenshot_1" src="https://github.com/user-attachments/assets/4a04a5b9-4a75-42c0-b2c7-476693bb07d3" />


Posteriormente creamos un archivo y le quitamos permiso a los demas usuarios
<img width="2093" height="1285" alt="asda" src="https://github.com/user-attachments/assets/9624171c-62bb-4646-b3b1-7ecc71593ddf" />

Aca se cambiaron los permisos
<img width="2040" height="1291" alt="permisos sobre un archivo" src="https://github.com/user-attachments/assets/03dac7e9-4c5c-4257-bffc-4a5132ad670c" />


Y se adjuntan imagenes de kali completamente actualizado al dia 
<img width="1276" height="884" alt="update" src="https://github.com/user-attachments/assets/55b8fa14-0757-4335-ae6a-67e08b41c56f" />

5. La Red de Seguridad: Snapshot Inicial
 
Kali linux
<img width="1271" height="746" alt="SNAPSHOTS" src="https://github.com/user-attachments/assets/aacd39ab-57b9-491e-818d-49fc2873557f" />


Windows
<img width="1277" height="748" alt="snapshot windows" src="https://github.com/user-attachments/assets/86be89e1-759e-46e8-bbf3-116cc4c00770" />
