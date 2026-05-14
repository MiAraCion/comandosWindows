# MyCommands

Colección de comandos personalizados para Windows mediante archivos `.bat`.

> Para el funcionamiento correcto de los comandos, se deben configurar las variables de entorno y tener instalado el programa correspondiente.

---

# Comando `gitb`

## Función

Permite abrir **Git Bash** directamente en la ruta actual desde CMD o PowerShell.

---

## Ejemplo de uso

### Paso 1

Ubicarse en la carpeta del proyecto y ejecutar:

```bash
C:\Users\Usuario\Desktop\Proyecto> gitb
```

### Paso 2

Presionar `ENTER`.

Resultado esperado:

- Git Bash se abrirá automáticamente en:

```bash
C:\Users\Usuario\Desktop\Proyecto
```

### Paso 3

Agregar la carpeta donde están almacenados los scripts a las variables de entorno de Windows.

Ejemplo:

```bash
C:\MyCommands
```

---

# Comando `npm`

## Función

Reemplazar automáticamente `npm` por `pnpm`.

Esto permite que, al ejecutar accidentalmente comandos con `npm`, realmente se utilice `pnpm` para una instalación de dependencias más segura y eficiente.

---

## Ejemplo de uso

### Paso 1

Verificar la versión original de `npm`:

```bash
C:\Users\Usuario\Desktop\Proyecto> npm -v
11.1.1
```

### Paso 2

Verificar la versión de `pnpm`:

```bash
C:\Users\Usuario\Desktop\Proyecto> pnpm -v
11.11.1
```

> Observación: `npm` y `pnpm` son comandos distintos, por eso muestran versiones diferentes.

### Paso 3

Copiar el archivo `npm.bat` dentro de la carpeta donde almacenas tus scripts personalizados.

Ejemplo:

```bash
C:\MyCommands
```

### Paso 4

Agregar esa carpeta a las variables de entorno de Windows.

### Paso 5

Cerrar y volver a abrir la terminal.

Ahora, al ejecutar:

```bash
npm -v
```

El resultado debería ser la versión de `pnpm`:

```bash
11.11.1
```

Y al ejecutar:

```bash
pnpm -v
```

También debería devolver:

```bash
11.11.1
```

---

# Configuración de Variables de Entorno

Agregar la carpeta de scripts personalizados al `PATH` de Windows.

Ejemplo:

```bash
C:\MyCommands
```

Ruta recomendada para almacenar los `.bat`:

```bash
C:\MyCommands
```