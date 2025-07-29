# 🔧 Esquema Conceitual – Oficina Mecânica

## 📌 Descrição

Projeto de modelagem conceitual para um sistema de gerenciamento de **ordens de serviço** em uma **oficina mecânica**. O modelo representa clientes, veículos, mecânicos, equipes, serviços, peças e ordens de serviço.

## 🧱 Entidades Principais

- **Cliente**: dados pessoais
- **Veículo**: modelo, placa, cliente
- **Mecânico**: código, nome, especialidade
- **Equipe**: composta por mecânicos
- **OS (Ordem de Serviço)**: número, datas, valor, status
- **Serviço**: descrição, valor (por tabela de mão de obra)
- **Peça**: descrição, valor

## 🔗 Relacionamentos

- Cliente possui veículos
- Veículo tem ordens de serviço
- OS é executada por uma equipe
- OS envolve serviços e peças
- Serviços têm valor baseado em tabela

## 📁 Arquivos

- `README.md`
- `modelo_conceitual.drawio` *(ou imagem .png/.pdf)*

## ✅ Status

Concluído e pronto para avaliação.

