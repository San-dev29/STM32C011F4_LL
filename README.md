# STM32C011F4 - Embedded System Project

# 

# Este repositorio contiene el firmware desarrollado en C para el microcontrolador STM32C011F4. El proyecto se centra en usar la capa LL para no exceder los 16kB de Flash del MCU.

# 

# 🛠️ Hardware y Ecosistema

## \*\*Microcontrolador:\*\* STM32C011F4 (ARM Cortex-M0+)

## \*\*Entorno de Desarrollo:\*\* STM32CubeIDE

## \*\*Herramientas de Depuración:\*\* ST-Link V2 / OpenOCD

# \*\*Capa de Abstracción:\*\* Low-Level (LL)



# ⚙️ Periféricos y Características

# El sistema implementa la configuración y uso de los siguientes periféricos:

## \*\*GPIO / EXTI:\*\* Control de interrupciones externas.

## \*\*ADC:\*\* Lectura de señales analógicas.

## \*\*TIM (Timers):\*\* Generación de señales PWM y temporización de hardware.

## \*\*Comunicaciones:\*\*

## &#x20; \*\*USART:\*\* Transmisión de datos en serie.

## &#x20; \*\*I2C \& SPI:\*\* Interfaz con sensores y módulos externos.

# 

# \## Cómo compilar y ejecutar

## 1\. Clona este repositorio: `git clone https://github.com/TuUsuario/STM32C011F4\_LL.git`

## 2\. Importa el proyecto en tu espacio de trabajo de STM32CubeIDE (`File > Import > Existing Projects into Workspace`).

## 3\. Compila el proyecto utilizando el botón del martillo (Build).

## 4\. Conecta el ST-Link V2 a los pines SWD del microcontrolador y presiona el botón de Debug para flashear el código `.elf` generado.

# 

# \---

# \*\*Autor:\*\* Santiago Ventura González

# \*Estudiante de Ingeniería Mecatrónica\*

