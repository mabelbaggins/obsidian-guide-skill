# 🗂️ obsidian-guide — Claude Skill

Uma skill do Claude que transforma o Claude num guia prático de Obsidian — ajudando qualquer pessoa a configurar um vault do zero, entender como o app funciona, resolver problemas e pensar em como organizar suas notas.

Funciona tanto para iniciantes completos quanto para quem já usa o Obsidian e quer refinar o próprio sistema.

---

## O que esta skill faz

Quando instalada, a skill ensina o Claude a:

- **Configurar o Obsidian do zero** — vault, primeira nota, pastas, plugins essenciais, sincronização
- **Tirar dúvidas de uso** — wikilinks, backlinks, tags, propriedades (YAML/frontmatter), Daily Notes, Templater, Dataview
- **Pensar em organização** — explica e compara as metodologias mais usadas: Zettelkasten, PARA, MOCs e notas atômicas
- **Resolver problemas comuns** — links que não funcionam, templates que não aplicam, vault virou bagunça

A skill detecta automaticamente o perfil de quem pergunta (iniciante, usuário perdido, usuário avançado) e adapta a resposta.

---

## Como instalar

### Opção 1 — Direto pelo Claude.ai (mais fácil)
1. Baixe o arquivo `obsidian-guide.skill`
2. No Claude.ai, vá em **Configurações → Habilidades**
3. Clique em **Adicionar habilidade** e selecione o arquivo

### Opção 2 — Via upload no chat
1. Inicie uma conversa no Claude.ai
2. Faça upload do arquivo `obsidian-guide.skill`
3. Peça: *"Instale esta skill"*

---

## O que vem dentro

```
obsidian-guide/
├── SKILL.md                      → instruções principais da skill
└── references/
    ├── mecanica.md               → referência técnica (links, tags, propriedades, plugins)
    ├── metodologias.md           → Zettelkasten, PARA, MOCs, notas atômicas
    └── glossario.md              → vocabulário e gírias da comunidade Obsidian
```

---

## Requisitos

- Conta Claude Pro, Max, Team ou Enterprise
- Execução de código habilitada nas configurações

---

## Exemplo de uso

Depois de instalar, basta perguntar naturalmente:

> *"Como configuro o Obsidian do zero?"*
> *"Qual a diferença entre tags e links?"*
> *"Devo usar PARA ou Zettelkasten?"*
> *"Por que meu link não está funcionando?"*
> *"O que é um MOC?"*

---

## Glossário da comunidade

Alguns termos que você vai encontrar ao entrar no mundo Obsidian:

| Termo | Significado |
|---|---|
| **PKM** | Personal Knowledge Management — gestão do conhecimento pessoal |
| **Second brain** | "Segundo cérebro" — sistema externo que lembra e conecta por você |
| **Digital garden** | Vault que cresce organicamente, como um jardim — notas em evolução contínua |
| **Note gardening** | Ato de cuidar das notas: revisar, conectar, podar o que não serve |
| **Fleeting notes** | Notas temporárias, pensamentos soltos capturados na hora |
| **Atomic notes** | Uma nota = uma ideia. Pequenas e reconectáveis |
| **Evergreen notes** | Notas que crescem e evoluem com o tempo, nunca "vencem" |
| **Orphan notes** | Notas sem nenhum link — isoladas no grafo, conhecimento não integrado |
| **Brain dump** | Despejar tudo numa nota sem estrutura. Útil pra capturar, precisa ser processado |
| **MOC** | Map of Content — nota-índice que linka para outras notas de um tema |
| **LYT** | Linking Your Thinking — abordagem de Nick Milo baseada em MOCs |
| **Architect** | Quem planeja a estrutura antes de capturar |
| **Gardener** | Quem captura primeiro e deixa a estrutura emergir |
| **"Second brain, zero output"** | Vault lindo, sem nenhuma entrega real — autocrítica clássica da comunidade |
| **Plugin rabbit hole** | Passar horas configurando plugins em vez de escrever notas |

---



Sugestões, correções e melhorias são bem-vindas! Abra uma issue ou um pull request.

---

[Mabel Baggins](https://github.com/mabelbaggins) | Vendo o que tem além do Condado. ✨🍄
