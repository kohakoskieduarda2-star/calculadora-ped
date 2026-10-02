# Calculadora Pediátrica de Emergência

Versão web/PWA pronta para publicação pelo GitHub Pages.

## Arquivos que devem permanecer na raiz
- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `.nojekyll`

## Publicar no GitHub Pages
1. Criar um repositório.
2. Enviar todos os arquivos deste pacote para a raiz do repositório.
3. Abrir **Settings → Pages**.
4. Em **Build and deployment**, selecionar **Deploy from a branch**.
5. Selecionar a branch `main` e a pasta `/ (root)`.
6. Salvar.
7. Aguardar a publicação do endereço fornecido pelo GitHub Pages.

O `index.html` contém a calculadora final. O manifest e o service worker permitem a experiência PWA e cache offline após a primeira visita.

## Atenção
Para uso institucional/assistencial, manter controle de versão e homologação clínica da versão publicada.
