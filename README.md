# Design Essencial no Figma para Criadores v6.2

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso aberto INEMA.CLUB. 18 aulas em 6 mÃ³dulos, inspirado no OSWork v6.2. Caso fictÃ­cio Luz de Rua.

ProduÃ§Ã£o completa estimada: 8â€“12 horas, incluindo estudo e montagens. As prÃ¡ticas curtas nÃ£o substituem a produÃ§Ã£o final. Computador e conta Figma necessÃ¡rios para editar.

Imagens criadas pelo recurso nativo de imagens do Codex. A ferramenta nÃ£o expÃµe seletor nem confirmaÃ§Ã£o de uma versÃ£o chamada 2.5; nenhum modelo externo foi substituÃ­do. Diagramas e exemplos tipogrÃ¡ficos sÃ£o HTML autoral, nÃ£o capturas do Figma. A interface real do Figma nÃ£o foi operada nesta produÃ§Ã£o; os caminhos foram conferidos na documentaÃ§Ã£o oficial em 25/09/2026. O kit contÃ©m imagem e roteiro, nÃ£o um arquivo .fig pronto.

ReconstruÃ§Ã£o: `python3 montar.py`. EvidÃªncias de auditoria e leitura em context/.

## English / EspaÃ±ol

[English](https://inematds.github.io/curso-figma-criadores/en/) Â· [EspaÃ±ol](https://inematds.github.io/curso-figma-criadores/es/)

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. IlustraÃ§Ãµes originais compartilhadas; progresso e anotaÃ§Ãµes separados por idioma.

ApÃ³s montar o portuguÃªs, reaplique os catÃ¡logos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem nÃ£o chama modelos nem redes. MudanÃ§as na fonte PT exigem revisar os catÃ¡logos `i18n/`. O motor oficial `assets/curso.js` Ã© preservado; a proteÃ§Ã£o de importaÃ§Ã£o Ã© gerada em `assets/curso-i18n.js` e nas ediÃ§Ãµes traduzidas.

EvidÃªncias em `context/validacao-i18n.md`. RevisÃµes por agentes sÃ£o simuladas, nÃ£o testes com alunos reais.

<!-- inema-backlink:v1 -->
## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/297-design-essencial-no-figma-para-criadores/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
<!-- /inema-backlink:v1 -->

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>