
# Levantar aplicación  Android 

Este documento proporciona instrucciones detalladas sobre cómo configurar y levantar la aplicación Android dinersclub-android en tu entorno de desarrollo.

## Clonado de Proyectos

Clonado de Proyectos
Primero, asegúrate de tener Git instalado en tu sistema. Luego, clona los dos proyectos necesarios:

- git clone dinersclub-android
- git clone dinersclub-android-core

## Paso 1: Integración del Módulo dinersclub-android-core

copia el proyecto dinersclub-android-core dentro del directorio raíz de dinersclub-android. Este paso asegura que el módulo dinersclub-android-core esté disponible dentro del proyecto principal y pueda ser referenciado correctamente en el proceso de desarrollo y compilación de la aplicación.
![image](https://github.com/DiegoFelipe7/config-service/assets/90659322/ff9e9d9f-2e7b-4237-ba6b-01caf4077aa5)


## Paso 2: Configuración del gradel

**build.gradle**:Agrega la referencia al nuevo módulo dentro de la sección dependencies en el archivo build.gradle de la aplicación dinersclub-android.
![image](https://github.com/DiegoFelipe7/config-service/assets/90659322/ccd6e64b-1ed8-4958-82c1-607a2f34d7e1)


**settings.gradle**:Agrega una línea para incluir el nuevo módulo en el archivo settings.gradle de la aplicación dinersclub-android.
![image](https://github.com/DiegoFelipe7/config-service/assets/90659322/8f802b78-ee50-48f2-8394-9d2d85633355)

## Paso 3: Sincronización y Reconstrucción del Proyecto
Sincroniza los cambios en Gradle y reconstruye el proyecto para asegurarte de que todas las dependencias se resuelvan correctamente.
Con estos pasos completados, estaria listo para ejecutar la aplicación Android dinersclub-android en tu entorno de desarrollo local.

## Paso 4: Ejecución local
Con los pasos anteriores completados, la aplicación dinersclub-android está lista para ser ejecutada en tu entorno local. Utiliza tu IDE preferido
![image](https://github.com/DiegoFelipe7/config-service/assets/90659322/6175414b-afd3-4c92-9c81-0376fa7baa64)
