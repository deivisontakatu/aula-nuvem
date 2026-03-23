# 📘 Aula 04 — Conceitos de Virtualização

## 🎯 Objetivos da Aula
- Compreender o conceito de virtualização  
- Entender seu papel na computação em nuvem  
- Identificar os principais tipos de virtualização  
- Diferenciar máquinas virtuais e containers  
- Conhecer técnicas e abordagens de virtualização  

---

## 🧠 1. Introdução

A **virtualização** é uma tecnologia que permite criar versões virtuais de recursos computacionais, como:

- Servidores  
- Sistemas operacionais  
- Armazenamento  
- Redes  

➡️ Ela é a base da computação em nuvem moderna.

---

## 📌 2. Definição de Virtualização

Virtualização é o processo de **abstrair recursos físicos**, permitindo que múltiplos ambientes virtuais sejam executados em um único hardware.

➡️ Em outras palavras:
- Um único servidor físico pode rodar vários sistemas independentes  

---

## 🏗️ 3. Como Funciona a Virtualização

A virtualização utiliza um componente chamado:

### 🔧 Hipervisor (Hypervisor)

Responsável por:
- Criar e gerenciar máquinas virtuais  
- Distribuir recursos (CPU, memória, disco)  
- Garantir isolamento entre ambientes  

---

### 📊 Tipos de Hipervisor

#### 🔹 Tipo 1 (Bare Metal)
- Executa diretamente no hardware  
- Maior desempenho  

📌 Exemplos:
- VMware ESXi  
- Microsoft Hyper-V  
- Xen  

---

#### 🔹 Tipo 2 (Hosted)
- Executa sobre um sistema operacional  

📌 Exemplos:
- VirtualBox  
- VMware Workstation  

---

## 🖥️ 4. Máquinas Virtuais (VMs)

### 📌 Definição
Uma **máquina virtual (VM)** é um ambiente isolado que simula um computador completo.

### 🔧 Características
- Possui sistema operacional próprio  
- Usa recursos virtualizados  
- Total isolamento  

---

### ✅ Vantagens
- Isolamento entre aplicações  
- Segurança  
- Flexibilidade  

### ⚠️ Desvantagens
- Maior consumo de recursos  
- Inicialização mais lenta  

---

## 📦 5. Containers

### 📌 Definição
Containers são ambientes leves que compartilham o sistema operacional do host.

➡️ Diferente das VMs:
- Não possuem SO completo  
- São mais rápidos e leves  

---

### 🔧 Características
- Inicialização rápida  
- Baixo consumo de recursos  
- Alta portabilidade  

---

### ✅ Vantagens
- Eficiência  
- Escalabilidade  
- Ideal para microserviços  

### ⚠️ Desvantagens
- Menor isolamento que VMs  
- Dependência do sistema operacional  

---

## ⚖️ 6. Comparação: VM vs Container

| Característica     | Máquina Virtual       | Container            |
|--------------------|----------------------|----------------------|
| Sistema Operacional| Completo             | Compartilhado        |
| Inicialização      | Lenta                | Rápida               |
| Consumo de recursos| Alto                 | Baixo                |
| Isolamento         | Alto                 | Médio                |
| Portabilidade      | Média                | Alta                 |

---

## 🧩 7. Tipos de Virtualização

### 🖥️ Virtualização de Servidores
- Divide um servidor físico em várias VMs  

---

### 💾 Virtualização de Armazenamento
- Agrupa múltiplos dispositivos em um único pool  

---

### 🌐 Virtualização de Rede
- Cria redes virtuais independentes  

---

### 🖥️ Virtualização de Desktop (VDI)
- Desktop acessado remotamente  

---

## ⚙️ 8. Técnicas de Virtualização

A virtualização pode ser implementada por diferentes técnicas:

### 🔹 Emulação
- Simula completamente um hardware diferente  
- Permite executar sistemas incompatíveis  
- Baixo desempenho  

---

### 🔹 Virtualização Completa (Full Virtualization)
- Não requer modificação do sistema operacional  
- Hardware totalmente simulado  
- Alta compatibilidade  

