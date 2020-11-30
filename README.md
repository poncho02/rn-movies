# RN Movies

_App de ejemplo_

## Comenzando

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

_Clona el repositorio desde:_

```
git clone https://github.com/poncho02/rn-movies.git
```

### Pre-requisitos 📋

_Para correr el app, necesitas preparar el ambiente, revisar la documentación de React native_

```
https://reactnative.dev/docs/environment-setup
```

Donde debes elegir la pestaña de:

```
React Native CLI Quickstart
```

Seleccionas el Development OS, para seguir las instrucciones correspondientes.

```
windows o macOS
```

Seleccionas el Target OS, para ejecutar los dos emuladores, debes de seguir ambas instrucciones por separado.

```
android o IOS, o ambos si deseas las dos plataformas
```

El proceso de configuración termina en la sección de de Creating a new application.


### Instalación de App básica

Para revisar y confirmar tu configuración del ambiente, puedes crear un proyecto básico.


```
npx react-native init AwesomeProject
```

Una vez terminada la instalación del proyecto


```
cd AwesomeProject
npx react-native start
```

Inicia la aplicacion en android

```
npx react-native run-android
```

Inicia la aplicacion en IOS

```
npx react-native run-ios
```

Si todo salio bien , deberías ver los dos emuladores con la pagina de inicio de React. Caso contrario, la configuración tiene errores.


### Ejecutar app de movies

Si ya probaste tu configuración, solo instala los paquetes del proyecto, dirigite a la carpeta del proyecto y ejecuta:


```
cd rn-movies
yarn install
```

iOS necesita un paso extra, ejecuta

```
cd ios
pod install
cd ..
```

Para android no se necesita nada extra.


Con esto, ya puedes correr el proyecto, ejecuta:

```
npx react-native run-ios y npx react-native run-android
```

### Terminado 
