# ☁️ Resumo — Computação em Nuvem (5 Tópicos)

---

## 📌 1. Contextualização e Tipos de Nuvem

A **computação em nuvem** é um modelo que permite o acesso sob demanda a recursos computacionais (servidores, armazenamento, redes e software) via internet, sem a necessidade de infraestrutura local.

### 🌐 Tipos de Nuvem

* **Nuvem Pública**
  Infraestrutura compartilhada, acessada via internet e gerenciada por provedores externos.

* **Nuvem Privada**
  Uso exclusivo de uma organização, com maior controle e segurança.

* **Nuvem Híbrida**
  Combinação entre nuvem pública e privada, permitindo flexibilidade e otimização de recursos.

---

## ⚙️ 2. Características da Computação em Nuvem

As principais características (modelo NIST) são:

* **Autoatendimento sob demanda**
  Recursos podem ser provisionados automaticamente pelo usuário.

* **Amplo acesso à rede**
  Serviços acessíveis via internet por diferentes dispositivos.

* **Pool de recursos**
  Recursos compartilhados entre múltiplos usuários (multi-tenant).

* **Elasticidade**
  Capacidade de escalar recursos rapidamente conforme a demanda.

* **Serviço mensurável**
  Uso monitorado e cobrado conforme consumo (pay-per-use).

---

## 🏗️ 3. Modelos de Serviço em Nuvem

Definem o nível de responsabilidade entre cliente e provedor:

* **IaaS (Infrastructure as a Service)**
  Fornece infraestrutura (servidores, rede, armazenamento).
  O cliente gerencia sistema operacional e aplicações.

* **PaaS (Platform as a Service)**
  Fornece ambiente completo para desenvolvimento.
  O cliente gerencia apenas aplicações e dados.

* **SaaS (Software as a Service)**
  Fornece software pronto via internet.
  O usuário apenas utiliza o sistema.

---

## ⚠️ 4. Desafios da Computação em Nuvem

* **Segurança**
  Risco de ataques, vazamento de dados e acessos indevidos.

* **Privacidade**
  Proteção de dados pessoais e adequação a leis (ex: LGPD).

* **Sistemas Legados**
  Dificuldade de migrar sistemas antigos para a nuvem.

* **Cultura Organizacional**
  Resistência à mudança e necessidade de capacitação.

---

## 🧠 5. Virtualização

A **virtualização** é a base da computação em nuvem, permitindo a execução de múltiplos ambientes virtuais em um único hardware.

### 📦 Tipos de Virtualização

* Servidores
* Armazenamento
* Redes
* Desktop

---

### ⚙️ Técnicas de Virtualização

* **Emulação** → simulação completa de hardware
* **Virtualização Total** → não exige modificação do sistema operacional
* **Paravirtualização** → sistema operacional adaptado ao hipervisor
* **Virtualização assistida por hardware** → uso de recursos do processador

---

### ⚖️ Virtualização Total vs Paravirtualização

| Característica    | Virtualização Total | Paravirtualização |
| ----------------- | ------------------- | ----------------- |
| Modificação do SO | Não                 | Sim               |
| Desempenho        | Médio               | Alto              |

---

### ⚙️ Recursos da Virtualização

* Provisionamento dinâmico
* Snapshots
* Live migration
* Balanceamento de carga
* Isolamento
* Escalabilidade

---