---

### 🔹 Paravirtualização
- Sistema operacional adaptado para o hipervisor  
- Comunicação direta com o hipervisor  
- Melhor desempenho  

---

### 🔹 Virtualização Assistida por Hardware
- Utiliza recursos do processador (Intel VT-x, AMD-V)  
- Aumenta desempenho e eficiência  

---

## ⚖️ 9. Virtualização Total vs Paravirtualização

### 🖥️ Virtualização Total
- Hardware totalmente simulado  
- Sistema operacional não precisa ser modificado  
- Maior compatibilidade  

---

### ⚙️ Paravirtualização
- Sistema operacional modificado  
- Comunicação direta com o hipervisor  
- Melhor desempenho  

---

### 📊 Comparação

| Característica        | Virtualização Total | Paravirtualização |
|----------------------|--------------------|------------------|
| Modificação do SO    | Não                | Sim              |
| Desempenho           | Médio              | Alto             |
| Compatibilidade      | Alta               | Média            |
| Complexidade         | Baixa              | Maior            |

---

## 🌍 10. Exemplos Reais

### ☁️ Amazon AWS
- Usa virtualização para criar instâncias EC2  

### 🏢 Google Cloud
- Utiliza containers (Kubernetes) em larga escala  

### 🏦 Bancos
- Virtualização para isolamento de sistemas críticos  

---

## ⚙️ 11. Benefícios da Virtualização

- Melhor aproveitamento de hardware  
- Redução de custos  
- Escalabilidade  
- Facilidade de gerenciamento  
- Alta disponibilidade  

---

## ⚙️ 12. Recursos da Virtualização

A virtualização oferece diversos recursos importantes:

### 🔹 Provisionamento Dinâmico
- Criação rápida de máquinas virtuais  

### 🔹 Snapshots
- Captura do estado de uma VM  

### 🔹 Live Migration
- Migração de VMs sem interrupção  

### 🔹 Balanceamento de Carga
- Distribuição eficiente de recursos  

### 🔹 Isolamento
- Separação segura entre ambientes  

### 🔹 Escalabilidade
- Ajuste de recursos conforme demanda  

---

## ⚠️ 13. Desafios

- Complexidade de gestão  
- Segurança  
- Overhead de virtualização  
- Dependência de ferramentas  

---

## 🔄 14. Virtualização e Computação em Nuvem

➡️ Relação direta:

- Virtualização = base tecnológica  
- Nuvem = modelo de entrega  

Sem virtualização:
- Não há elasticidade  
- Não há multi-tenant  

---

## 🔄 15. Síntese da Aula

- Virtualização permite múltiplos ambientes em um único hardware  
- Hipervisor é o componente central  
- VMs e containers são abordagens principais  
- Existem diferentes técnicas de virtualização  
- É essencial para a computação em nuvem  

---

## 📚 16. Referências

### Bibliografia Básica
- CHEE, J. S. B.; JUNIOR, Franklin C.  
  *Computação em Nuvem – Cloud Computing Tecnologias e Estratégias*. São Paulo: M. Books, 2013.

- VERAS, Manoel  
  *Cloud Computing: Nova Arquitetura de TI*. Rio de Janeiro: Brasport, 2012.

- VERAS, Manoel  
  *Virtualização: Tecnologia Central do Datacenter*. Rio de Janeiro: Brasport, 2016.

### Bibliografia Complementar
- ANTUNES, L. J.  
  *Amazon AWS: Descomplicando a computação na nuvem*. São Paulo: Casa do Código, 2016.

- ARUNDEL, J.; DOMINGUS, J.  
  *DevOps Nativo de Nuvem com Kubernetes*. São Paulo: Novatec, 2019.

- MOLINARI, L.  
  *Cloud Computing: A inteligência na nuvem e seu novo valor em TI*. São Paulo: Érica, 2017.

- TAURION, Cesar  
  *Cloud Computing*. Rio de Janeiro: Brasport, 2009.