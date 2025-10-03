# DataWings

> Plataforma de análise e predição de atrasos e performance operacional no setor aéreo — projeto acadêmico/protótipo.

---

## 🔎 Visão geral

O DataWings transforma dados abertos da aviação (ANAC e outras fontes públicas) em indicadores operacionais, dashboards e modelos preditivos para monitoramento de atrasos, cancelamentos e performance por aeroporto/companhia.

Este repositório contém o código-fonte, documentação e scripts para: extração e tratamento de dados (ETL), armazenamento relacional, APIs para consumo de dashboards e um site institucional simples.

---

## 🧭 Objetivos do projeto

- Centralizar e consolidar informações de atrasos, cancelamentos e condições operacionais.
- Oferecer dashboards e relatórios gerenciais.
- Suportar modelos preditivos para antecipar atrasos e cancelamentos.
- Facilitar comparações entre companhias e aeroportos.

---

## 🧰 Tecnologias propostas

- Linguagens: Java (ETL, ML), JavaScript / HTML / CSS (frontend / backend opcional)
- Frameworks: Chart.js (ou Next.js) para dashboards
- Banco de dados: MySQL Server 
- Processamento: Apache POI (para leitura de .xls/.xlsx)
- Cloud: AWS (S3 para storage, RDS para BD, IAM para controle de acesso)
- Containerização: Docker

---

## ♻️ Fluxo principal (ETL)

1. **Extração**: baixar CSV/XLSX da ANAC e outras fontes.
2. **Transformação**: Analisat e validar od dados adquiridos.
3. **Carga**: gravar em MySQL Server e/ou arquivos parquet em S3.
4. **Consumo**: Dados que alimentam dashboards e Geração de Relatórios.

---

## 🔐 Controle de acesso

- Planejado: AWS IAM para gerenciamento de perfis (admin, analista, visualizador).

---

## ⚠️ Limitações e exclusões (conforme especificado no projeto)

- O sistema **não** controla tráfego aéreo nem integra sistemas de vigilância.
- Não há módulo de venda de passagens ou atendimento ao cliente.
- A infraestrutura física dos aeroportos é responsabilidade do cliente.

---

## 📚 Fontes e referência

O projeto foi baseado na documentação do escopo e justificativa, incluindo dados e referências citadas na documentação inicial do projeto (ANAC, reportagens e estudos setoriais).

---

## 📝 Licença

Escolha a licença apropriada (ex.: MIT, Apache-2.0). Arquivo `LICENSE` deve ser adicionado no root do repositório.

---

## 📬 Contato

Projeto mantido por: Squad DataWings — contato: datawings@example.com.