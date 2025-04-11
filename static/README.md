# Hello World Flask - Python Project

En este proyecto generaremos un proyecto en Python de un "Hello World" simple y lo subiremos a GitHub.

---

## PASO 1

Abrimos Visual Studio Code y verificamos que tenga Python:

```bash
python --version
```

---

## PASO 2

### Crear el entorno virtual:

```bash
python -m venv venv
```

### Activar el entorno:

```bash
venv\Scripts\activate
```

### Instalar Flask:

```bash
pip install flask
```

### Desarrollamos el proyecto o lo modificamos

---

### Ejecutar el proyecto:

```bash
python app.py
```

---

## PASO 3: Subir a GitHub

Abrimos GitHub, nos autenticamos y creamos un repositorio vacío.

Después vamos a la carpeta de nuestro proyecto y en la terminal ejecutamos:

```bash
git init
git remote add origin https://github.com/Bryan03A/HelloWorldPY.git
```

### Renombrar la rama `main` a `test`:

```bash
git checkout -b test
```

> Nota: Esto crea y cambia a la rama `test` (si estás en `main`, puedes eliminarla luego).

---

## PASO 4: Borrar todo lo anterior del repositorio remoto y subir

```bash
git add .
git commit -m "Subiendo proyecto Flask Hello World"
git push -u origin test --force
```

---

## PASO 5 (opcional): Eliminar la rama `main` en remoto

```bash
git push origin --delete main
```

---

## ✅ ¡Listo!

Verifica que los cambios se hayan hecho en tu repositorio GitHub:  
[https://github.com/Bryan03A/HelloWorldPY](https://github.com/Bryan03A/HelloWorldPY)