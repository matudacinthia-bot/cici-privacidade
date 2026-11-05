# CICI · Política de Privacidade

## O que é
Página estática com a política de privacidade do app OAuth "hermes-cinthia", usado pela CICI (assistente pessoal da Cinthia, projeto `hermes`). Serve como "Página inicial do aplicativo" e "Link da Política de Privacidade" na tela de Branding do Google Auth Platform, exigidos para tirar o app do modo "Testando".

## Stack e ferramentas
- Linguagem/framework: HTML e CSS puros, sem script e sem fonte externa
- Banco de dados: nenhum
- Hospedagem: GitHub Pages (branch `main`, raiz), repositório público `matudacinthia-bot/cici-privacidade`

## Como rodar
```bash
# abrir o index.html no navegador; não há build
```

## Estrutura de pastas
- `index.html`: a página
- `docs/para-que-serve.md`: por que a página existe e onde ela é usada

## ESTADO ATUAL
**Última atualização:** 2026-11-05
**Status:** no ar

### Onde parei
Página publicada em https://matudacinthia-bot.github.io/cici-privacidade/ e usada no Branding do Google Auth Platform. Com ela, a Cinthia passou o app hermes-cinthia de "Testando" para "Em produção" em 05/11, e o Google da CICI foi reautorizado e está funcionando.

### Próximos passos
- [x] Colar a URL nos campos "Página inicial do aplicativo" e "Link da Política de Privacidade" do Branding no Google Auth Platform (projeto hermes-cinthia)
- [x] Publicar o app (sair do modo "Testando")
- Nada pendente. Mexer só se os escopos do app mudarem.

### Pendências e problemas conhecidos
- Se os escopos do app mudarem, atualizar a lista de dados e a data da página.
- A página diz que os dados não são usados para treinar IA "pelo aplicativo"; a política do provedor do modelo (Ollama Cloud) sobre treinamento não foi conferida.
- Tirar a página do ar quebra a exigência do Google para o app em produção.

## Decisões importantes
| Data | Decisão | Motivo |
|------|---------|--------|
| 2026-11-05 | GitHub Pages em repositório público só com a página | Autorizado pela Cinthia; o Google exige URL pública |
| 2026-11-05 | Sem e-mail, telefone, IP ou nome de servidor na página | Contato pelo perfil do GitHub |

## Convenções deste projeto
Repositório público: nada de segredo, token ou dado do servidor aqui.

## Histórico de sessões
<!-- SESSOES:INICIO -->
- [2026-11-05] criação da página de privacidade e publicação no GitHub Pages
- [2026-11-05 17:45] URL colada no Branding do Google e app hermes-cinthia publicado em produção; Google da CICI reautorizado
<!-- SESSOES:FIM -->
