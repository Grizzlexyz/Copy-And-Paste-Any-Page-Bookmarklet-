# Feito Por "@marcos10pc"
Eu so Traduzi msm
# Don't F**** With Paste (Bookmark)

Bookmarklet que remove bloqueios de colar, copiar e recortar em sites.

## Como utilizar

1. Crie um novo favorito no navegador.
2. Defina qualquer nome.
3. Cole o código abaixo no campo de URL/endereço do favorito.
4. Salve.
5. Abra o site bloqueado.
6. Clique no favorito para remover as restrições.

## Script

```javascript
javascript:function remove_block(){const e=function(e){return e.stopImmediatePropagation(),!0};document.addEventListener("copy",e,!0),document.addEventListener("cut",e,!0),document.addEventListener("paste",e,!0),alert("Bloqueio Removido!")}remove_block();
