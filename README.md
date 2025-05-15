# 💣 Reto CTF: Lower1

> Creado por [4Mart1](https://github.com/4mart1nez) 
> Mayo 2025 · Nivel: Fácil · Linux · Escalada local

---

## 📘 Descripción

`Lower1` es una máquina vulnerable tipo CTF diseñada para jugadores que se inician en el pentesting.  
El reto incluye un acceso inicial mediante **FTP anónimo o vulnerabilidad LFI**, y una posterior **escalada de privilegios** a través de un binario con SUID.

Ideal para practicar:

- Enumeración básica de servicios
- Acceso a través de LFI o FTP
- Escalada de privilegios local
- Gestión de flags

---

## ⚙️ Información técnica

- 🐧 Sistema operativo: Debian 12 (sin entorno gráfico)
- 🌐 Servicios activos:
  - FTP anónimo (vsftpd)
  - Web Apache con PHP vulnerable a LFI
- 🎯 Escalada de privilegios: binario con permisos SUID

---

## 🎯 Objetivo del reto

1. Accede como el usuario `ctfplayer`
2. Encuentra la flag en `/home/ctfplayer/flag.txt`
3. Escala privilegios a `root`
4. Lee la flag final en `/root/root.txt`

---

## 🧾 Credenciales

- Usuario: `ctfplayer`
- Contraseña: `ctf1234`

---

## 📥 Importación de la máquina

1. Abre VirtualBox
2. Ve a `Archivo > Importar servicio virtualizado`
3. Selecciona el archivo `Lower1.ova`
4. Asegúrate de marcar **"Reinicializar dirección MAC de red"**
5. Inicia la máquina

---

## 🏁 Flags

- 🧷 Usuario: `/home/ctfplayer/flag.txt`
- 👑 Root: `/root/root.txt`

---

## 🖋️ Autor

- **Nombre:** Álvaro Martínez
- 🌐 GitHub:(https://github.com/4mart1nez)
- 🐦 Linkedin:(www.linkedin.com/in/4martinez)

---

## ✅ ¿Funcionó el reto?

Si te gustó, compártelo con tu comunidad 🔁  
Y no olvides mencionarme para seguir creando máquinas 🔧💀
---

## ⚠️ Aviso Legal

Esta máquina vulnerable ha sido creada exclusivamente con fines **educativos, formativos y de concienciación en ciberseguridad**.

Está diseñada para su uso en **entornos controlados**, como laboratorios virtuales o CTFs, y **no debe utilizarse en sistemas reales ni en redes no autorizadas**.

El autor, Álvaro Martínez, no se responsabiliza del uso indebido de esta máquina ni de las consecuencias derivadas de su distribución o explotación fuera de un entorno ético.

⚖️ **Respeta la ley y el hacking ético.**
