# 🔌 Protocolo RS232

El protocolo **RS-232** es uno de los más utilizados en comunicaciones seriales, especialmente en entornos industriales y de computación. Su función principal es definir cómo se transmiten y reciben datos entre dispositivos a través de comunicación serial asíncrona.

---

## 🔠 Código ASCII: historia y funcionamiento
El **American Standard Code for Information Interchange (ASCII)** fue creado en 1963 para unificar la representación de letras, números y símbolos en los sistemas de cómputo.  

- Inicialmente usó **7 bits = 128 caracteres**.  
- Luego se amplió a **8 bits = 256 caracteres**, añadiendo caracteres especiales.  

Esto permitió la comunicación consistente entre equipos de diferentes fabricantes.  

<p align="center">
  <img width="319" height="319" alt="image" src="https://github.com/user-attachments/assets/734f5f28-0c4a-475a-9043-9ad5c95d6990" />
</p>

---

## 🖇️ Descripción de pines del conector DB9 y DB25
Los puertos serie RS-232 suelen emplear conectores **DB9** y **DB25**.  

| Señal | Función                          | DB9 | DB25 |
|-------|----------------------------------|-----|------|
| DCD   | Detecta portadora                | 1   | 8    |
| RXD   | Datos recibidos                  | 2   | 3    |
| TXD   | Datos transmitidos               | 3   | 2    |
| DTR   | Terminal listo                   | 4   | 20   |
| GND   | Tierra                           | 5   | 7    |
| DSR   | Equipo listo                     | 6   | 6    |
| RTS   | Solicitud para enviar            | 7   | 4    |
| CTS   | Listo para enviar                | 8   | 5    |
| RI    | Indicador de llamada entrante    | 9   | 22   |

<p align="center">
  <img width="323" height="519" alt="image" src="https://github.com/user-attachments/assets/307f08e1-00d4-4367-88ed-d14e9a87aa59" />
</p>

---

## 📡 Formato de trama RS-232
El estándar RS-232 define la transmisión de datos en tramas **asincrónicas**.  
Una configuración común es **8N1**:  


