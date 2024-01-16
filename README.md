# 04-peliculasJScriptApp
Aqui desarrollamos el ejemplo del curso de udemy que empieza en la sección 10 Aplicacion de Peliculas

**Comando para crear este proyecto**

```npx react-native init AwesomeTSProject --template react-native-template-typescript --version 0.68.2```


**Para ejecutarloa**

Bastará con ejecutar este comando:

```npm run android```

**Links externos** 
Esta es el backend que consume esta aplicacion. Usuario: losorio75

https://www.themoviedb.org/?language=es

Para acceder tenes que tener un usuario y password ya que son personalizados.
Para ver mi token tenes que iniciar, ir a Configuraciones y luego a API. Ahi vas a tener la clave API y el Token de acceso.

**Fase de Navegacion**
Para la navegación tendremos que hacer lo siguiente:

sitio oficial para copiarnos el navegador
https://reactnavigation.org/docs/getting-started

***Paso 1***
```npm install @react-navigation/native```

***Paso 2***
Tenemos que instalar estas dependencias

```npm install react-native-screens react-native-safe-area-context```

***Paso 3***
En este paso ya podemos utilizar por medio del import la navegación en nuestro archivo principal de app.tsx.

```
import { NavigationContainer } from '@react-navigation/native';
```

***Paso 4***
Ahora falta instalar la parte de stack (eso esta en Navitators/Stack)

```npm install @react-navigation/stack```

***Paso 5***
Creamos el archivo navigation.tsx que contiene todas las paginas que voy a navegar.



**Notas**
Si vamos a trabajar en IOS hay que eliminar el uso de flipper

```ios/PodFileuse_flipper!()```

