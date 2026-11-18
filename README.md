# Actividad Grupal: Manejo de Merge en GitHub — Grupo D

**Universidad de Guayaquil**  
**Facultad de Ciencias Matemáticas y Físicas**  
**Carrera de Software**  
**Asignatura:** Gestión de la Configuración del Software (Unidad 2 — Semana 3)  
**Docente:** Ing. Franklin Ricardo Parrales Bravo  
**Grupo:** Grupo D  

---

## 🎥 Video de Entrega (YouTube)

> **Enlace al video (3–5 minutos):** *(Pendiente de publicar — pegar aquí el enlace de YouTube)*  
> `https://youtu.be/PENDIENTE`

El video documentará:
- El repositorio en GitHub con las ramas creadas por los integrantes.
- La explicación de los cambios realizados en cada rama.
- La demostración del proceso de **Pull Request (PR)**, **merge** hacia `main` y **resolución de conflictos**.
- Grabación y/o capturas de pantalla del proceso colaborativo.

---

## 🎯 Objetivo de Aprendizaje

Aplicar los conceptos de control de versiones y gestión de cambios mediante el uso de GitHub, específicamente realizando operaciones de *branching*, *Pull Request*, *merge* entre ramas y resolución de conflictos en un proyecto colaborativo.

---

## 👥 Integrantes — Grupo D

| # | Integrante | Rama sugerida | Estado |
| :-: | :--- | :--- | :-: |
| 1 | Jefferson Xamir Anchundia Peñaherrera | `feature/jefferson-anchundia` | ⏳ Pendiente |
| 2 | María Fernanda Chourio Linares | `feature/maria-chourio` | ⏳ Pendiente |
| 3 | Everaldo Alejandro Fernández Villamar | `feature/everaldo-fernandez` | ⏳ Pendiente |
| 4 | Mario Mauricio Jacho Cedeño | `feature/mario-jacho` | ⏳ Pendiente |
| 5 | Rubén Alfredo Quiroga Peralta | `feature/ruben-quiroga` | ⏳ Pendiente |
| 6 | Ronny Andrés Sánchez Moriel | `feature/ronny-sanchez` | ⏳ Pendiente |
| 7 | Alonso Mikkail Serrano Abarca | `feature/alonso-serrano` | ⏳ Pendiente |
| 8 | Elías Hernán Vera Landázuri | `feature/elias-vera` | ⏳ Pendiente |
| 9 | Danna Briggitte Vera Moreira | `feature/danna-vera` | ⏳ Pendiente |
| 10 | Luis Enrique Vera Sabando | `feature/luis-vera` | ⏳ Pendiente |

---

## 📝 Registro de Aportes por Integrante

*(Cada integrante agregará su aporte desde su rama `feature/[NOMBRE]` y lo integrará a `main` mediante un Pull Request).*

- *Aportes pendientes de integración...*

---

## 🔄 Flujo de Trabajo (Procedimiento)

### 1. Clonar el repositorio
```bash
git clone [URL_DEL_REPOSITORIO]
cd gcsw-u2-s3-github-merge-grupo-d
```

### 2. Crear una rama individual a partir de `main`
```bash
git checkout main
git pull origin main
git checkout -b feature/[NOMBRE]
```

### 3. Realizar cambios y confirmar (*commit*)
Edita el archivo correspondiente (por ejemplo, `README.md` o un archivo de aporte en el repositorio) y guarda los cambios:
```bash
git add .
git commit -m "feat: agregar aporte de [NOMBRE]"
```

### 4. Subir la rama y crear un Pull Request (PR)
```bash
git push -u origin feature/[NOMBRE]
```
Luego, en GitHub:
1. Abrir un **Pull Request (PR)** desde `feature/[NOMBRE]` hacia `main`.
2. Describir claramente los cambios realizados.

### 5. Revisión, resolución de conflictos y *merge*
1. Los demás integrantes revisan el Pull Request.
2. Si existen conflictos con `main`, se resuelven en conjunto antes de aprobar.
3. Aprobar el PR y ejecutar el **merge** hacia `main`.

### 6. Verificación local
```bash
git checkout main
git pull origin main
```

---

## 📊 Criterios de Evaluación

| Criterio | Ponderación |
| :--- | :-: |
| Correcta aplicación de los conceptos de GitHub | 50 % |
| Calidad de la explicación en el video | 30 % |
| Trabajo colaborativo demostrado | 20 % |
