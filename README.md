# BIZZ.IA — Auditoria Executiva (Blind-Audit™)

Landing de **Dossiê Forense Executivo** da BIZZ.IA: diagnóstico dos 6 eixos comerciais de conversão no WhatsApp, raio-X de atendimento e matriz de resgate high-ticket.

Site estático publicado via **GitHub Pages** com domínio próprio `bizzia.com.br`.

## Stack

- HTML estático + Tailwind CSS (CDN) + Chart.js + Font Awesome
- Deploy: GitHub Pages (branch `main`, raiz do repositório)

## Deploy

O site é servido da branch `main`, diretório raiz. O arquivo `.nojekyll` desativa o processamento Jekyll (site 100% estático).

URL pública: https://marcuscarvalho1322.github.io/blind/
Domínio próprio: https://bizzia.com.br/

### Domínio próprio (`bizzia.com.br`)

O DNS está hospedado no **registro.br**. Para o domínio resolver, é preciso criar no painel do registro.br (Sistema → Zona DNS do domínio):

| Tipo | Nome | Valor |
|------|------|-------|
| A | `@` (bizzia.com.br) | `185.199.108.153` |
| A | `@` (bizzia.com.br) | `185.199.109.153` |
| A | `@` (bizzia.com.br) | `185.199.110.153` |
| A | `@` (bizzia.com.br) | `185.199.111.153` |
| CNAME | `www` | `marcuscarvalho1322.github.io` |

> O registro TXT de verificação `_github-pages-challenge-MarcusCarvalho1322` já está criado (domínio já verificado no GitHub). Após adicionar os registros A/CNAME e propagar (até 24h), ative o **HTTPS forçado** em Settings → Pages.

## Arquivos

- `index.html` — dossiê completo
- `favicon.svg` — ícone da marca
- `.nojekyll` — desativa Jekyll
- `CNAME` — domínio próprio

## Aviso

Conteúdo de caráter ilustrativo/assistivo. Decisão final é sempre médica. Tratamento de dados conforme LGPD.
