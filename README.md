# RETO-MASTER-Semana-1

**"CONCEPTOS DE LA NUBE CON AZURE"**

## **¿Qué es AZURE?**
> Es una plataforma de computación en la nube con un conjunto de servicios en constante expansión para ayudarlo a crear soluciones para alcanzar sus objetivos comerciales. 

## **Ventajas de usar la computacion en la nube**

- Escalabilidad:
  - Vertical: La capacidad de calculo se puede aumentar agregando RAM o CPU a una maquina virtual. 
  - Horizontal: La capacidad de calculo se aumenta agregando instancias de un recurso, como agregar mas maquinas virtuales.

- Elasticidad:
Las aplicaciones de la nube se pueden configurar para que siempre tengan los recursos necesarios. Ejem. un servidor limite de 100 personas, pero se meten 120, no hay problema, funcionara correctamente.

- Agilidad:
Los recursos basados en la nube se pueden implementar y configurar rápidamente a medida que cambian los requisitos de su aplicación.

- Distribucion geografica:
las aplicaciones y los datos se pueden implementar en centros de datos regionales de todo el mundo, para que sus clientes siempre tengan el mejor rendimiento en su región.

- Recuperacion ante desastres:
Como hay respaldo en la nube, los datos siempre estaran seguros.

- Fiabilidad:
Las aplicaciones basadas en la nube pueden proporcionar una experiencia de usuario continua sin tiempo de inactividad.

## **Modelos de servicios de Azure**

- IaaS (Infrastruture): Servicio mas cercano a gestion de servidores publicos. Un provedor de la nube lo mantiene actualizado, pero el mantenimiento del sistema operativo y la configuración de la red se dejan al inquilino de la nube. 
Por ejemplo: *Azure Virtual Machines*.

- PaaS (Plataform): Es un alojamiento gestionado. El proveedor de la nube administra las máquinas virtuales y los recursos de red, y el inquilino de la nube implementa sus aplicaciones en el entorno de alojamiento administrado. Por ejemplo: *Azure App Services*. 

- SaaS (Software): El proveedor de la nube gestiona todos los aspectos del entorno de la aplicación, como máquinas virtuales, recursos de red, almacenamiento de datos y aplicaciones. El inquilino de la nube solo necesita proporcionar sus datos a la aplicación administrada por el proveedor de la nube. Por ejemplo *Office 365*.

## **Modelos de implementacion**

- Nube Publica: Los servicios se ofrecen a través de la Internet pública y están disponibles para cualquier persona que desee adquirirlos. Los recursos en la nube, como los servidores y el almacenamiento, son propiedad y están operados por un proveedor de servicios en la nube externo y se entregan a través de Internet.

- Nube Privada: Los recursos informáticos son utilizados exclusivamente por usuarios de una empresa u organización. Una nube privada se puede ubicar físicamente en el centro de datos en el sitio de su organización. 

- Nube Hibrida: Este entorno informático combina una nube pública y una nube privada al permitir que los datos y las aplicaciones se compartan entre ellos.

## **OpEx y CapEx**

Operation Expenditure y Capital Expenditure, el primero es el gasto de dinero en productos o servicios en el momento y se factura por ellos en ese mismo momento, por lo tanto no inversion inicial. Y el segundo SI hay un gasto inicial en infraestructura fisica que se deduce a lo largo del tiempo.

## **Base de datos y Storage**

Son diferentes, base de datos proporciona servicios de bases de datos en varios tipos y volumenes y storage es almacenamiento de archivos y objetos. Ejem: en netflix base de datos guarda usuarios y contraseñas y storage las pelis vistas.
