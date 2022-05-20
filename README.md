
### Lista de comandos

```
ng serve
ng serve -c locale
ng serve -c production

ng build (por defecto ahora incluye --prod)
ng build -c development
ng build -c locale
```


### 2. Creando un ambiente personalizado
Se creo un ambiente personalizado *locale*. 

Para ello se creo un archivo `environment.locale.ts` y se tuvo que modificar el archivo `angular.json`



### 3. Probando nuestra compilación `ng-build`
Para probar la compilación del proyecto de forma local podemos utilizar el paquete http-server:
```
npm i -g http-server
```
Luego:
```
http-server dist/ng-environments-sample
```
