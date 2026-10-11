# ⚡ InstaLed Firmware (ESP32)

[![PlatformIO](https://img.shields.io/badge/PlatformIO-Integrated-orange?style=for-the-badge&logo=platformio)](https://platformio.org/)
[![C++](https://img.shields.io/badge/C%2B%2B-Embedded-00599C?style=for-the-badge&logo=c%2B%2B)](https://isocpp.org/)
[![ESP32](https://img.shields.io/badge/Hardware-ESP32-E7352C?style=for-the-badge&logo=espressif)](https://www.espressif.com/)

Firmware embarcado em **C++** configurado com **PlatformIO** para controle de fitas de LED endereçáveis no microcontrolador ESP32.

---

## 📌 Sobre o Projeto

O **InstaLed Firmware** roda no microcontrolador ESP32, conectando-se à rede Wi-Fi local para receber comandos da API backend (`instaled-api`). Ele aciona fitas de LED digitais endereçáveis (WS2812B / NeoPixel) com transições suaves de cores, dimerização por PWM e animações de alta taxa de atualização.

## 🚀 Funcionalidades

- 🌈 **Controle Endereçável de LEDs:** Acionamento de pixels individuais e grupos de cores.
- 📶 **Conectividade Wi-Fi:** Recepção de comandos remotos via HTTP/WebSocket/MQTT.
- ⚡ **Efeitos Fluídos:** Rotinas otimizadas em C++ para transições sem travamentos.
- ⚙️ **Configuração Modular:** Suporte completo via PlatformIO para compilação e upload serial.

## 🛠️ Tecnologias e Hardware

- **ESP32 DevKit v1**
- **C++ (PlatformIO / Framework Arduino)**
- Bibliotecas para fitas de LED digitais (FastLED / Adafruit NeoPixel)

## ⚙️ Como Compilar e Fazer Upload

### Pré-requisitos
- Visual Studio Code com extensão **PlatformIO IDE**.

```bash
# 1. Clone o repositório
git clone https://github.com/IuryAlmeidaDev/instaled-firmware.git
cd instaled-firmware

# 2. Compile o projeto
pio run

# 3. Grave no ESP32 conectado via USB
pio run --target upload
```

---

## 👤 Autor

Desenvolvido por **[Iury Almeida](https://github.com/IuryAlmeidaDev)**.
