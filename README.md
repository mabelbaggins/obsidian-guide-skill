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
    └── metodologias.md           → Zettelkasten, PARA, MOCs, notas atômicas
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

## Contribuições

Sugestões, correções e melhorias são bem-vindas! Abra uma issue ou um pull request.

---
