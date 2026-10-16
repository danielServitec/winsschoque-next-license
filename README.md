# WinSSChoque Next: autorizações de licença

Este repositório público guarda o arquivo `autorizacao.json`, que o WinSSChoque Next (Servitec) baixa para renovar a licença de uso.

- `autorizacao.json`: documento assinado digitalmente pela Servitec. Só a Servitec consegue assiná-lo; o programa recusa qualquer arquivo alterado.
- `publica.pem`: a chave pública usada para conferir a assinatura.

O programa **só baixa** este arquivo; não envia nenhum dado ao repositório. Não edite o `autorizacao.json` manualmente.
