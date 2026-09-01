# Jurisprudência TJSC

### Jurisprudência do TJSC para Claude, Cursor e agentes de IA

Pesquise jurisprudência do TJSC direto do Claude, ChatGPT ou do seu agente. Cada decisão traz órgão julgador, relator, data, o trecho que casou a busca e o link no site oficial. Decisão em segredo de justiça aparece com a ementa anonimizada, como o próprio tribunal publica. A mesma conexão alcança outros 16 tribunais. Grátis, sem login.

- ⚖️ **TJSC** e mais 16 tribunais na mesma conexão, incluindo STF, STJ e TST
- 📚 **Cível, família e consumidor**
- 🎯 **O trecho que CASOU a busca**, não a abertura burocrática do acórdão
- 🔗 **Link no site oficial** em cada resultado, para conferência
- 📄 **Inteiro teor sob demanda** quando a decisão permite
- 🚦 **Diz quando não sabe**: fonte indisponível ou acervo desatualizado vira aviso explícito
- 🔒 **Somente leitura**
- ⚡ **Grátis, sem login, sem credencial**
- 💬 **Funciona com qualquer cliente MCP**: Claude Desktop, Cursor, VS Code, Cline, Continue

[English version](README.en.md) · [Documentação completa](docs/) · [Skill pra agentes](skills/)

---

## Instalar em 1 clique

### Claude (Web e Desktop)

A Anthropic unificou a instalação de MCPs em `claude.ai/customize/connectors`. **O mesmo link serve pra Claude Web e Claude Desktop** (basta estar logado):

[➕ Abrir no Claude e conectar](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (se o deeplink não abrir): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Adicionar conector personalizado** → cole **Nome** `Jurisprudência TJSC` e **URL** `https://api.mcp.ai/p_tjsc`.

### Cursor

[➕ Instalar Jurisprudência TJSC no Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=tjsc&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF90anNjIn0=)

### VS Code (Copilot Chat)

[➕ Instalar Jurisprudência TJSC no VS Code](vscode:mcp/install?name=tjsc&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_tjsc%22%7D)

### ChatGPT, Manus, OpenClaw e mais 40+ clientes

Funciona em qualquer cliente MCP que suporte **MCP over HTTP**. A URL do servidor é sempre:

```
https://api.mcp.ai/p_tjsc
```

Detalhes por cliente: [INSTALL.md](INSTALL.md).

---

## Exemplos de uso

```
Pesquise jurisprudência do TJSC direto do Claude, ChatGPT ou do seu agente. Cada decisão traz órgão julgador, relator, data, o trecho que casou a busca e o link no site oficial. Decisão em segredo de justiça aparece com a ementa anonimizada, como o próprio tribunal publica. A mesma conexão alcança outros 16 tribunais. Grátis, sem login.
Jurisprudência do TJSC sobre alimentos gravídicos
Como o TJSC vem decidindo divórcio com partilha de bens?
Leia o inteiro teor do acórdão que você achou e resuma a tese
```

---

## 3 ferramentas disponíveis

| Tool | Descrição |
|---|---|
| `jurisprudencia_buscar` | Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese. |
| `jurisprudencia_sumulas` | Busca SÚMULAS (incluindo vinculantes) por termo. |
| `jurisprudencia_documento` | Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo). |

Detalhe de cada tool: [docs/ferramentas.md](docs/ferramentas.md)

---

## Preços

Grátis.

---

## Privacidade & LGPD

- **Somente leitura**, nenhuma ferramenta altera dados na origem.
- **Sub-processadores**: Serper (Google Search), o LLM host que você escolher (Claude, ChatGPT, Cursor, agente próprio). Lista completa em [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Os dados retornados pelas tools são enviados ao **LLM host que você escolher**, sub-processador fora do nosso controle. Recomendamos planos com opt-out de treinamento.

---

## Perguntas frequentes

**O TJSC é o único tribunal?**
Não. A conexão serve 17 tribunais: além do TJSC, STF, STJ, TST, TRF3, TRF4, CARF e os demais tribunais de justiça estaduais. Restringir a busca ao TJSC é opcional, e comparar com as cortes superiores é uma pergunta só.

**Precisa de login ou cadastro?**
Não. É grátis e sem credencial, e você não precisa de conta em nenhum tribunal.

**Serve para citar em petição?**
Serve para encontrar e ler. Todo resultado traz o link no site oficial, e a conferência lá é obrigatória antes de citar.

**Por que uma busca voltou vazia?**
Quase sempre é vocabulário: o tribunal nomeia a tese de um jeito diferente do coloquial, e a resposta sugere o que tentar. Se a fonte estiver indisponível no momento, ela diz isso explicitamente, o que é diferente de a decisão não existir.

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills, tudo MIT.


---

## Suporte

- 📧 [tjsc@mcp.ai](mailto:tjsc@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/tjsc-mcp/issues)
- 📄 [docs/](docs/)

---

## Licença

MIT — veja [LICENSE](LICENSE). O servidor MCP em `api.mcp.ai/p_tjsc` é proprietário (hosted); este repositório (manifestos, docs, skills) é MIT.
