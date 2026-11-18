<div align="center">

# 🦔 Taller Echidna Black 2

**Programación de sensores y actuadores con Echidna ML**
Club Robótica Granada · OpenLab del Parque de las Ciencias

[![echidna.es](https://img.shields.io/badge/🌐_Web_oficial-echidna.es-2b7a78?style=for-the-badge)](https://echidna.es)

</div>

---

## 🧭 Punto de partida

> Toda la documentación, el software y los manuales del proyecto están en la web oficial.

### 👉 [**echidna.es**](https://echidna.es)

| Recurso | Enlace |
|---|---|
| 🌐 Web principal del proyecto Echidna | [echidna.es](https://echidna.es) |
| 💻 Descarga e instalación de **Echidna ML** | [echidna.es/a-programar/echidnaml](https://echidna.es/a-programar/echidnaml/) |

---

## 📋 Guion de la sesión

Esquema completo del taller: ecosistema, conectividad, ejemplos de Echidna ML y ejemplos de Arduino IDE.

| Formato | Descarga |
|---|---|
| 📄 PDF (para leer) | [taller_echidna.pdf](guion/taller_echidna.pdf) |
| ✏️ ODT (editable) | [taller_echidna.odt](guion/taller_echidna.odt) |

---

## 🧩 Programas de Scratch (.sb3)

Proyectos propios del taller, hechos con las extensiones de **Echidna**. Descarga el archivo y ábrelo desde **Echidna ML** (*Archivo → Cargar desde tu ordenador*).

| # | Programa | Qué hace | Entrada → Salida | Descarga |
|:-:|---|---|---|:-:|
| 1 | **Sensor de luz progresivo** | El brillo del LED verde varía de forma gradual según la luz ambiente | 💡 Sensor de luz → 🟢 LED | [⬇️ .sb3](programas/sensor_luz_progresivo.sb3) |
| 2 | **Sensor de luz y paisajes** | Cambia el paisaje en pantalla según el nivel de luz | 💡 Sensor de luz → 🖼️ Escenario | [⬇️ .sb3](programas/sensor_luz_paisaje.sb3) |
| 3 | **Movimiento de erizo** | Mueve al erizo por la pantalla con el joystick | 🕹️ Joystick → 🦔 Objeto | [⬇️ .sb3](programas/movimiento_erizo.sb3) |
| 4 | **RGB aleatorio** | Genera colores aleatorios en el LED RGB | 🎲 Aleatorio → 🌈 LED RGB | [⬇️ .sb3](programas/rgb_aleatorio.sb3) |
| 5 | **Gráfica de luz** | Dibuja con el lápiz la gráfica de la luz medida a lo largo del tiempo | 💡 Sensor de luz → ✏️ Lápiz | [⬇️ .sb3](programas/grafica_luz.sb3) |

---

## 🔌 Antes de empezar

- **Conexión:** la placa funciona con *Firmata estándar* y solo trabaja conectada al PC.
- **Drivers:** instalar el controlador **CH340** si el ordenador no reconoce la placa.
- **Linux:** si la placa no responde, añadir tu usuario al grupo `dialout`:
  ```bash
  sudo usermod -a -G dialout $USER
  ```
- **Software:** traer instalado **Echidna ML** ([guía de instalación](https://echidna.es/a-programar/echidnaml/)).

---

## 🗺️ Itinerario de la sesión

### 1️⃣ La web de Echidna
Presentación del proyecto Echidna (dotación a centros andaluces) en [echidna.es](https://echidna.es):

- **Ecosistema:** características de la placa **Echidna Black 2**, instalación de **Echidna ML**, **Arduino IDE**, etc.
- **Recursos docentes:** manuales y otros recursos (comprobar la placa).
- **Conectividad:** Firmata estándar, instalación de drivers (CH340) y permisos en Linux; la placa solo funciona conectada al PC.
- **Sobre el proyecto:** quiénes son.

### 2️⃣ Ejemplos

**Programas de test** para probar las placas.

**Ejemplos de Echidna ML** *(⭐ = programa propio, descargable arriba)*

| Nº | Ejemplo |
|:-:|---|
| 00 | Hola mundo |
| 01 | Fade |
| 01 | Semáforo |
| 02 | Apagar/encender LED con un pulsador |
| 02 | Pulsador/LED con memoria |
| 03 | Pulsador/zumbador |
| 04 | Sensor de luz/LED: interruptor crepuscular |
| ⭐ | [Sensor de luz progresivo](programas/sensor_luz_progresivo.sb3) |
| ⭐ | [Sensor de luz paisajes](programas/sensor_luz_paisaje.sb3) |
| 05 | Joystick: pintamos |
| ⭐ | [Movimiento de erizo con joystick](programas/movimiento_erizo.sb3) |
| 06 | Acelerómetro: movemos el erizo |
| 07 | Dice la temperatura |
| ⭐ | [RGB aleatorio](programas/rgb_aleatorio.sb3) |
| 08 | Termómetro RGB |
| 09 | Vúmetro (sin media) |
| ⭐ | [Gráfica de luz](programas/grafica_luz.sb3) |
| 10 | MK-MK piano |
| — | LML: modelo de texto |
| — | LML: modelo de imagen |

**Ejemplos de Arduino IDE**

- 2.10 Vúmetro (mejorarlo con gráfica)
- 2.11 Regulador de luz con joystick
- 2.12 Nivel de burbuja

---

<div align="center">

**Ponente:** Pedro Ruiz · [Club Robótica Granada](https://echidna.es) · Granada, 2026

*Materiales de uso educativo. Más recursos en* **[echidna.es](https://echidna.es)**

</div>
