# Matriz de Prioridades de Notebooks e Desktops

Esta planilha foi criada para apoiar a avaliação, a classificação e a priorização da troca de equipamentos do parque de TI. Ela combina informações do equipamento, do setor e do perfil de uso para gerar uma pontuação que facilite decisões de renovação de notebooks e desktops.

> Arquivo utilizado: `Matriz de Prioridades Notebooks_Desk.xlsx`

## Objetivo

A matriz ajuda o time de TI a:

- centralizar os equipamentos avaliados;
- identificar usuários e áreas com maior necessidade;
- comparar os modelos existentes no parque;
- definir requisitos mínimos por setor ou cargo;
- organizar a ordem de substituição dos equipamentos;
- apoiar decisões de compra com critérios padronizados.

A pontuação deve ser usada como apoio à decisão. Antes de realizar uma troca, confirme também o estado físico do equipamento, garantia, idade, capacidade de upgrade, incidentes recorrentes e disponibilidade de estoque.

## Estrutura da planilha

O arquivo possui cinco abas principais.

### 1. Máquinas

É a área principal para consultar e consolidar os equipamentos avaliados.

Campos identificados:

| Campo | Como preencher |
|---|---|
| Nome | Nome do equipamento ou identificação utilizada pela empresa |
| ST | Número de patrimônio, Service Tag ou identificador equivalente |
| Setor - Função | Área e função do usuário responsável pelo equipamento |
| Usuário | Pessoa que utiliza o equipamento |
| Modelo | Modelo do notebook ou desktop |
| Pontuação | Resultado utilizado para representar a prioridade do equipamento |

A pontuação final deve ser interpretada conforme a regra adotada na planilha. Quanto maior a pontuação configurada, maior tende a ser a prioridade de análise ou substituição.

### 2. Distribuição

Relaciona o setor ou cargo com a necessidade operacional e com a configuração mínima recomendada.

Campos identificados:

| Campo | Finalidade |
|---|---|
| Setor / Cargo | Perfil profissional que será avaliado |
| Impacto / Necessidade | Grau de impacto da função e necessidade de desempenho |
| Modelo mínimo | Modelo mínimo indicado para o perfil |
| Recurso mínimo | Requisitos mínimos de hardware ou capacidade |
| Necessidade de troca | Indicador utilizado para orientar a substituição |

Exemplos de recursos mínimos que podem ser registrados:

- memória RAM mínima;
- tipo e capacidade do SSD;
- geração ou categoria mínima do processador;
- necessidade de GPU dedicada;
- quantidade de monitores suportados;
- recursos específicos, como leitor biométrico, câmera, Wi-Fi corporativo ou porta de rede.

### 3. Modelos

Mantém a classificação dos modelos existentes no parque.

| Campo | Finalidade |
|---|---|
| Parque | Identificação ou agrupamento do equipamento no parque |
| Modelos | Modelo comercial do notebook ou desktop |
| Nota | Classificação atribuída ao modelo |

Cadastre cada modelo apenas uma vez e mantenha um padrão de nomenclatura. Por exemplo, evite registrar o mesmo equipamento como `Latitude 5420`, `Dell 5420` e `DELL Latitude 5420`.

### 4. Setores

Registra o impacto e a necessidade de cada setor, formando a prioridade final da área.

Escala identificada na planilha:

| Nota | Classificação |
|---:|---|
| 1 | Muito baixo |
| 2 | Baixo |
| 3 | Médio |
| 4 | Alto |
| 5 | Muito alto |

Campos principais:

| Campo | Finalidade |
|---|---|
| Setor | Nome da área avaliada |
| Impacto | Consequência operacional de indisponibilidade ou baixo desempenho |
| Necessidade | Demanda de recursos computacionais da área |
| Prioridade Final | Resultado da classificação do setor |
| Utilização | Descrição ou nível de uso dos equipamentos |

### 5. Usuários

Classifica o perfil de utilização de cada usuário.

| Nota | Perfil de uso |
|---:|---|
| 1 | Muito baixa necessidade |
| 2 | Baixa necessidade |
| 3 | Usuário padrão |
| 4 | Alta performance |
| 5 | Muito alta performance |

Campos principais:

| Campo | Finalidade |
|---|---|
| Nome | Nome do usuário |
| Uso | Descrição do perfil de utilização |
| Usuário | Nota ou classificação atribuída ao perfil |

## Tutorial de uso

### Etapa 1: faça uma cópia de segurança

Antes de editar a matriz:

1. mantenha uma cópia original do arquivo;
2. crie uma versão de trabalho com a data da atualização;
3. se o arquivo estiver no SharePoint ou no OneDrive, confirme se o histórico de versões está habilitado.

Sugestão de nome:

```text
Matriz_Prioridades_Notebooks_Desk_2026-11.xlsx
```

### Etapa 2: atualize a aba Modelos

1. abra a aba **Modelos**;
2. cadastre os modelos existentes no parque;
3. atribua uma nota coerente para cada modelo;
4. considere processador, memória RAM, armazenamento, idade, garantia e capacidade de upgrade;
5. evite duplicidades na descrição dos modelos.

Exemplo de critério:

- nota baixa: equipamento antigo, limitado ou incompatível com o padrão atual;
- nota intermediária: equipamento adequado para atividades administrativas;
- nota alta: equipamento atual, com bom desempenho e maior vida útil prevista.

### Etapa 3: classifique os setores

1. acesse a aba **Setores**;
2. informe o nome de cada setor;
3. atribua uma nota de **Impacto**, de 1 a 5;
4. atribua uma nota de **Necessidade**, de 1 a 5;
5. revise o resultado em **Prioridade Final**;
6. descreva o padrão de utilização quando necessário.

