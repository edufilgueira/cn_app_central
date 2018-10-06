# Congfigurar o build arduino via shell

### Instalando o IDE Arduino
```
sudo apt-get update && sudo apt-get upgrade
```

```
sudo apt-get install arduino
```

```
sudo apt-get install avr-libc libftdi1 avrdude openjdk-6-jre librxtx-java
```

### Preparando o arduino pelo terminal

```
sudo apt-get install arduino-mk
```

### Preparando o projeto shell

https://www.youtube.com/watch?v=_EKwvHQctyY

1. criar a pasta sketchbook

```
mkdir sketchbook
```
Copia o arquivo _Arduino.mk_ para a pasta criada

```
ln -s /usr/share/arduino/Arduino.mk

```
