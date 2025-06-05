📊 Análise da Representatividade Feminina na Câmara dos Deputados

📌 **Descrição**
Este projeto visa analisar a representatividade feminina na Câmara dos Deputados durante as legislaturas 56ª (2019–2022) e 57ª (2023–2026). Utilizando dashboards interativos desenvolvidos no Power BI e análises complementares em Python, buscamos compreender o cenário atual da participação política das mulheres no Brasil, observando tanto os aspectos demográficos quanto legislativos, incluindo distribuição partidária e desigualdade entre estados.

---

🌟 **Indicadores e Análises Desenvolvidas**

1. **Participação e Perfil Demográfico**
   - Distribuição por gênero, idade, geração e escolaridade

2. **Deputadas Eleitas por Partido**
   - Partidos com maior e menor representatividade
   - Evolução da representatividade feminina e masculina (2019–2023)
   - Quantidade de deputadas por partido em cada legislatura

3. **Distribuição Geográfica**
   - Mapa das deputadas por estado (UF)
   - Regiões e Estados com maior ou menor representação

4. **Lideranças femininas**
   - Proporção de lideranças por gênero
   - Evolução de lideranças por gênero e legislatura
   - Média de permanência na liderança por gênero
   - Partidos e estados com lideranças femininas

5. **Proposições com autoria feminina**
   - Distribuição por tipo e tema de proposição
   - Total geral de proposições x Total de proposições com autoria feminina
   - Evolução anual de proposições femininas x Total geral

---

🛠️ **Tecnologias Utilizadas**
   - Python 
      - Bibliotecas: pandas, requests
      - Análises exploratórias e tratamento de dados: cálculo de dias de liderança, contagem de proposições, métricas demográficas...
   - Power BI
      - Dashboards interativos (colunas empilhadas, treemap, mapas, box plot, cartões KPI)
      - Filtros dinâmicos e segmentadores para Legislatura, Gênero, Estado, Partido, Tema
   - Git/GitHub 
      - Versionamento e organização do projeto

---

📁 **Estrutura do Projeto**

```
📆 representatividade-feminina-camara
👤📁 dashboards
   ├── representatividade.pbix
   └── capturas_tela/
   └── pdf/
👤📁 data
   ├── arquivos.csv
   └── dados_proposicoes/
   └── modelo_de_dados/
👤📁 scripts
   └── representatividade.ipynb
📄 README.md
📄 LICENSE
📄 .gitignore
```

---

📱 **Fontes de Dados**
- [Câmara dos Deputados – Dados Abertos](https://dadosabertos.camara.leg.br/)
- [API da Câmara dos Deputados](https://dadosabertos.camara.leg.br/swagger/api.html)

---

📜 **Licença**
Este projeto está licenciado sob a **MIT License** – veja o arquivo LICENSE para mais detalhes.

---

💬 **Sugestões ou dúvidas?**
Abra uma issue neste repositório ou entre em contato diretamente!
Contribuições, correções e novas ideias são sempre bem-vindas!

   Este trabalho faz parte do Trabalho de Conclusão do Curso de Análise e Desenvolvimento de Sistemas.
   Agradeço seu interesse e colaboração! 💜