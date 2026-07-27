# Governança

Esta pasta contém as regras mínimas para manter o repositório compreensível, seguro e útil ao longo do tempo.

## Princípios

1. A IA é copiloto; a decisão e a responsabilidade são humanas.
2. Um artefato deve ter contexto, finalidade e responsável identificáveis.
3. Experimentos devem ser avaliados antes de entrarem nos processos operacionais.
4. Dados de clientes, documentos estratégicos e credenciais não devem ser publicados no repositório.
5. Toda decisão estrutural ou operacional relevante deve ser registrada em [`decisoes`](decisoes).

## Fluxo de maturidade

`ideia` → `experimento` → `validado` → `operacional` → `revisão`

## Convenção de nomes

Use nomes em minúsculas, sem acentos, com hífens e, quando houver uma sequência, com prefixo numérico (`01-`, `02-`, etc.).

## Separação entre estudo e operação

- `01-curso`: conhecimento, notas e exercícios;
- `02-lutz-pi`: processos, projetos e artefatos que possam apoiar a operação;
- `04-laboratorio`: testes e protótipos que ainda não devem ser tratados como procedimento oficial.

## Privacidade

Antes de versionar um arquivo, remova dados pessoais, informações processuais sigilosas, documentos de clientes, chaves de API e credenciais. Quando necessário, use exemplos fictícios ou arquivos locais ignorados pelo Git.
