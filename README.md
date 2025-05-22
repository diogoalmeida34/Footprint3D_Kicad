# 🧩 Modelos 3D de Footprints para KiCad

Este repositório contém modelos 3D de **footprints** para componentes eletrônicos, desenvolvidos para serem utilizados no software de design de placas de circuito impresso (PCB) **KiCad**. Os modelos 3D aqui disponíveis são projetados para melhorar a precisão e eficiência no processo de design de PCBs, permitindo a visualização detalhada dos componentes, facilitando a detecção de interferências e melhorando a confiabilidade do projeto final.

---

## 🎯 Objetivo

O objetivo deste repositório é fornecer modelos 3D de footprints, otimizados para uso no KiCad, com o intuito de:

- 🔍 **Visualização precisa:** Permitir que o projetista visualize o componente em 3D diretamente no ambiente do KiCad.
- 🚫 **Detecção de interferências:** Facilitar a detecção de possíveis conflitos entre os componentes no design da placa.
- ⚙️ **Aprimorar a eficiência e precisão do projeto:** Com componentes 3D detalhados, é possível evitar erros de posicionamento e garantir uma montagem física mais precisa.

---

## 📁 Estrutura do Repositório

Este repositório contém os seguintes diretórios e arquivos:

/FootPrintsModelos3D
/component_1 -> Diretório contendo os modelos de footprints e os arquivos 3D para os componentes.
- component_1.kicad_mod -> Arquivo de footprint do KiCad.
- component_1_3d.step -> Arquivo STEP com o modelo 3D do componente.
/component_2
- component_2.kicad_mod
- component_2_3d.step
...
/README.md -> Este arquivo com as informações sobre o repositório.
LICENSE -> Licença do projeto.

---

## ⚙️ Como Usar

Para usar os modelos 3D neste repositório no KiCad, siga as etapas abaixo:

1. **Baixar o Repositório:**
   Você pode clonar ou baixar o repositório com o seguinte comando:
   ```bash
   git clone https://github.com/seu-usuario/repo-footprints-3d.git
   
2. **Adicionar o Footprint no KiCad:**
- Abra o KiCad e crie ou edite um projeto.
- Na aba de Footprint Editor, selecione o arquivo .kicad_mod do componente desejado.
- Para associar o modelo 3D, no Footprint Properties, selecione a aba 3D Settings e aponte para o arquivo .step correspondente ao componente.

3. **Visualização em 3D:**
Após associar os modelos 3D aos footprints, você pode visualizar o design da placa em 3D na aba de visualização do KiCad, o que permitirá a verificação do posicionamento e a detecção de potenciais problemas de interferência.

---

## 📜 Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
