# ⚡ Calculadora de Consumo Elétrico

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Projeto-black?logo=github)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

## 📌 Sobre o projeto

A **Calculadora de Consumo Elétrico** é um programa desenvolvido em Python que permite estimar o consumo mensal de energia elétrica de um aparelho.

O sistema utiliza informações simples, como a potência do aparelho e o tempo médio de uso diário, para calcular o consumo aproximado em **kWh por mês**. Também é possível estimar o custo mensal da energia.

## 🎯 Objetivo

A proposta do projeto é ajudar o usuário a entender quanto um aparelho pode consumir de energia elétrica durante um mês e qual seria o custo aproximado desse consumo.

## 🛠️ Tecnologias utilizadas

* 🐍 **Python**
* 💻 **VS Code**
* 🐙 **GitHub**
* ⚡ **Cálculo de consumo de energia**

## 🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a seguinte fórmula:

```text
Consumo mensal = (Potência × Horas de uso por dia × 30) / 1000
```

Onde:

* **Potência** = potência do aparelho em watts (W)
* **Horas por dia** = tempo médio de funcionamento diário
* **30** = quantidade aproximada de dias em um mês
* **1000** = conversão de Wh para kWh

### 💰 Cálculo do custo

Para estimar o custo mensal, é utilizado o valor de **R$ 0,75 por kWh**:

```text
Custo mensal = Consumo mensal × 0,75
```

> ℹ️ O valor utilizado é apenas uma estimativa e pode variar de acordo com a tarifa de energia elétrica.

## ▶️ Como executar o programa

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acesse a pasta do projeto

```bash
cd consumo-energia
```

### 3. Execute o programa

```bash
python app.py
```

### 4. Informe os dados solicitados

O programa solicitará:

* Nome do aparelho;
* Potência em watts (W);
* Tempo médio de uso diário em horas.

Após informar os dados, o sistema exibirá o consumo estimado e o custo mensal.

## 📊 Exemplo

```text
=== Calculadora de Consumo Elétrico ===

Digite o nome do aparelho: Geladeira
Digite a potência do aparelho em watts (W): 100
Digite o tempo médio de uso diário (em horas): 15

--- Resultado ---
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
Custo estimado: R$ 33.75/mês
```

## 📁 Estrutura do projeto

```text
consumo-energia/
│
├── app.py
└── README.md
```

## 👩‍💻 Desenvolvido por

Projeto desenvolvido como parte de um programa de iniciação em tecnologia.

💡 **Aprendizado:** desenvolvimento de um programa em Python, entrada e processamento de dados, cálculos matemáticos, documentação de projetos e publicação no GitHub.
