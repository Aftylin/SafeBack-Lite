<table>
  <tr>
    <td><img src="https://i.imgur.com/CxH87tS.png" width="100" height="100" alt="SafeBack Lite Icon"></td>
    <td><h1>SafeBack Lite</h1></td>
  </tr>
</table>

## ¡Se te da la Bienvenida al repositorio oficial de **SafeBack Lite**! 

Este plugin esta desarrollado bajo los más altos estándares de ingeniería para Unturned (RocketMod), ofreciendo una solución de teletransportación hacia la ultima muerte, segura, optimizada y de alta eficiencia. Su arquitectura está pensada para servidores que priorizan la estabilidad y una experiencia de usuario sin errores.

## 🚀 ¿Por qué elegir SafeBack Lite?
A diferencia de otras soluciones genéricas, **SafeBack Lite** garantiza una gestión superior de las funciones esenciales para tu servidor:

* **Estabilidad bajo carga:** Diseñado para mantener un rendimiento impecable incluso en servidores con alta cantidad de jugadores simultáneos, asegurando que cada comando se procese con total fluidez.
* **Integridad de datos garantizada:** Cuenta con protocolos avanzados de protección de información que evitan la pérdida de datos o la corrupción de archivos ante cierres o reinicios inesperados del servidor.
* **Seguridad anti-exploits:** Incorpora sistemas inteligentes de supervisión que validan constantemente las condiciones del jugador, eliminando riesgos de abuso y asegurando que las mecánicas del juego se respeten siempre.
* **Eficiencia operativa:** Optimizado para operar de forma ligera y autónoma, manteniendo la base de datos limpia y organizada sin intervención manual.
* **Versatilidad Económica (Compatible con Uconomy):** Integración nativa y fluida con cualquier ecosistema de **Uconomy**. El plugin detecta automáticamente el sistema de economía instalado, permitiendo establecer costos de teletransportación.

## 📦 Instalación
1. Descarga el archivo `.dll` desde la sección de **Releases**.
2. Colócalo en la carpeta `Plugins` de tu servidor RocketMod.
3. Reinicia el servidor para generar el archivo de configuración automático.
4. *Nota: Asegúrate de tener **Uconomy** instalado en tu servidor si deseas utilizar la gestión de moneda virtual; de lo contrario, el plugin utilizará automáticamente la experiencia (EXP) como método de pago.*

## 💰 Configuración Económica
Puedes definir el costo y el método de pago directamente en el archivo `SafeBackLite.configuration.xml` generado en tu carpeta `Plugins/SafeBackLite/`.
```xml
<SafeBackLiteConfig>
  <UseUconomy>true</UseUconomy>
  <Cost>250</Cost>
  <TeleportDelay>5</TeleportDelay>
</SafeBackLiteConfig>
```
Si el valor de UseUconomy es false, el comando cobrará automáticamente en niveles de experiencia (EXP).

## 👥 Permisos (Permissions)
Asegúrate de añadir el siguiente permiso en tu archivo `Permissions.config.xml` para habilitar el acceso a tus jugadores:
```
<Permission Cooldown="0">back</Permission>
```
## 💎 ¿Buscas el siguiente nivel? SafeBack Pro
SafeBack Lite ofrece una base impecable para el regreso al lugar de muerte, pero si buscas potenciar la comodidad de tus jugadores, la versión SafeBack Pro desbloquea capacidades avanzadas diseñadas para entornos de alto combate:

* Configuración avanzada de tiempos de inmunidad (GodMode) al reaparecer tras el comando /back.

* Cancelación automática del escudo si el jugador intenta atacar, equipar armas o consumir objetos.

* Opción para restringir o permitir el uso del comando /back basándose en el radio de seguridad de otros jugadores o zonas de PvP/PvE.

* Efectos perzonalizables al momento de la muerte del jugador y al regreso con el comando /back. (Como particulas y sonidos)

Si la precisión y seguridad de esta versión Lite han mejorado la experiencia en tu servidor, el ecosistema Pro está diseñado para elevar el estándar del gameplay de tus jugadores.

## 📜 Licencia y Propiedad Intelectual
Este proyecto es propiedad intelectual de **Afty (a.k.a. Crafty) - S.E.R.A Club**. 

El uso del archivo `.dll` está sujeto estrictamente a los términos definidos en el archivo [LICENSE](LICENSE). El software se distribuye exclusivamente en formato binario compilado y ofuscado; el código fuente no se proporciona bajo ninguna circunstancia, quedando prohibida su ingeniería inversa, modificación o reventa.
