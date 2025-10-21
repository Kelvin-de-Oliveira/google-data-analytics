# Resumo do Curso 

O curso **“Process Data from Dirty to Clean”**, parte do **Certificado Profissional Google Data Analytics**, aborda o processo de transformar dados brutos, inconsistentes e imprecisos em conjuntos de dados limpos e confiáveis, prontos para análise. Ele guia o aluno pelos princípios da integridade dos dados, pelas técnicas práticas de limpeza utilizando planilhas e SQL, e pelos métodos de validação e verificação dos resultados de limpeza.

---

## Conteúdo e Aprendizado

### 1. Entendendo a Integridade dos Dados

Os participantes exploram o conceito de **integridade dos dados** e os riscos que podem comprometê-la, como erros de replicação, problemas de transferência ou manipulação incorreta. O curso enfatiza a importância de manter **precisão, completude, consistência e validade** em todos os conjuntos de dados.

**Principais restrições de integridade:**
* **Tipo de dado:** Os valores devem seguir formatos predefinidos (por exemplo, data, número).
* **Intervalo:** Os dados devem estar dentro de limites válidos.
* **Unicidade:** Nenhum identificador deve se repetir.
* **Campos obrigatórios:** Informações essenciais não podem ficar em branco.
* **Validação entre campos:** Os valores relacionados devem estar logicamente alinhados.
* **Precisão e completude:** Os dados devem refletir a realidade e conter todos os componentes necessários.

**Exemplo:** Padronizar formatos de data em um conjunto de dados global garante que 12/10/20 não seja interpretado erroneamente como 10 de dezembro de 2020 em vez de 12 de outubro de 2020.

---

### 2. Gerenciando Problemas de Qualidade dos Dados

O curso ensina a identificar e resolver **problemas de dados**, como dados ausentes, insuficientes ou incorretos. São apresentadas estratégias práticas, como o uso de **dados proxy** quando o conjunto desejado está indisponível ou é pequeno demais, e a importância do bom senso ao decidir se dados com erro devem ser excluídos.

**Problemas e soluções comuns:**
| Problema | Solução Exemplo |
|-----------|----------------|
| Ausência de dados | Usar conjuntos de dados proxy ou coletar uma amostra. |
| Poucos dados | Combinar conjuntos de dados ou restringir o escopo da análise. |
| Dados incorretos | Reforçar os requisitos e corrigir na fonte. |

Os alunos também são apresentados a **conjuntos de dados abertos e públicos** (como os disponíveis no Kaggle) como recursos valiosos para prática e análise.

---

### 3. Amostragem e Fundamentos Estatísticos

O curso introduz os conceitos de **determinação do tamanho da amostra**, **nível de confiança** e **margem de erro**, fundamentos estatísticos essenciais para análises confiáveis.

**Termos-chave:**
* **População:** O grupo completo em estudo.
* **Amostra:** Subconjunto representativo da população.
* **Nível de confiança:** Probabilidade de que os resultados representem corretamente a população.
* **Margem de erro:** Diferença esperada entre os resultados da amostra e da população.

**Exemplo:** Em uma pesquisa com funcionários, um nível de confiança de 95% e uma margem de erro de 5% garantem que os resultados sejam representativos da força de trabalho.

---

### 4. Identificando e Limpando Dados Sujos

O curso define **dados sujos** como informações incompletas, inconsistentes, duplicadas ou desatualizadas, explorando suas causas e os impactos negativos para os negócios.

**Tipos de dados sujos:**
* **Duplicados:** Entradas repetidas por erro de importação ou digitação.
* **Desatualizados:** Dados antigos que não refletem mais a realidade.
* **Incompletos:** Falta de informações essenciais.
* **Incorretos:** Erros humanos ou gerados por sistemas.
* **Inconsistentes:** Formatos e estruturas diferentes para o mesmo tipo de informação.

**Impacto nos negócios:** Dados sujos resultam em análises incorretas, perdas financeiras e decisões erradas — problemas especialmente graves em áreas como finanças, saúde e marketing.

---

### 5. Boas Práticas e Ferramentas de Limpeza de Dados

