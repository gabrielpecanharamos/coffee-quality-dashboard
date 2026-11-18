# Dashboard de Cafés Especiais

## Prompt Principal

```text
Preciso desenvolver um dashboard interativo para um projeto sobre cafés especiais, utilizando uma base de dados que contém informações sobre cafés Arábica e Robusta de diferentes países.

1. Objetivo do projeto
Desenvolver um dashboard profissional, intuitivo e visualmente atraente que apresente os principais indicadores de qualidade, produção e características dos cafés especiais ao redor do mundo.
O dashboard deverá transformar as análises realizadas por meio de consultas SQL as quais irei enviar em informações visuais que facilitem a interpretação dos dados e permitam identificar padrões, diferenças e tendências.

2. Análises que deverão estar presentes
Cafés Arábica:
- Top 10 melhores cafés Arábica, considerando a pontuação.
- Top 10 melhores cafés brasileiros.
- Média de pontuação por país.
- Melhor café de cada país.
- Os 10 países com maior número de sacas produzidas.
- Impacto dos diferentes métodos de processamento na pontuação dos cafés.
- Relação entre altitude e pontuação dos cafés.

Cafés Robusta:
- Análise das notas sensoriais dos cafés Robusta.
- Média de pontuação por país.
- Número total de sacas produzidas.

Análise comparativa:
- Comparação entre Arábica e Robusta, considerando pontuação, produção e demais indicadores disponíveis na base.

3. Organização do dashboard
Organize as informações de maneira lógica, evitando excesso de gráficos e informações repetidas.
Considere a seguinte estrutura:
- Visão geral: indicadores principais, quantidade de registros, pontuação média e produção total.
- Arábica: classificação dos melhores cafés, desempenho por país, produção e características de qualidade.
- Robusta: características sensoriais, pontuação média e produção por país.
- Comparativo: diferenças entre Arábica e Robusta.

4. Visualização dos dados
Escolha os gráficos mais adequados para cada análise:
- Gráficos de barras para rankings.
- Mapas para distribuição geográfica, caso existam dados suficientes.
- Gráficos de dispersão para investigar a relação entre altitude e pontuação.
- Gráficos comparativos para métodos de processamento.
- Indicadores (KPIs) para apresentar métricas gerais.
- Gráficos de distribuição para explorar as notas sensoriais.
Não utilize gráficos apenas por estética. Cada visualização deve responder a uma pergunta específica.

5. Design e identidade visual
Desenvolva uma interface com aparência profissional. A identidade visual deverá remeter ao universo dos cafés especiais, utilizando tons de marrom, bege, verde-escuro e cores neutras.

Referência de cores:
| Elemento | Cor | Código |
| :--- | :--- | :--- |
| Fundo | Off-white | #F8F5EF |
| Cards | Branco quente | #FFFDF9 |
| Títulos | Marrom escuro | #49352A |
| Textos | Cinza amarronzado | #75685D |
| Destaques | Caramelo | #B98755 |
| Gráficos secundários | Bege café | #D8C3A5 |
| Destaque complementar | Verde oliva | #788064 |

Diretrizes de design:
1. Utilize fundos claros e textos escuros para garantir excelente legibilidade.
2. Reserve os tons mais escuros para títulos, números importantes e elementos de destaque.
3. Evite utilizar marrom escuro em grandes áreas do dashboard.
4. Mantenha uma paleta consistente entre todas as páginas.
5. Utilize cores diferentes para Arábica e Robusta, mantendo harmonia visual.
6. Evite excesso de bordas, sombras, gradientes e elementos decorativos.
7. Dê preferência a espaços em branco, alinhamento e boa distribuição dos elementos.
8. Utilize uma tipografia moderna, elegante e de fácil leitura.

6. Interatividade
Implemente filtros que permitam explorar os dados, como:
- País de origem.
- Tipo de café (Arábica ou Robusta).
- Método de processamento.
- Faixa de altitude.
- Faixa de pontuação.
Os filtros devem afetar os gráficos e indicadores relacionados.

7. Requisitos técnicos
1. Analise a estrutura dos dados e as consultas SQL disponíveis.
2. Identifique quais campos e indicadores podem ser utilizados.
3. Verifique se existem limitações ou inconsistências nos dados.
4. Sugira os gráficos mais apropriados para cada pergunta.
5. Evite inventar informações ou criar indicadores que não possam ser calculados a partir da base.

8. Resultado esperado
Entregue um dashboard que apresente uma visão abrangente do mercado de cafés especiais.
```

## Ajustes Feitos Após a Criação do Dashboard
```text
1. Escopo e Estrutura de Abas:
Remover a aba de "Visão Geral" do dashboard.
Manter o dashboard focado exclusivamente em 3 abas principais: Cafés Arábica, Cafés Robusta e Análise Comparativa.

2. Qualidade de Conteúdo e Ortografia:
Revisar e corrigir todo o texto do dashboard quanto à ortografia, concordância e gramática em português.

3. Perfil Sensorial Interativo:
Incluir a análise de perfil sensorial para os cafés do Top 10 Mundial (Arábica), Top 10 Brasileiros (Arábica) e Cafés Robusta.
Tornar o gráfico de perfil sensorial totalmente dinâmico e comparativo: listar todas as opções de cafés do Top 10 de cada categoria com caixas de seleção.
Permitir que o usuário clique e selecione quais lotes específicos deseja comparar sobrepostos no mesmo gráfico radar.

4. Ajustes Técnicos de Navegação:
Garantir que a alternância entre as abas (Cafés Arábica, Cafés Robusta e Análise Comparativa) funcione perfeitamente ao clicar no menu superior, exibindo os conteúdos e renderizando os gráficos de cada aba sem falhas ou travamentos de visualização.
```