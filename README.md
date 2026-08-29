[README_SEAZONE_FINAL.md](https://github.com/user-attachments/files/31588107/README_SEAZONE_FINAL.md)
# Hackathon sobre Investimento Seazone — Itapema (SC)

**Vídeo de defesa (3 min):** https://drive.google.com/file/d/1cHcsyx3Smcijdzw33kalYWw8YPvs3CYm/view?usp=drive_link

## Objetivo do Projeto

Validação matemática da viabilidade de investimentos imobiliários em Itapema/SC, cruzando dados de receita de locação por temporada (Airbnb) com dados de aquisição imobiliária (VivaReal) para identificar o perfil de ativo com melhor equilíbrio entre rentabilidade, liquidez e resiliência sazonal.

## Recomendação Executiva

A análise recomenda **apartamentos compactos, especialmente de 1 quarto, na região central de Itapema**.

A decisão não considera apenas o maior Gross Yield isolado. A recomendação resulta do equilíbrio entre:

- **Gross Yield:** retorno bruto anual projetado sobre o capital investido;
- **Liquidez de mercado:** volume de ativos comparáveis disponível para uma estratégia escalável;
- **Resiliência sazonal:** comportamento da receita durante a baixa temporada.

O resultado indica aproximadamente **12,44% de Gross Yield anualizado**, considerando a premissa de 70% de ocupação utilizada na análise.

## Mapa do Repositório

- `analise_seazone_pedro.ipynb` — notebook com a modelagem em Python, tratamento dos dados, cálculos dos indicadores e geração dos gráficos.
- `relatorio.md` — relatório executivo com as respostas às perguntas do desafio, a análise de viabilidade e a recomendação final.
- `ai-log/AI_LOG_SEAZONE.md` — registro exportado da interação com a IA durante o desenvolvimento do projeto, documentando iterações, hipóteses, questionamentos, correções e decisões analíticas.
- `data/` — bases de dados originais utilizadas na análise.
- `index.html` — material original disponibilizado no desafio.

## Como Reproduzir a Análise

1. Baixe o arquivo `analise_seazone_pedro.ipynb` deste repositório.
2. Abra o notebook no **Google Colab**.
3. Faça o upload das cinco bases `.csv` originais disponíveis na pasta `data/`.
4. Execute o notebook utilizando **Ambiente de Execução → Executar tudo**.
5. O notebook processará as bases, realizará os cruzamentos e reproduzirá os indicadores e gráficos utilizados na análise.

> **Observação:** o ambiente do Google Colab é temporário. Os arquivos enviados diretamente para a sessão podem precisar ser carregados novamente caso a sessão seja reiniciada.

## Principais Conclusões

### 1. Perfil de imóvel

O perfil financeiramente mais eficiente identificado foi o **apartamento compacto de 1 quarto**, adequado ao modelo de estadias curtas e alto giro.

### 2. Localização

A **região central de Itapema** apresentou o melhor equilíbrio entre retorno e risco operacional dentro dos critérios adotados.

A Meia Praia possui forte volume de oferta e diárias elevadas, mas o alto custo de aquisição reduz sua eficiência financeira.

### 3. Características associadas às melhores receitas

Os anúncios de melhor desempenho no Centro apresentam principalmente comodidades de utilidade prática, como:

- cozinha equipada e micro-ondas;
- ar-condicionado;
- Wi-Fi e Smart TV;
- itens de conveniência, como secador de cabelo e ferro de passar.

### 4. Decisão de investimento

A tese de compactos no Centro foi **validada pelos dados analisados**, não por apresentar o maior retorno bruto isolado, mas por combinar rentabilidade, liquidez e maior resiliência na baixa temporada.

O bairro Morretes apresentou retorno bruto teórico superior, mas foi tratado como **falso positivo estratégico** após a contraprova de liquidez, por não apresentar volume suficiente para sustentar uma estratégia de escala.

## AI-First

A IA foi utilizada como parceira de desenvolvimento ao longo de todo o processo, apoiando:

- aprendizado e contextualização do domínio imobiliário;
- estruturação da metodologia;
- geração e iteração do código Python;
- exploração e tratamento das bases;
- formulação e teste de hipóteses;
- interpretação dos resultados;
- identificação de inconsistências;
- construção da recomendação final.

A decisão final, entretanto, foi conduzida por critérios definidos e questionados ao longo do processo, com validações e contraprovas antes da recomendação.

## Entregáveis

- **Vídeo de defesa:** link disponível na primeira linha deste README.
- **Transcrição do vídeo:** disponibilizada junto ao vídeo no Google Drive.
- **Análise:** `analise_seazone_pedro.ipynb`
- **Relatório:** `relatorio.md`
- **AI Log:** `ai-log/AI_LOG_SEAZONE.md`
