<h1 align="center">
    <img alt="NetPractice" width="200px" src="https://raw.githubusercontent.com/NataliaMatias2024/42-project-badges/main/badges/netpracticem.png">
</h1>

# 👩‍💻 NetPractice - @42SP
**Score:** 100/100 ✅

_This project has been created as part of the 42 curriculum by namatias._

Este repositório contém as configurações resolvidas para o projeto NetPractice, desenvolvido como parte do currículo da [42 São Paulo](https://www.42sp.org.br/).

## 🚀 Description

O **NetPractice** é um projeto prático focado nos fundamentos de redes de computadores. 
O objetivo é entender como funciona o endereçamento IP, mascaramento de sub-redes e o roteamento de pacotes através de uma interface web de treinamento, solucionando problemas de conectividade em redes de pequena escala.

## 🛠️ Instructions
### 1. Executando a Interface de Treino
1. Baixe os arquivos do projeto na página oficial da Intranet da 42.
2. Extraia os arquivos em um diretório de sua preferência.
3. Abra o arquivo `index.html` diretamente em seu navegador para carregar o ambiente gráfico.
4. Insira o seu login da intranet (ex: `namatias`) na aba **Training** e clique em **Start!** para iniciar.
5. Utilize o botão **[Check again]** para validar as alterações realizadas.

### 2. Exportando as Configurações
* Para cada um dos **10 níveis** resolvidos com sucesso, utilize o botão **[Get my config]** disponível no topo da interface.
* O botão gerará o download do arquivo de configuração correspondente àquele nível.

### 3. Requisitos de Submissão
* Os **10 arquivos de configuração exportados** (um para cada nível) devem ser colocados obrigatoriamente na **raiz (root)** do repositório Git para a avaliação.
* Certifique-se de que os arquivos foram exportados com o seu login inserido corretamente na plataforma.


## 🧠 Conceitos-Chave

### 🌐 TCP/IP Addressing & Subnet Masks
* **IP Address:** Identificador único de cada dispositivo dentro de uma rede. No IPv4, é dividido entre a porção de rede e a porção de host.
* **Subnet Mask:** Define os limites e o tamanho de uma rede. Determina quais IPs pertencem ao mesmo escopo local e conseguem se comunicar diretamente, mapeando a máscara tanto em formato decimal (ex: `255.255.255.0`) quanto em notação CIDR (ex: `/24`).
* **Reserved Addresses:** Toda sub-rede possui dois endereços reservados que não podem ser atribuídos a nenhum host: o *Network Address* (primeiro IP da faixa, representando a rede) e o *Broadcast Address* (último IP da faixa, usado para comunicação com todos os hosts daquela rede).

### 📡 Routing & Default Gateway
* **Default Gateway:** O endereço da interface do roteador que serve como porta de saída para os hosts locais enviarem pacotes para fora de sua sub-rede.
* **Routing Tables:** Tabelas de decisão utilizadas pelos roteadores. O roteador analisa o IP de destino do pacote e encontra a rota mais específica para encaminhá-lo. Caso não haja correspondência exata, utiliza a rota padrão (`0.0.0.0/0`).

### 🗺️ Network Devices
* **Routers:** Equipamentos responsáveis por interconectar redes diferentes e encaminhar pacotes entre elas através de tabelas de roteamento.
* **Switches:** Dispositivos que conectam hosts dentro de uma mesma rede local, distribuindo o tráfego internamente.

## 📚 Resources
- [Playlist YouTube - Subnetting Mastery](https://youtube.com/playlist?list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE&si=fAibshMaaLJgvs5O)
- [Geeks for Geeks - Role of Subnet Mask](https://www.geeksforgeeks.org/computer-networks/role-of-subnet-mask/)
- [Wikipedia - IPv4](https://pt.wikipedia.org/wiki/IPv4)

## 🤖 Artificial Intelligence (AI) Usage Statement
Em conformidade com as diretrizes do projeto, ferramentas de Inteligência Artificial foram utilizadas durante o desenvolvimento com foco exclusivo em otimização de fluxo de trabalho e validação conceitual:
* **Tasks Executed:** A IA foi aplicada como suporte de produtividade para estruturar e revisar a formatação Markdown e a gramática deste arquivo de documentação.
* **Validation Rigor:** Nenhuma configuração de rede ou solução de nível foi gerada ou copiada de ferramentas automatizadas. Todas as lógicas de sub-redes e rotas foram analisadas e calculadas de forma estritamente autoral.


## 💻 Hard Skills
`Networking` • `TCP/IP` • `Subnet Masking` • `IP Routing` • `Systems Infrastructure`
