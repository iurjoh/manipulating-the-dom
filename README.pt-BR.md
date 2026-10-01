# DOM manipulation lesson

[English](README.md)

## Ideia e processo

Código educacional revisado em 01/10/2026. Não foram encontrados plano datado, wireframes ou diário pessoal nos arquivos revisados. Este README registra o exercício implementado, sem inventar histórico. A estrutura revisada não tem backend ou banco.

## Arquitetura e design

index.html é exemplo com CSS Bootstrap 3.3.7, navegação, jumbotron e parágrafo lead. Único script local carregado: js/app.js, que registra Hello World. js/transcript.js é aula separada de console para localizar nós, criar elementos e alterar lista, não funcionalidade ativa. Contém problemas como coleção em insertBefore, getElementByTagName e encadeamento tipo jQuery em coleção DOM. A página não carrega JavaScript Bootstrap para o controle de collapse.

## Preview local

```bash
python3 -m http.server 8000
```

Abra `http://localhost:8000/index.html`. Arquivos estáticos revisados não exigem instalação de pacotes; fontes/bibliotecas externas precisam de rede. Comando não executado nesta atualização.

## Testes e limites

Nenhuma suíte automatizada encontrada na listagem revisada da raiz. Comportamento no navegador não testado e nenhum deploy público confirmado aqui. Use o roteiro seção por seção, conferindo seletor/tipo de nó. Teste navegação e collapse mobile separadamente; CSS Bootstrap não torna o controle funcional. Revise título ausente da página e teclado antes de reutilizar.

## Capturas

Nenhuma captura de aplicação verificada ou adicionada. Capturas futuras devem usar arquivos datados em `docs/assets/`, mostrar estados inicial/alterado em desktop/mobile e identificar o exercício de aula. Só adicione links após as imagens existirem.

## Créditos e licença

Baseado no [template Gitpod do Code Institute](https://github.com/Code-Institute-Org/gitpod-full-template) e exercícios do curso. Direitos de código, imagens e bibliotecas de terceiros preservados, sem nova licença. README original mantido no [apêndice em inglês](README.md#original-readme), como referência histórica.
