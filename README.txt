
Central_Operacional_News_v4.0_PRO
================================

Como publicar no GitHub Pages:
1. Extrair todo o conteúdo deste ZIP para a pasta do repositório.
2. Commit + push para o branch 'main' (ou gh-pages).
3. Em Settings -> Pages, selecione Branch: main / Root, e aguarde a publicação.
4. Acesse: https://<seu-usuario>.github.io/<seu-repo>/

Login: adm / adm
O site é 100% estático (HTML + JS + JSON) e usa Leaflet e Chart.js via CDN.
Os dados iniciais vêm de /data/mock_data.json. Para ativar feeds reais, substitua a função fetchFeeds no arquivo assets/app_v4.js para fazer fetch dos RSS desejados.
