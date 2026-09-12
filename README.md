# Suplementos

PWA pessoal de acompanhamento diário de suplementos, com sequência de dias e estatísticas por categoria.

**No ar:** https://esdraaline.github.io/suplementos-pwa/

## Como é

Site estático de página única (`index.html`). Sem build, sem dependências.
Para ver localmente, abra o `index.html` no navegador.

## A lista é de quem usa, não do código

O `index.html` não traz nenhum suplemento escrito dentro. Quem abre a página
cadastra os itens dele em cada período ("+ Adicionar"), e a lista fica salva só
no `localStorage` do próprio navegador. Nada disso é enviado para lugar nenhum
nem entra no repositório.

É de propósito: rotina de suplementação é dado pessoal de saúde, e este
repositório é público.

## Como publicar

Editar o `index.html`, commitar e dar push na `main`. O GitHub Pages publica sozinho.

