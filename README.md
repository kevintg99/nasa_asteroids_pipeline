# Asteroid Data Pipeline - Projeto de Engenharia de Dados

![banner](https://img.shields.io/badge/Asteroid-Pipeline-blueviolet?style=for-the-badge&logo=python&logoColor=white)

Este projeto implementa um pipeline completo de engenharia de dados para coletar, transformar e visualizar dados de asteroides próximos à Terra usando a API pública da NASA.  
Tudo desenvolvido no **Google Colab** e usando apenas ferramentas gratuitas!

---

## Sobre o Projeto

O objetivo principal foi criar um **ETL (Extract, Transform, Load)** organizado em três etapas:

- **Ingestão**: Consumo da API da NASA e armazenamento dos dados brutos em CSV.
- **Tratamento**: Limpeza, transformação e normalização dos dados brutos para análise.
- **Visualização**: Criação de gráficos e insights exploratórios sobre os asteroides.

---

## Tecnologias Utilizadas

- Python 3
- Pandas para manipulação de dados
- Requests para conexão com APIs
- Matplotlib e Seaborn para visualizações
- Google Colab para desenvolvimento e execução
- Google Drive para armazenamento dos dados
- Git e GitHub para controle de versão

---

## Estrutura de Pastas

```
  nasa-asteroids-pipeline/
 ├──   data/
 │    ├── raw/             # Dados brutos (direto da API)
 │    └── processed/       # Dados tratados (prontos para análise)
 ├──  notebooks/
 │    ├── ingestao.ipynb    # Notebook de ingestão de dados
 │    ├── tratamento.ipynb   # Notebook de processamento de dados
 │    └── visualizacao.ipynb # Notebook de visualização
 ├──   visualizacoes/    # Gráficos gerados
 ├── .env                  # (Ignorado no Git) Armazena chave da API
 ├── .gitignore            # Arquivos/pastas ignorados no repositório
 └── README.md             # Documentação do projeto
```

---

## Segurança

- O arquivo `.env` **não** é versionado para proteger a chave da API.
- Uso correto do `.gitignore` para manter dados sensíveis fora do repositório.

---

## Resultados

Este projeto gera:
- Análises exploratórias sobre asteroides
- Gráficos de distribuições de tamanho, velocidade, e outros atributos
- Insights sobre a ameaça potencial de asteroides

---

## Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/kevintg99/nasa_asteroids_pipeline.git
   ```

2. Configure seu ambiente no Google Colab.

3. Preencha seu arquivo `.env` com sua chave da API da NASA:

   ```
   NASA_API_KEY=suachaveaqui
   ```

4. Execute os notebooks na seguinte ordem:

   - `notebooks/ingestao.ipynb`
   - `notebooks/tratamento.ipynb`
   - `notebooks/visualizacao.ipynb`

5. Explore os dados e gráficos gerados!

---

## Diferenciais do Projeto

- Separação clara das etapas (Ingestão, Tratamento e Visualização)
- Organização dos dados em `raw` e `processed`
- Segurança com variáveis de ambiente
- Visualizações profissionais com Seaborn

---

# Sobre o Autor

Feito com dedicação e um toque de insanidade técnica.

**Contato**:
- https://www.linkedin.com/in/kevingonzales01/
