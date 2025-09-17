# Laboratorio-06-Sesión-11
## 🚀 Ejercicio 1: Temporizador con useState y useEffect

### 🎯 Objetivo
Construir un temporizador que comience en **10** y llegue hasta **0**, mostrando un mensaje de finalización.

### 📝 Pasos
1. Crear un estado `timeLeft` con valor inicial `10`.
2. Usar `useEffect` con `setInterval` para disminuir `timeLeft` en 1 cada segundo.
3. Detener el temporizador cuando llegue a `0` (`clearInterval`).
4. Mostrar el mensaje **"¡Tiempo terminado!"** al finalizar.

### 💻 Código

<img width="763" height="719" alt="image" src="https://github.com/user-attachments/assets/1760af7d-5fbe-4f97-b3f9-d80e0261c9a8" />

### 🪄 Resolución

<img width="309" height="607" alt="image" src="https://github.com/user-attachments/assets/cc9f4008-ab26-4d5c-8d82-188eb411be79" />
<img width="291" height="609" alt="image" src="https://github.com/user-attachments/assets/b30955f5-f37d-44e4-9f59-288abae78dfe" />

## 🚀 Ejercicio 2: Formulario de Login con limpieza automática

### 🎯 Objetivo

Construir un formulario de login que:

Reciba usuario y contraseña.

Al presionar "Iniciar sesión" muestre un mensaje de bienvenida.

Limpie automáticamente los campos después de enviar.

### 📝 Pasos

1. Crear estados username, password y submitted.

2. Al presionar el botón:

- Mostrar un Alert con el nombre ingresado.

- Cambiar submitted a true.

3. Usar useEffect que dependa de submitted:

- Si es true, limpiar los campos y resetear submitted.

### 💻 Código

<img width="625" height="784" alt="image" src="https://github.com/user-attachments/assets/f893e08f-c6ca-4dca-8059-85dc067e4f8c" />

### 🪄 Resolución

<img width="306" height="615" alt="image" src="https://github.com/user-attachments/assets/2204649b-8382-46bf-b6fc-213d3be6af3e" />
<img width="309" height="615" alt="image" src="https://github.com/user-attachments/assets/c8daebe9-dc9a-4a74-8611-7418b38fd0a7" />
<img width="308" height="610" alt="image" src="https://github.com/user-attachments/assets/6e073aba-64a6-4184-99bb-cdeed30e8481" />
<img width="305" height="625" alt="image" src="https://github.com/user-attachments/assets/f6aecc4f-0984-425c-b727-db5840f6de5c" />
<img width="295" height="616" alt="image" src="https://github.com/user-attachments/assets/6168f5a6-a069-4e6d-8776-75cf8e74739e" />






