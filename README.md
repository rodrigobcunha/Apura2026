# APURA 26 — GitHub Pages v2.4.2

Versão de arquivo único para GitHub Pages.

## Correção v2.4.2
A v2.4.1 tinha três declarações `export async function` preservadas dentro de um `<script>` clássico. Isso interrompia a execução do JavaScript antes da conexão com os dados e fazia a tela permanecer em "Conectando / Aguardando TSE".

Na v2.4.2 todo o JavaScript embutido é válido como script clássico, sem imports/exports.

## Publicação
Substitua o `index.html` da raiz do repositório pelo deste pacote, aguarde o deploy do GitHub Pages e faça Ctrl+F5.

Criado por Rodrigo Bahiense.