Considere impacto alto para áreas em que a indisponibilidade de um computador interrompe atendimento, operação, entrega ao cliente ou atividade crítica.

### Etapa 4: classifique os usuários

1. acesse a aba **Usuários**;
2. cadastre o nome do usuário;
3. avalie as aplicações e atividades utilizadas;
4. selecione uma classificação de 1 a 5;
5. revise perfis de alta e muito alta performance com o gestor da área.

Referência prática:

- **1 a 2:** navegação, comunicação e tarefas leves;
- **3:** Microsoft 365, sistemas corporativos e multitarefa moderada;
- **4:** desenvolvimento, análise de dados, máquinas virtuais ou multitarefa intensa;
- **5:** cargas especializadas e de alta exigência, validadas tecnicamente.

### Etapa 5: configure a distribuição

1. abra a aba **Distribuição**;
2. relacione cada setor ou cargo ao impacto e à necessidade;
3. informe o modelo mínimo recomendado;
4. descreva o recurso mínimo esperado;
5. indique a necessidade de troca conforme o padrão definido pela empresa.

Exemplo:

| Setor / Cargo | Impacto / Necessidade | Modelo mínimo | Recurso mínimo | Necessidade de troca |
|---|---|---|---|---|
| Atendimento | Alta | Linha corporativa atual | 16 GB RAM e SSD de 512 GB | Avaliar equipamentos abaixo do padrão |
| Administrativo | Média | Linha corporativa intermediária | 8 ou 16 GB RAM e SSD | Trocar em caso de limitação ou fim de garantia |
| Desenvolvimento | Muito alta | Linha de alta performance | 16 ou 32 GB RAM, SSD e CPU de maior desempenho | Priorizar equipamentos incompatíveis com a carga |

Os valores acima são apenas exemplos. Adapte-os ao padrão de hardware e às políticas da empresa.

### Etapa 6: preencha a aba Máquinas

1. abra a aba **Máquinas**;
2. registre o nome do equipamento;
3. informe o Service Tag, patrimônio ou identificador adotado;
4. selecione o setor e a função;
5. informe o usuário responsável;
6. selecione o modelo correto;
7. confira a pontuação apresentada;
8. registre todos os equipamentos antes de iniciar a priorização.

### Etapa 7: valide a ordem de prioridade

Após preencher os dados:

1. ordene ou filtre a coluna **Pontuação**;
2. revise primeiro os equipamentos com maior prioridade;
3. confirme se os dados do setor, usuário e modelo estão corretos;
4. valide casos críticos com o gestor responsável;
5. verifique se há equipamento em estoque compatível com o perfil;
6. documente a decisão de trocar, manter, reparar ou realizar upgrade.

## Critérios complementares recomendados

A pontuação da matriz deve ser analisada junto com critérios técnicos e operacionais:

- idade do equipamento;
- término da garantia;
- compatibilidade com Windows 11;
- quantidade de memória RAM;
- saúde e capacidade do SSD;
- condição da bateria;
- falhas recorrentes registradas no service desk;
- danos físicos;
- desempenho durante o uso real;
- custo estimado de reparo;
- possibilidade de upgrade;
- disponibilidade de equipamento substituto.

## Boas práticas

- Não altere fórmulas sem criar uma cópia de segurança.
- Use listas suspensas sempre que estiverem disponíveis.
- Não mova nem exclua colunas usadas por fórmulas.
- Padronize nomes de setores, usuários e modelos.
- Faça uma revisão periódica, preferencialmente trimestral ou semestral.
- Restrinja a edição das abas auxiliares quando o arquivo for compartilhado.
- Registre decisões de troca no GLPI ou na ferramenta de inventário adotada.
- Não use apenas o cargo para definir prioridade. Valide a utilização real.

## Cuidados com dados

A planilha pode conter nomes de usuários, identificadores de equipamentos e informações internas. Por isso:

- não publique a planilha preenchida em um repositório público;
- use dados fictícios em exemplos e demonstrações;
- remova nomes, Service Tags, patrimônios e informações internas antes de compartilhar;
- mantenha o arquivo operacional em local corporativo autorizado, como SharePoint ou OneDrive;
- publique no GitHub somente o modelo vazio, quando permitido pela política da empresa.

## Solução de problemas

### A pontuação não é atualizada

1. confirme se o cálculo do Excel está definido como **Automático**;
2. verifique se o setor, o usuário e o modelo existem nas abas auxiliares;
3. confira se os nomes foram digitados exatamente da mesma forma;
4. verifique se alguma fórmula foi substituída por um valor manual;
5. atualize os vínculos e tabelas, caso existam.

### Um modelo ou setor não aparece na seleção

1. cadastre o item na aba correspondente;
2. confirme se ele está dentro do intervalo usado pela validação de dados;
3. remova espaços extras do início ou do fim do texto;
4. salve, feche e abra novamente o arquivo, se necessário.

### Os resultados parecem incorretos

1. revise as notas das abas **Modelos**, **Setores** e **Usuários**;
2. confirme se a escala está sendo aplicada de forma consistente;
3. verifique se as fórmulas da linha foram copiadas corretamente;
4. compare o resultado com um equipamento já validado;
5. restaure uma versão anterior se houver alteração indevida.

## Controle de alterações

Ao modificar critérios, notas ou fórmulas, registre:

- data da alteração;
- responsável;
- campo alterado;
- justificativa;
- impacto esperado na priorização.

Exemplo:

| Data | Responsável | Alteração | Justificativa |
|---|---|---|---|
| AAAA-MM-DD | Nome | Ajuste da nota de um modelo | Revisão do padrão mínimo do parque |

## Aviso

Esta matriz é uma ferramenta de apoio à decisão e não substitui a avaliação técnica do time de TI, a validação do gestor da área nem as políticas internas de compras, segurança e ciclo de vida dos ativos.
