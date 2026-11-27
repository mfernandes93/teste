Preciso alinhar alguns pontos para a construção do método no Mobius:

Estrutura definitiva do payload, incluindo os campos, tipos e obrigatoriedade.

Qual identificador devemos enviar no requisicaoId.

Se os valores de passo e ordem serão fixos para o nosso fluxo.

Como será realizado o tratamento de erros caso algum dado enviado esteja incorreto.

A validação dos dados será retornada na própria resposta do POST ou o processamento será assíncrono, sendo necessário consultar outro endpoint para obter o status e eventuais erros?

Caso exista um endpoint de consulta, qual identificador devemos utilizar e qual será a estrutura de retorno?
