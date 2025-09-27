# Projeto-Sem-foro-com-LEDs-Raspberry-Pi-Pico
# 🚦 Projeto Semáforo com LEDs – Raspberry Pi Pico

Este projeto em **MicroPython** simula um semáforo simples utilizando três LEDs (vermelho, amarelo e verde), alternando os estados com tempos definidos.

🔗 [Abrir no Wokwi](https://wokwi.com/projects/440487947621265409)

---

## 📖 Descrição
O sistema controla três LEDs conectados ao **Raspberry Pi Pico** para representar as três fases de um semáforo tradicional:

1. **Vermelho** → Pare  
2. **Amarelo** → Atenção  
3. **Verde** → Siga  

Cada estado permanece ativo por **3 segundos**, alternando em ciclo infinito.

---

## 🧠 Funcionalidades
- Controle digital de três LEDs via GPIO:
  - 🔴 LED vermelho → **GPIO 8**
  - 🟡 LED amarelo → **GPIO 4**
  - 🟢 LED verde → **GPIO 0**
- Ciclo contínuo de semáforo com intervalos de 3 segundos.
- Uso de **MicroPython** para programação simples e direta.

---

## 🛠️ Tecnologias
- Linguagem: **MicroPython**  
- Microcontrolador: **Raspberry Pi Pico**  
- Simulação: **[Wokwi](https://wokwi.com/)**  

---

✍️ Desenvolvido como parte dos estudos de **microcontroladores e eletrônica digital**.
