# Validador de Sitemap XML e Indices de URLs

[![Validador Sitemap](https://img.shields.io/badge/TAVARDT-Sitemap%20XML-5b3cf5.svg)](https://tools.tavardt.com/br/validador-sitemap-xml/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Auditoria tecnica de sitemaps XML e sitemap indexes, analise de conformidade com protocolo sitemaps.org, validacao de esquemas e checagem de erros.

Desenvolvido e mantido pela divisao de engenharia de busca e infraestrutura web da **TAVARDT**.

***

## Capacidades de Validacao de Sitemaps XML

* **Conformidade com Protocolo Sitemaps.org**: Verificacao estrutural de tags raiz `<urlset>` e indices hierarquicos `<sitemapindex>`.
* **Inspecao de Atributos de Indexacao**: Checagem rigorosa de presenca e formatacao de `<loc>`, `<lastmod>` (W3C Datetime), `<changefreq>` e `<priority>`.
* **Auditoria de Integridade de URLs**: Deteccao de URLs mistas (HTTP em ambientes HTTPS), links quebrados e caminhos relativos invalidos.
* **Controle de Limites Tecnicos**: Validacao dos limites de 50.000 URLs por arquivo e tamanho descomprimido de 50MB.
* **Pontuacao de Saude Semantica**: Indice tecnico de 0 a 100 com recomendacoes de saneamento de estrutura XML.

***

## Instalacao e Execucao

Requer Python 3.8 ou superior sem dependencias externas adicionais.

```bash
git clone https://github.com/TAVARDT-Brasil/xml-sitemap-validator-br.git
cd xml-sitemap-validator-br
python sitemap_validator.py https://exemplo.com.br/sitemap.xml
```

Para gerar a saida em formato estruturado JSON:

```bash
python sitemap_validator.py https://exemplo.com.br/sitemap.xml -json
```

***

## Diagnostico Completo na Web

Para auditorias profundas e teste de sitemaps complexos:

* **Validador de Sitemap XML Oficial**
* **[Portal Corporativo TAVARDT](https://ag.tavardt.com/br/)**

***

## Consultoria em Arquitetura de Indexacao e Rastreamento

Para projetos de arquitetura de URLs de grande porte e conformidade com Protocolo Sitemaps.org e Diretrizes de Rastreamento, consulte os especialistas da **TAVARDT**.

***

## Links Úteis

* **Portal Corporativo:** https://ag.tavardt.com/br/
* **Suíte de Diagnósticos:** https://tools.tavardt.com/br/
* **Contato Técnico:** https://ag.tavardt.com/br/contato/

***

***

### Licença
Distribuído sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes completos.

***

© 2026 TAVARDT. Todos os direitos reservados.
