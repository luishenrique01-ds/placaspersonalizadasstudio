# Placas Personalizadas Studio

Protótipo responsivo em HTML, CSS e JavaScript puro, preparado para deploy na Vercel.

## Como publicar na Vercel
1. Entre em https://vercel.com e escolha **Add New → Project**.
2. Importe o repositório `luishenrique01-ds/placaspersonalizadasstudio`.
3. Não precisa configurar build command nem framework; deixe como projeto estático e clique em Deploy.

## Antes de receber pedidos reais
No final de `index.html`, procure por:
```js
const phone="";
```
Substitua o valor vazio pelo número comercial do WhatsApp, com código do país e DDD, somente números. Exemplo fictício: `const phone="5511999999999";`

O botão de pedido ainda funciona como protótipo: sem o número configurado, ele avisa e tenta copiar os detalhes. A prévia é ilustrativa, e o QR Code mostrado não é gerado a partir do link informado. Confirme preços, tamanhos, arte, pagamento e frete antes de vender.
