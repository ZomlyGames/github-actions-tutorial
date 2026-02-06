# despr5_1

## Ejercicios ya resuletos

### Parte 1: Hello World workflow

#### Paso 1: Crear repositorio

![Creación repositorio](./img/image1.png)

#### Paso 2: Clonar repositorio

#### Paso 3: Crear estructura de workflows

#### Paso 4: Crear primer workflow

![Creación repositorio](./img/image2.png)

#### Paso 5: Commit y push

#### Paso 6: Ver ejecución

![Ejecución](./img/image3.png)
![Detalles](./img/image4.png)

### Parte 2: Workflow con checkout

#### Paso 7: Crear workflow con código

![Crear workflow](./img/image5.png)

#### Paso 8: Push y verificar

![Verificación](./img/image7.png)

### Parte 3: Triggers avanzados

#### Paso 9: Workflow solo en main

![Creación](./img/image8.png)
![No se ejecuta](./img/image9.png)
![Push desde main](./img/image10.png)
![Ahora se ejecuta](./img/image11.png)

#### Paso 10: Workflow con pull requests

![Creación](./img/image12.png)
![Verificación](./img/image13.png)

#### Paso 11: Workflow manual

![Creación](./img/image14.png)

#### Paso 12: Ejecutar manualmente

![Introducción valores inputs](./img/image16.png)
![Resultado](./img/image17.png)

### Parte 4: Workflow con múltiples jobs

![Creación](./img/image18.png)
![Subida workflow](./img/image19.png)
![Comprobación](./img/image20.png)

### Parte 5: Variables de entorno

![Creación](./img/image21.png)
![Comprobación](./img/image24.png)

### Parte 6: Condicionales

![Creación](./img/image25.png)
![Comprobación](./img/image28.png)

### Parte 7: Strategy Matrix

![Creación](./img/image29.png)
![Comprobación](./img/image31.png)

#### Paso 13: Matrix con exclude

![Creación](./img/image32.png)
![Comprobación](./img/image33.png)

#### Paso 14: Matrix con include

![Creación](./img/image34.png)
![Comprobación](./img/image35.png)

#### Paso 15: Matrix fail-fast

![Creación](./img/image36.png)
![Comprobación](./img/image37.png)

## Ejercicios

### Ejercicio 1: Workflow personalizado

![Creación](./img/image38.png)
![Comprobación](./img/image39.png)

Con schedule cron se puede marcar en qué momento o momentos se pueden ejecutar el workflow. Los pasos que hace son, mostrar el mensaje motivacional mediante echo y mostrar los últimos 5 commits

### Ejercicio 2: Calculator workflow

![Introducción números](./img/image40.png)
![Comprobación](./img/image41.png)

Con workflow_dispatch se hace que la ejecución sea manual (habrá que introducir los 2 números para que se ejecute). Una vez introducido hará un único paso que consiste en calcular y mostrar los resultados (el if es para evitar la división entre 0).

### Ejercicio 3: Multi-OS workflow

![Comprobación Ubuntu](./img/image42.png)
![Comprobación Windows](./img/image43.png)
![Comprobación Macos](./img/image44.png)

El workflow se ejecutará en distintos sistemas operativos gracias a matrix (que hace que se repita para cada una de las posibles opciones) y a "os" que indica el sistema operativo
