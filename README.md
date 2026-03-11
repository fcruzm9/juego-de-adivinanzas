# 🎯 Adivina el Número

Práctica del módulo **Programación Python** — Universidad Complutense de Madrid  
Autor: **Felipe Cruz**

---

## 📋 Descripción

Juego de adivinanza en Python donde el jugador intenta adivinar un número entre 1 y 1000.  
Los resultados de cada partida se guardan automáticamente en un fichero Excel y se pueden consultar con gráficos desde el menú de estadísticas.

---

## 🕹️ Modos de juego

| Modo | Descripción |
|------|-------------|
| **Solitario** | El ordenador genera el número aleatoriamente |
| **2 Jugadores** | El Jugador 1 escribe el número y el Jugador 2 lo adivina |

### Dificultades disponibles

| Nivel | Intentos |
|-------|----------|
| Fácil | 20 |
| Medio | 12 |
| Difícil | 5 |

---

## 📁 Estructura del repositorio

```
adivina-el-numero/
│
├── adivina_el_numero.py   # Código principal del juego
├── Estadisticas.xlsx      # Excel vacío con cabeceras (se rellena al jugar)
└── README.md              # Este fichero
```

---

## ⚙️ Instalación

### 1. Clona el repositorio
```bash
git clone https://github.com/tu-usuario/adivina-el-numero.git
cd adivina-el-numero
```

### 2. Instala los paquetes necesarios
```bash
pip install openpyxl matplotlib
```

> `random` y `os` ya vienen incluidos en Python, no hace falta instalarlos.

---

## ▶️ Ejecución

### Desde terminal
```bash
python adivina_el_numero.py
```

### Desde Jupyter Notebook
Abre el fichero `.py` directamente en Jupyter o copia el contenido en una celda y ejecútala.

---

## 📊 Estadísticas

Al finalizar cada partida se guarda automáticamente en:

- **Windows:** `C:\EjerciciosPython\Estadisticas.xlsx`  
- **Mac / Linux:** `~/EjerciciosPython/Estadisticas.xlsx`

Desde el menú principal, la opción **3. Estadística** muestra:
- Una tabla con todas las partidas jugadas
- Un gráfico de victorias y derrotas
- Un gráfico de partidas por dificultad

---

## 📦 Dependencias

| Paquete | Uso | Instalación |
|---------|-----|-------------|
| `openpyxl` | Leer y escribir el Excel | `pip install openpyxl` |
| `matplotlib` | Mostrar gráficos | `pip install matplotlib` |
| `random` | Generar número aleatorio | Incluido en Python |
| `os` | Rutas y limpiar pantalla | Incluido en Python |
