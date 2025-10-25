# POO-Git-Casos
Desarrollo de Casos Prácticos - POO y Git

# Desarrollo de Casos Prácticos - POO y Git

Este repositorio contiene los ejercicios prácticos del curso de **Programación Orientada a Objetos (POO)**, integrando el uso de **Git y GitHub** para la gestión de versiones y documentación del desarrollo.

---

## 🧩 Actividades esperadas

- Desarrollar guía de primeros pasos con Git.  
- Crear repositorio local y clonar uno desde GitHub.  
- Navegación básica por el repositorio (`git status`, `git log`).  
- Realizar el primer commit, registrar cambios con `git add` y `git commit`.  
- Visualizar el historial de commits.  
- Crear ramas (`git branch`) y cambiar entre ellas (`git checkout`).  
- Fusionar ramas (`git merge`).  
- Publicar el proyecto en un repositorio compartido en GitHub.  
- Documentar el uso de Git en el archivo `guia_git.md`.  
- Desarrollar los casos planteados.  
- Subir el código fuente, guía y reporte final al repositorio.

---

## 📂 Estructura sugerida del repositorio

POO-Git-Casos/
├── caso1/
│ └── UsuarioSimple.java
├── caso2/
│ └── EstudianteInteractivo.java
├── caso3/
│ └── CuentaBancaria.java
├── guia_git.md
├── informe_final.pdf
└── README.md

---

## Casos prácticos

### CASO 1: Lectura de datos simples con Scanner

**Consigna:**  
Desarrolla un programa en Java que solicite datos por teclado usando la clase `Scanner`.  
El programa debe ser guardado en la carpeta `caso1/` y subido al repositorio con commits explicativos.

**Sugerencia de archivo:**  
`caso1/UsuarioSimple.java`

**Ejemplo de commits:**
```bash
git add caso1/UsuarioSimple.java
git commit -m "Caso 1: se crea programa que solicita datos con Scanner"
git push
```

### CASO 2: Clase Estudiante con atributos privados
**Consigna:**  
Implementa una clase Java llamada `Estudiante` con atributos privados, constructor y métodos `get/set`. 
El estudiante debe ser creado desde el método `main()` y sus datos deben ser mostrados con uso de Scanner. 
Publica tu código en `caso2/`.

**Sugerencia de archivo:**  
`caso2/EstudianteInteractivo.java`

**Ejemplo de commits:**
```bash
git add caso1/UsuarioSimple.java
git commit -m "Caso 2: se crea programa para estudiante"
git push
```

### CASO 3: Clase CuentaBancaria con validación
**Consigna:**  
Crea una clase Java llamada `CuentaBancaria` que permita operaciones básicas como depositar y retirar, validando que no se retire más del saldo. 
Usa Scanner para el ingreso de datos. 
El código debe estar en la carpeta `caso3/` con commits bien documentados.

**Sugerencia de archivo:**  
`caso3/CuentaBancaria.java`

**Ejemplo de commits:**
```bash
git add caso1/UsuarioSimple.java
git commit -m "Caso 3: se crea programa para cuenta bancaria"
git push
```