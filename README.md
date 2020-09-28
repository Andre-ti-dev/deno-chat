# Chat com Deno + JavaScript + WebSockets
Um simples chat feito com Deno para aprendizado desse novo runtime.
###### Requisitos
**Deno**: https://deno.land/#installation

As dependências serão baixadas assim que o projeto iniciar, pois o Deno permite que carreguemos módulos diretamente de uma url.

###### Rodando o projeto

Você pode utilizar o comando ``` deno run --allow-net server.js ``` ou utilizar o ``` .bat ``` para facilitar.

###### Aprendizado

O projeto foi desenvolvido a partir do tutorial do canal **The Codeholic** que você pode encontrar nesse link https://www.youtube.com/watch?v=XWyUtYL6ynE.

No projeto aprendemos algumas das diferênças do Deno em comparação ao Node.

Uma das diferênças que foi mencionado logo acima é a possibilidade de importar bibliotecas através de uma url, uma funcionalidade muito interessante.

O Deno também permite que utilizemos o TypeScript para desenvolver nosso projeto sem precisar adicionar nenhuma biblioteca a mais.

A segurança também é um ponto importante mostrado no tutorial, com o Deno temos que dizer oque iremos utilizar ou ele irá impedir sua aplicação de rodar, no projeto é necessário utilizar a flag ``` --allow-net ``` para permitir que o Deno utilize a rede.
