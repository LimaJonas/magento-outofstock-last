## Magento Modulo Out of Stock Last

- Simples solução para levar produtos sem estoque para o final da lista do catalogo.
- Testado e criado usando Magento 2.3.6

### Instalação (Apenas manual)
- Faça o [download](https://github.com/LimaJonas/magento-outofstock-last/releases "download") do modulo.
- Em [Magento_Root]/App/Code, crie as pastas Jonaslima/Outofstock.
- Extraia arquivos dentro da pasta Autocomplete.
- Execute os comandos:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy pt_BR -f
php bin/magento cache:flush
```
- Pronto, instalado. Basta ir ao catalogo e testar!