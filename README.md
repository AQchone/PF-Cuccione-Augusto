## Iniciar GIT

colocamos lo siguiente 

```
git init
```
despues de eso agregamos todos los cambios a git con


```
git add .
```
hacemos un commit con lo que modificaron

```
git commit -m "primer commit"
```

y unimos el git al master 


```
git branch -m main / master
```

despues agregamos el git a github

```
git remote add origin "https..."
```
y pandamos todo los archivos a github

```
git push -u origin main / master
```

## Instalacion

Instalamos npm en el proyecto

```bash
  npm init

```
## Modificamos el script del archivo package.json

colocamos lo siguiente 

```bash
"build-sass": "node-sass --include-path scss ./scss/style.scss ./css/style.css -w"
```

luego creamos las carpetas scss y css e instalamos lo siguiente
```bash
npm i -D node-sass

```

Finalmente corremos sass con 
```bash
npm run build-sass

```

## Descargamos el proyecto y corremos para reinstalar las dependencias

```bash
npm install

```


Una vez instalado corremos sass con 
```bash
npm run build-sass

```

