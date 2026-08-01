# 🎯 Mega Prompt: Consulta & Mapeamento de Carreira em TI

> Projeto desenvolvido como parte do desafio de **Engenharia de Prompt** na **Digital Innovation One (DIO)**.

---

## 📌 Sobre o Projeto

O **Mega Prompt de Consulta de Carreira em TI** é uma solução de engenharia de prompt projetada para atuar como um **consultor e mentor virtual de carreira**. 

Por meio de uma **entrevista estruturada em 35 perguntas profundas**, o prompt coleta dados sobre histórico acadêmico, conhecimentos técnicos, *soft skills*, preferências de atuação e visão de futuro do profissional. Com base nas respostas fornecidas, o modelo processa o perfil e gera um diagnóstico personalizado apresentando **4 carreiras ideais** em Tecnologia da Informação.

---

## 🧩 Estrutura da Entrevista (35 Perguntas)

A entrevista é dividida estrategicamente em 6 pilares de avaliação:

1. **🎓 Formação e Experiência:** Mapeamento de histórico acadêmico, certificações, bootcamps e prática em projetos reais.
2. **💻 Competências Técnicas:** Diagnóstico de linguagens, frameworks, bancos de dados, DevOps e segurança.
3. **🤝 Soft Skills:** Avaliação de comunicação, gestão de tempo, trabalho sob pressão e receptividade a feedbacks.
4. **🎯 Áreas de Interesse:** Identificação de afinidade (Front/Back/Full Stack, IA, Dados, Cloud, Cyber, Mobile, IoT, Games).
5. **📚 Aprendizado Contínuo:** Hábitos de estudo, proficiência em idiomas e planos de especialização/certificação.
6. **🚀 Visão de Futuro:** Metas de curto, médio e longo prazo (5 a 10 anos), estilo de empresa ideal e aspirações globais.

---

## 📊 Matriz de Saída & Análise do Prompt

Após a execução do questionário, o prompt executa a seguinte lógica de processamento:

```text
[ Respostas das 35 Perguntas ]
              │
              ▼
  [ Mapeamento de Padrões & Afinidades ]
              │
              ▼
  [ Seleção das 4 Carreiras Mais Compatíveis ]
              │
              ▼
  [ Emissão do Relatório Detalhado de Carreira ]
