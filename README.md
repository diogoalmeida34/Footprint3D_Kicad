# 🧩 Modelos 3D de Footprints para KiCad

Este repositório oferece modelos 3D de **footprints** para componentes eletrônicos, projetados para uso no **KiCad**. Com esses modelos, você pode visualizar componentes em 3D, detectar interferências e aprimorar a precisão de seus projetos de PCB.

---

## 🎯 Objetivo

Fornecer modelos 3D otimizados para o KiCad, com os seguintes benefícios:
- 🔍 **Visualização precisa:** Veja os componentes em 3D diretamente no KiCad.
- 🚫 **Detecção de interferências:** Identifique conflitos no layout da placa.
- ⚙️ **Maior eficiência:** Evite erros de posicionamento e garanta precisão na montagem.

---

## 📋 Pré-requisitos
- KiCad versão 6.0 ou superior.
- Arquivos `.step` compatíveis com o visualizador 3D do KiCad.

---

## 📁 Estrutura do Repositório

```
/footprint3D_Kicad
  /component_1
    - component_1.kicad_mod -> Arquivo de footprint do KiCad.
    - component_1_3d.step -> Modelo 3D no formato STEP.
  /component_2
    - component_2.kicad_mod
    - component_2_3d.step
  ...
  /README.md -> Este arquivo.
  /LICENSE -> Licença do projeto.
```

---

## ⚙️ Como Usar

### 1. Baixar o Repositório
Clone o repositório com o comando:
```bash
git clone https://github.com/diogoalmeida34/footprint3D_Kicad.git
```

### 2. Adicionar o Footprint no KiCad
- Abra o KiCad e acesse o **Footprint Editor** no menu principal.
- Clique em **File > Import Footprint** e selecione o arquivo `.kicad_mod` do componente desejado.
- Para associar o modelo 3D:
  - No Footprint Editor, clique com o botão direito no footprint e selecione **Properties**.
  - Na aba **3D Settings**, clique em **Add 3D Model** e selecione o arquivo `.step` correspondente.

### 3. Visualização em 3D
Após associar os modelos, use a aba **3D Viewer** no KiCad para verificar o posicionamento dos componentes e detectar possíveis interferências.

---

## 📦 Componentes Disponíveis
- Microcontroladores (ESP-32 CAM, ARDUINO MEGA 2560)
- Sensores (DHT-11, DS18B20, HC-SR04)
- Conectores Molex

---

## 🤝 Como Contribuir
- Envie sugestões ou reporte problemas criando uma **issue**.
- Para adicionar novos modelos:
  1. Crie um fork do repositório.
  2. Adicione seus arquivos `.kicad_mod` e `.step` no diretório correspondente.
  3. Envie um **pull request** com uma descrição clara das alterações.

---

## 📜 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
