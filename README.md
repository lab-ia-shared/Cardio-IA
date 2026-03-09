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
Utilizamos dados clínicos para identificar fatores de risco que antecedem eventos cardiovasculares, especialmente relacionados à hipertensão arterial.

* **Dataset:** Cardiovascular Disease Dataset  
* **Fonte:** https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset  
* **Link para os Dados:** [COLE_AQUI_O_LINK_DO_SEU_DRIVE]

* **Origem:** Dataset público contendo aproximadamente **70.000 registros clínicos de pacientes**.

### Variáveis Relevantes
* **Pressão Sistólica/Diastólica (ap_hi / ap_lo):** essencial para classificação da hipertensão.
* **Colesterol:** marcador biológico associado ao risco cardiovascular.
* **Glicose:** indicador importante para doenças metabólicas relacionadas ao sistema cardiovascular.
* **Idade e Sexo:** variáveis demográficas relevantes na avaliação de risco.
* **Peso e Altura:** utilizados para cálculo de IMC.
* **Tabagismo, Consumo de Álcool e Atividade Física:** fatores comportamentais que influenciam diretamente no risco cardiovascular.

* **Justificativa para IA:** Estes dados permitem o treinamento de modelos de classificação binária para prever a presença de doenças cardiovasculares com base em biometria e exames laboratoriais.

---

## 📑 2. Dados Textuais (NLP)
Simulação de prontuários médicos para estruturação de dados não estruturados.

* **Arquivos:** Disponíveis na pasta `/docs` deste repositório.
* **Fontes:** Dados simulados baseados em diretrizes médicas sobre hipertensão arterial.

### Fontes Científicas Utilizadas
- http://www.scielo.br/j/abc/a/BXT7Vk4B9VKQnJFsJhgJ4Hn/?lang=pt  
- https://bvsms.saude.gov.br/bvs/publicacoes/linha_cuidado_adulto_hipertens%C3%A3o_arterial.pdf  
- https://www.scielo.br/j/abc/a/f6qfTvNPNTWSXnTYVQszRLs/?format=pdf&lang=pt  
- https://docs.bvsalud.org/biblioref/2018/03/881441/rbh-v21n1_3-12.pdf  
- https://www.scielo.br/j/csc/a/S3rGV7YyJgStLFgcBQxjkfK/?format=pdf&lang=pt  
- https://docs.bvsalud.org/biblioref/2018/03/881411/rbh-v21n2_75-82.pdf  

### Análises de NLP
* **Extração de Entidades Nomeadas (NER):** identificação automática de sintomas, pressão arterial e fatores de risco.
* **Classificação Clínica:** identificação de pacientes com suspeita de hipertensão.
* **Extração de Sintomas:** reconhecimento de termos como cefaleia, tontura e palpitações.
* **Estruturação de Prontuários:** conversão de registros clínicos em dados estruturados.

* **Justificativa para IA:** O processamento de linguagem natural permite transformar relatos clínicos em dados estruturados, auxiliando na triagem hospitalar.

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
