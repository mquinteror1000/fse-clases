# Tema 2

#### Perifericos = memoria

El cpu no ve sensor,  lo que el cpu vé es registros de memoria

- Para controlar los dispositivos: Lee / Escribe en los registros de memoria

##### Mapa de memoria

En la memoria encontramos las siguientes áreas

- ROM: Flash / Código

- RAM: Datos y Stack

- Perfericos: Periféricos ( MMIO )

- Registros del sistéma: NVIC( Nested Vector Interruption Control ) , SysTick

#### Memory Map Input /output ( MMIO )

- Periféricos exponen registros como posiciones de memoria

- cada registro ocupa una dirección específica

##### GPIO de la RPI

Casa pin de la GPIO está mapeado a una dirección

* GOPIO_BASE=0x3f200000
  
  * GPFSEL: Selección de función
  
  * GPSET: Porner en alto
  
  * GPCLR: Poner en cero

```c
registro = base + offset;
```

### GPFSEL

Un registro controla 10 pines

cada pin ocupa 3 bits

posición 

$registro = \frac{pin}{3}$

**Posibles configuraciones del un pin (modos)**:

- alta impedancia

- input

- output

- i2c

- spi

##### Acceso a la GPIO

codigo viene en la siapositiva 22

```c
#define GPIO_BASE 0x0
#define BLOCK_SIZE 4096

int main ()
{
    int fd   
}
```
