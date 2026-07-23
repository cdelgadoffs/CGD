# 🚀 Guía Rápida de GitHub y Comandos Básicos

¡Bienvenido a este repositorio de aprendizaje! Este documento sirve como una referencia rápida para entender qué es un repositorio y cuáles son los comandos esenciales de Git que utilizarás en tu día a día.

## 📁 ¿Qué es un Repositorio de GitHub?

Un **repositorio** (o *repo*) es el espacio virtual donde se almacenan todos los archivos de tu proyecto, junto con el **historial de cambios** de cada uno de ellos. 

### Tipos de repositorios:
* **Públicos:** Cualquier persona en Internet puede ver el código (ideal para proyectos de código abierto).
* **Privados:** Solo tú y los colaboradores que elijas explícitamente pueden ver el contenido.

---

## 🛠️ Comandos Básicos de Git

Para usar estos comandos, necesitas tener Git instalado en tu computadora y abrir tu terminal.

### 1. Configuración Inicial
Configura tu identidad antes de registrar cambios (solo se hace una vez).
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu-correo@example.com"
```

### 2. Comenzar un Proyecto

| Comando | Descripción |
| :--- | :--- |
| `git init` | Inicializa un repositorio local en la carpeta actual. |
| `git clone <url-del-repo>` | Descarga una copia exacta de un repositorio de GitHub a tu computadora. |

### 3. El Ciclo de Trabajo Diario
Sigue estos tres pasos en orden para registrar tus cambios y enviarlos a la nube:

1. **Preparar los archivos:** Añade los archivos modificados al área de preparación (Staging Area).
   ```bash
   git add nombre-del-archivo.txt
   # O usa el siguiente comando para añadir TODO lo que cambiaste:
   git add .
   ```
2. **Confirmar los cambios:** Guarda una especie de "foto" o versión de tus archivos con un mensaje descriptivo.
   ```bash
   git commit -m "Explicación breve del cambio realizado"
   ```
3. **Enviar a GitHub:** Sube tus confirmaciones locales al repositorio remoto en la nube.
   ```bash
   git push origin main
   ```

### 4. Actualizar tu Código Local
Si trabajas en equipo y alguien más subió cambios a GitHub, descarga la última versión con:
```bash
git pull
```

---

## 💡 Buenas Prácticas
* **Escribe mensajes de commit claros:** Usa frases como `"Corrección de error en el inicio de sesión"` en lugar de `"Cambios"`.
* **Crea un archivo `.gitignore`:** Sirve para decirle a Git qué archivos o carpetas pesadas/secretas **no** debe subir a GitHub.

---
_Creado con ❤️ para la comunidad de aprendizaje de GitHub._
