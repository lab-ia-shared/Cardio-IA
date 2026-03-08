# 💓 CardioIA - A Nova Era da Cardiologia Inteligente

## 📋 Descrição do Projeto

O **CardioIA** é um projeto acadêmico inovador focado na convergência entre tecnologia de ponta e saúde cardiovascular. O objetivo é desenvolver uma plataforma digital que simule um ecossistema cardiológico moderno, integrando dados clínicos, modelos de Machine Learning, Visão Computacional e IoT para triagem e diagnósticos precoces.

Nesta **Fase 1 – Batimentos de Dados**, assumimos o papel de cientistas de dados hospitalares para levantar, organizar e estruturar a base de dados fundamental (numérica, textual e visual) que alimentará os futuros módulos inteligentes do sistema, sempre com foco na Governança de Dados e ética em IA.

## 👨‍⚕️ Integrantes do Grupo
- <a href="https://www.linkedin.com/in/nicolas--araujo/">Nicolas Antonio Silva Araujo</a> 
- <a href="https://www.linkedin.com/in/vitoria-bagatin-31ba88266/">Vitória Pereira Bagatin</a> 

## 📂 Estrutura de Arquivos

A organização do repositório segue a estrutura necessária para a gestão de ativos de dados:

```text
Cardio-IA/
│
├── docs/                       # Subpasta de ativos (conforme enunciado)
│   ├── diretriz_hipertensao.txt  # Artigo textual 1 (NLP)
│   └── protocolo_arritmia.txt    # Artigo textual 2 (NLP)
│
└── README.md                     # Documentação principal e justificativas
````

---

## 🔢 1. Dados Numéricos (IoT e Predição)
Utilizamos dados clínicos para identificar fatores de risco que antecedem eventos críticos.

* **Dataset:** [Cardiovascular Disease dataset]
* **Link para os Dados:** [COLE_AQUI_O_LINK_DO_SEU_DRIVE]
* **Origem:** Dados reais de exames médicos (70.000 registros).
* **Variáveis Relevantes:** * **Pressão Sistólica/Diastólica:** Essencial para classificar o grau de hipertensão.
    * **Colesterol e Glicose:** Marcadores biológicos que potencializam o risco cardiovascular.
* **Justificativa para IA:** Estes dados permitem o treinamento de modelos de classificação binária para prever a presença de doenças cardiovasculares com base em biometria e exames laboratoriais.

---

## 📑 2. Dados Textuais (NLP)
Simulação de prontuários médicos e relatos de pacientes para estruturação de dados não estruturados.

* **Arquivos:** Disponíveis na pasta `/docss` deste repositório.
* **Fontes:** Dados fictícios criados pelo grupo para simular o fluxo de triagem hospitalar.
* **Análises de NLP:**
    * **Extração de Entidades Nomeadas (NER):** Para identificar automaticamente sintomas (ex: palpitação, tontura) e histórico de comorbidades nos relatos.
    * **Análise de Sentimento e Urgência:** Para classificar a prioridade do atendimento com base na gravidade dos sintomas descritos.
* **Justificativa para IA:** O processamento de linguagem natural permite transformar relatos informais em dados estruturados, agilizando o preenchimento de prontuários e a triagem prioritária na rede de saúde.

---

## 👁️ 3. Dados Visuais (Visão Computacional)
Análise de exames de imagem para detecção de anomalias estruturais e elétricas.

* **Dataset:** [ECG Images dataset of Cardiac and Abnormal Beats]
* **Link para as Imagens (Mínimo 100):** [COLE_AQUI_O_LINK_DO_DRIVE]
* **Tipo de Exame:** Eletrocardiograma (ECG), Raio-X.
* **Aplicações de VC:**
    * **Detecção de Padrões:** Identificação visual de arritmias (como Fibrilação Atrial) através do formato das ondas.
    * **Reconhecimento de Anomalias:** Filtros para distinguir batimentos normais de batimentos ectópicos.
* **Justificativa para IA:** Algoritmos de Visão Computacional podem analisar milhares de exames por segundo, auxiliando o médico na triagem prioritária de casos graves.

---

## 🛡️ Governança e Ética
Este projeto segue os princípios de governança de dados, garantindo que as fontes sejam citadas e os dados utilizados (reais ou simulados) sirvam estritamente para fins acadêmicos, visando a redução de vieses em diagnósticos automatizados.
---
