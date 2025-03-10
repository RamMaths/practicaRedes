# Práctica de Administración de redes

Servidor web simple para la práctica de Administración de redes.


## Pasos para correr el servidor en tu red local

### Linux / MacOS

1. Descarga `node.js` de la [página oficial](https://nodejs.org/es).

2. Descarga este proyecto en tu computadora usando git.

```sh
git clone https://github.com/RamMaths/practicaRedes.git
cd practicaRedes
```

También puedes descargar el archivo con extensión `.zip` y descomprimirlo

```sh
unzip practicaRedes-main.zip 
cd practicaRedes-main
```

3. Comprueba que tienes `node.js` instalado

```sh
node --version
npm --version
```

4. Instala las dependencias

```sh
npm install
```

5. Corre el servidor en tu red local!

```sh
export PORT=8080
PORT=$PORT node app.js -- --host --port $PORT
```

### Windows

1. Descarga `node.js` de la [página oficial](https://nodejs.org/es).

2. Descarga este proyecto en tu computadora usando git

```sh
git clone https://github.com/RamMaths/practicaRedes.git
cd practicaRedes
```

También puedes descargar el archivo `.zip` descomprimirlo, entrar en la carpeta y abrir una terminal en dicha carpeta.

3. Comprueba que tienes `node.js` instalado

```sh
node --version
npm --version
```

4. Instala las dependencias

```sh
npm install
```

5. Corre el servidor en tu red local!

- Si usas `Command Prompt`

```sh
set PORT=8080
node app.js -- --host --port %PORT%
```

- Si usas `Powershell`

```sh
$env:PORT = 8080
node app.js -- --host --port $env:PORT
```
