1. La Fundación: VirtualBox y Red Aislada

Para la configuración del laboratorio se seleccionó el modo NAT ya que permite que la máquina virtual tenga acceso a Internet utilizando la conexión de red de la máquina real (Host), pero sin estar conectada directamente a la red local como un dispositivo independiente. Esto proporciona un nivel de aislamiento que ayuda a reducir la exposición de la máquina virtual y del Host frente a otros dispositivos de la red. A diferencia del modo Red Interna, que permite la comunicación únicamente entre las máquinas virtuales que pertenecen a esa misma red interna y normalmente no proporciona acceso directo a Internet, el modo NAT sí permite que la máquina virtual navegue por Internet y descargue actualizaciones o herramientas necesarias para realizar las prácticas. Por este motivo se eligió NAT, ya que ofrece un equilibrio entre conectividad y aislamiento, permitiendo trabajar con la máquina virtual y acceder a Internet sin exponerla directamente a la red física donde se encuentra el equipo Host.

<img width="824" height="518" alt="NAT" src="https://github.com/user-attachments/assets/ee058008-2eb0-49a0-82c8-50ba91b99c9f" />

2. Capa Windows: Usuarios y Actualizaciones

Para la capa de Windows se crearon 2 usuarios, 1 como administrador y otro sin permisos de administrador para mas seguridad

<img width="1078" height="855" alt="USUARIO ESTANDAN WINDOWS" src="https://github.com/user-attachments/assets/6a9e95c1-6e4d-4fed-abf6-026f9b853e71" />

Y la maquina virtual de Windows posee sus respectivas actualizaciones 














4. La Red de Seguridad: Snapshot Inicial

Adjunto imagen de la snapshot creada para la maquina virtual de Kali

<img width="1271" height="746" alt="SNAPSHOTS" src="https://github.com/user-attachments/assets/f94abb0f-8d54-400d-8771-6cade37bd5a9" />
