# Repositório de APIs públicas portuguesas

Este repositório é um agregador de APIs e dados públicos, ou semi públicos, de entidades Portuguesas.

## Regras de contribuição

Se quiseres contribuir, corrigir algo, ou até recomendar melhorias, cria um pull request. Caso queiras adicionar alguma entrada nova, garante que segues a estrutura usada. Cada entrada deverá conter:
- API (nome e link da API)
- Info (curta explicação sobre a API)
- Categoria (Governo, Saúde, Meteorologia, Transportes, Media, Outros)
- Spec (link, com ícone, para a spec da API)
- Docs (link, com ícone, para documentação da API)

### Como posso começar?

1. Faz fork do projeto (<https://github.com/devpt-org/public-api-portugal/fork>)
2. Cria uma branch para a tua feature (`git checkout -b add/bank-public-api`)
3. Faz commit das tuas alterações (`git commit -am 'Add some bank public api'`)
4. Faz push da tua branch para master (`git push origin add/bank-public-api`)
5. Cria um novo Pull Request

## Conteúdos
- [Governo](#governo)
- [Saúde](#saúde)
- [Meteorologia](#meteorologia)
- [Transportes](#transportes)
- [Media](#media)
- [Outros](#outros)

## APIs

### Governo

| API         |  Info | Spec | Docs |
| ----------- | ----- | :--: | :--: |
| [Dados Gov](https://dados.gov.pt/pt/docapi/) | Dados abertos em Portugal | [✅](https://dados.gov.pt/api/1/swagger.json) | [✅](https://dados.gov.pt/pt/docapi/)
| [GEO PT API](https://github.com/jfoclpf/geoptapi) | Regiões de Portugal | ❌ | [✅](https://github.com/jfoclpf/geoptapi)
| [INE](https://www.ine.pt/xportal/xmain?xpid=INE&xpgid=ine_api&INST=322751522&xlang=pt) | Base de dados de difusão do INE | ❌ | [✅](https://www.ine.pt/ngt_server/attachfileu.jsp?look_parentBoui=322762582&att_display=n&att_download=y)
| [Lisboa Aberta](http://lisboaaberta.cm-lisboa.pt/index.php/pt/desenvolvedores) | Dados abertos de Lisboa | ⁉️ | ⁉️
| [NIF](https://www.nif.pt/api/) | Validação programatica de NIF | ❌ | ❌
| [Turismo de Portugal](https://dadosabertos.turismodeportugal.pt/) | Dados sobre informação turística | ⁉️ | ⁉️

### Saúde

| API         |  Info | Spec | Docs |
| ----------- | ----- | :--: | :--: |
| [Vost Covid](https://covid19-api.vost.pt/) | Dados DGS COVID-19 | [✅](https://covid19-api.vost.pt/swagger.json) | ❌

### Meteorologia

| API         |  Info | Spec | Docs |
| ----------- | ----- | :--: | :--: |
| [IPMA](https://api.ipma.pt/) | Dados meteorológicos e oceanográficos | ❌ | [✅](https://api.ipma.pt/)

### Transportes

| API         |  Info | Spec | Docs |
| ----------- | ----- | :--: | :--: |
| [CP](https://github.com/juliuste/comboios) | Cliente em JS para a API da CP | [✅]() | [✅](https://github.com/juliuste/comboios)
| [EMEL](https://emel.city-platform.com/opendata/) | Dados abertos da EMEL | [✅](https://emel.city-platform.com/opendata/) | ❌
| [Metro de Lisboa](https://api.metrolisboa.pt/store/apis/info?name=EstadoServicoML&version=1.0.1&provider=admin) | Conjunto de APIs disponibilizadas pelo ML | [✅](https://api.metrolisboa.pt/store/api-docs/admin/EstadoServicoML/1.0.1?gwType=undefined&gwName=undefined) | [✅](https://api.metrolisboa.pt/store/apis/info?name=EstadoServicoML&version=1.0.1&provider=admin#tab2)
| [TransporLis](https://www.transporlis.pt/Default.aspx?tabid=258&language=pt-PT) | Dados abertos dos transportes públicos de Lisboa | ⁉️ | ⁉️

### Media

| API         |  Info | Spec | Docs |
| ----------- | ----- | :--: | :--: |
| [Observador](https://observador.pt/wp-json/) | Dados do Observador | ❌ | ❌
| [PT-NEWS-EXTRACTOR](https://github.com/spamz23/PT-NEWS_EXTRACTOR) | Notícias de jornais | [✅](https://pt-news-extractor.herokuapp.com/#operation/cm_url_search_create) | ❌
| [Público](https://www.publico.pt/api/list/ultimas) | Dados do Público | ❌ | ❌

### Outros

| API         |  Info | Spec | Docs |
| ----------- | ----- | :--: | :--: |
| [arquivo.pt](https://arquivo.pt/) | Acesso a conteúdo histórico da Web | Outros | ❌ | [✅](https://github.com/arquivo/pwa-technologies/wiki/Arquivo.pt-API)