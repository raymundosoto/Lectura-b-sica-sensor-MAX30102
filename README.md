# Lectura-básica-sensor-MAX30102
Funcionamiento básico del sensor de ritmo cardiaco y saturación de oxígeno
En este repositorio se muestra el funcionamiento básico del sensor MAX30102 usando el ESP32-CAM 

Las conexiones entre el sensor y el ESP32CAM deben ser las siguientes:
  
  -5V = 5V (3.3V es permitido)
  -GND = GND
  -SCL = 14 (or SDA)  (En el código de arduino están al revés, pero aquí funcionan así)
  -SDA = 15 (or SCL)
  -INT = No conectar
  - Poner resistencias de 4.7 K ohms entre SDA y 5V, SCL y 5V.
  - Colocar el monitor serial, después del reset del ESP32 CAM en 9600 baudios. Durante la carga del código mantener en 115200
  
  # Circuito conectado
  
  ![imagen](https://user-images.githubusercontent.com/72757419/184510872-e36f4267-0ef9-4e2b-8e12-ae491707b5f6.png)
  
Sensor MAX30102
![imagen](https://user-images.githubusercontent.com/72757419/184510908-8ec2a5ae-fa29-4ba1-b203-8d0f3dd8a494.png)

Lecturas del sensor

![imagen](https://user-images.githubusercontent.com/72757419/184510887-4f59c028-f8b9-48eb-a592-f2c7de11b668.png)

  
  
