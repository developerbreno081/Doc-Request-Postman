# 🖥 Tutorial Request API com o Postman
Realize o seus primeiros requests utilizando a ferramenta de testes API Postman.
## 👀 O que é o Postman?
O [Postman](https://www.postman.com/) é uma ferramenta de API Client utilizada pela comunidade de desenvolvedores para criar, compartilhar, testar e documentar APIs.
## 🔎 Modelo clássico de Request x Response - WEB
![image](https://github.com/developerbreno081/Documentacao_Request_Postman/assets/156582515/88546c97-b930-43b8-8198-08402b5550b4)
## 🤔 O que vamos aprender?
* Principais Verbos HTTP;
* Principais Status Code;
* Autenticação e Autorização de uma API;
* Organizar o Workspace do Postman e realizar os Requests.
# 📌 Principais Verbos HTTP
## 👀 O que é um Verbo HTTP? 
São comandos que indicam a ação a ser executada em um determinado Request. Esses métodos são usados para especificar a natureza da operação desejada. Cada método tem um significado específico e está associado a uma ação particular. Abaixo alguns dos principais Verbos HTTP:
 * GET - Pergunta ao servidor se ele pode te devolver alguma coisa, é um metodo totalmente seguro no sentindo de não causar efeitos colaterias no servidor;
 * POST - Diz ao servidor para guardar algo novo que você está mandando para ele;
 * PUT - Utilizado para atualizar ou substituir informações em um recurso existente no servidor; 
 * DELETE - Pede ao servidor para apagar algo específico.

😉 Observação: existe outros métodos, mas não irei abordar nesse artigo, pois vamos trabalhar com os verbos HTTPs simples. Como forma de consulta e estudos deixo esse link referencial sobre todos os recursos deste universo, [Verbos HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods).

# 📌 Principais Status Code
## 👀 O que é um Status Code? 
São códigos compostos por 3 dígitos para indicar para o Client alguma sinalização do servidor como Informativo, Confirmação, Redirecionamento, Erro do cliente ou Erro no servidor.
* 1XX: Informativo – a solicitação foi aceita ou o processo continua em andamento;
* 2XX: Confirmação – a ação foi concluída ou entendida;
* 3XX: Redirecionamento – indica que algo mais precisa ser feito ou precisou ser feito para completar a solicitação;
* 4XX: Erro do cliente- indica que a solicitação não pode ser concluída ou contém a sintaxe incorreta;
* 5XX: Erro no servidor – o servidor falhou ao concluir a solicitação.