Os alunos praticam **processos de limpeza de dados** em planilhas e SQL, utilizando ferramentas e fórmulas integradas para identificar, corrigir e evitar erros.

**Erros comuns a evitar:**
* Ignorar erros de ortografia ou formatação
* Deixar de verificar valores ausentes ou fora de campo
* Não fazer backup antes da limpeza
* Não documentar os erros e correções
* Perder o foco nos objetivos do projeto

**Técnicas de planilha:**
* **Formatação condicional:** Destacar células vazias ou anômalas.
* **Remover duplicatas:** Excluir entradas repetidas automaticamente.
* **SPLIT, TRIM, LEFT, RIGHT, MID, CONCATENATE:** Limpar e manipular strings.
* **COUNTIF e LEN:** Identificar outliers e validar comprimentos.
* **Tabelas dinâmicas e gráficos:** Resumir e visualizar problemas de qualidade.
* **VLOOKUP:** Combinar dados entre planilhas para verificação.

---

### 6. SQL e Transformação de Dados

O curso compara o uso de **planilhas e bancos de dados SQL**, destacando quando cada um é mais adequado:

| Planilhas | Bancos de Dados SQL |
|------------|---------------------|
| Conjuntos de dados pequenos | Dados em larga escala |
| Entrada manual | Consultas automatizadas |
| Visualizações integradas | Processamento rápido |
| Trabalho individual | Colaboração em equipe |

São introduzidas **funções básicas de SQL** para limpeza e formatação, com foco em operações de **string** e **conversão de tipos** para manter a consistência.

---

### 7. Verificando os Resultados da Limpeza de Dados

O curso apresenta uma **lista de verificação de limpeza de dados** para garantir que os conjuntos finais estejam corretos e alinhados com os objetivos do projeto.

**Itens da checklist:**
* Verificar **NULLs**, duplicatas e valores fora de campo
* Garantir consistência de **tipos de dados**, **formatos de data** e **rótulos de coluna**
* Validar a **lógica de negócios** (ex: receita > 0)
* Revisar se os dados continuam alinhados aos objetivos do projeto

Os alunos também aprendem a manter **registros de alterações (changelogs)** e usar **sistemas de controle de versão** para documentar, revisar e reverter transformações de dados de forma segura.

---

### 8. Funções Avançadas e Automação na Limpeza de Dados

Funções avançadas de planilha como **IMPORTRANGE**, **QUERY** e **FILTER** permitem automatizar, sincronizar e extrair dados de múltiplas fontes com eficiência. Essas ferramentas reproduzem as funcionalidades de **SELECT** e **WHERE** do SQL, tornando os processos de limpeza mais escaláveis.

**Exemplo:** Usar IMPORTRANGE para atualizar automaticamente um conjunto de dados de transações diárias de uma fonte externa garante consistência sem necessidade de cópia manual.

---

### 9. Fortalecendo Habilidades Técnicas

O curso destaca as principais **competências técnicas** para aspirantes a analistas de dados:
* **SQL:** Consultar e limpar bancos de dados.
* **Planilhas:** Manipular e organizar dados.
* **Ferramentas de visualização:** Comunicar resultados de forma clara.
* **R/Python:** Linguagens para análises mais avançadas (opcional para iniciantes).

---

## Habilidades Desenvolvidas

Ao final do curso, o aluno desenvolve habilidades práticas em:

* Garantir e manter a **integridade dos dados**
* Aplicar **SQL** e **funções de planilha** para limpeza
* Identificar e corrigir **dados sujos ou inconsistentes**
* Calcular **tamanho de amostra** e **margem de erro**
* Automatizar processos de limpeza com **consultas e fórmulas**
* **Verificar e documentar** resultados de limpeza
* Aprimorar a **proeficiência técnica** em ferramentas analíticas

---

## Conclusão

Este curso me proporcionou o conhecimento e as ferramentas essenciais para transformar dados brutos e pouco confiáveis em conjuntos de dados limpos e validados. Por meio da prática com planilhas e SQL, desenvolvi confiança em garantir a integridade dos dados, manter sua qualidade e verificar resultados, fortalecendo habilidades fundamentais para meu crescimento como analista de dados.