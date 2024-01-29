# 🖥 Tutorial Request API com o Postman
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
👀 O que é um Verbo HTTP? 
São comandos que indicam a ação a ser executada em um determinado Request. Esses métodos são usados para especificar a natureza da operação desejada. Cada método tem um significado específico e está associado a uma ação particular. Abaixo alguns dos principais Verbos HTTP:
 * GET - Pergunta ao servidor se ele pode te devolver alguma coisa, é um metodo totalmente seguro no sentindo de não causar efeitos colaterias no servidor;
 * POST - Diz ao servidor para guardar algo novo que você está mandando para ele;
 * PUT - Utilizado para atualizar ou substituir informações em um recurso existente no servidor; 
 * DELETE - Pede ao servidor para apagar algo específico.

😉 Observação: existe outros métodos, mas não irei abordar nesse artigo, pois vamos trabalhar com os verbos HTTPs simples. Como forma de consulta e estudos deixo esse link referencial sobre todos os recursos deste universo, [Verbos HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods).

# 📌 Principais Status Code
👀 O que é um Status Code? 
São códigos compostos por 3 dígitos para indicar para o Client alguma sinalização do servidor como Informativo, Confirmação, Redirecionamento, Erro do cliente ou Erro no servidor.
* 1XX: Informativo – a solicitação foi aceita ou o processo continua em andamento;
* 2XX: Confirmação – a ação foi concluída ou entendida;
* 3XX: Redirecionamento – indica que algo mais precisa ser feito ou precisou ser feito para completar a solicitação;
* 4XX: Erro do cliente- indica que a solicitação não pode ser concluída ou contém a sintaxe incorreta;
* 5XX: Erro no servidor – o servidor falhou ao concluir a solicitação.
# 📌 Autenticação e Autorização de uma API
É de suma importância entender esse conceito, pois nem todas as APIs precisam necessariamente ter autenticação e autorização. A necessidade de implementar autenticação e autorização em uma API depende dos requisitos de segurança e do tipo de serviço que a API oferece. Em cenários mais complexos e em APIs que manipulam dados sensíveis ou realizam operações críticas.

👀 O que é uma Autenticação e Autorização de APIs? 
* Autenticação é o processo de determinar a identidade de um usuário;
* Autorização é o processo de determinar se um usuário tem acesso a um recurso.
## Exemplificando a Autenticação
Imagine que você está em frente à porta de sua casa. Para entrar, você precisa provar que é o dono da casa. Então, você tira a chave do bolso e a insere na fechadura. A chave é como sua identificação única, e inseri-la com sucesso na fechadura é como provar que você é quem diz ser. Neste caso, a ação de usar a chave para entrar na casa representa a autenticação - você está provando sua identidade.
## Exemplificando a Autorização
Agora, você está dentro de casa e quer acessar uma sala trancada. Você sabe que tem a chave daquela sala específica. No entanto, só porque você é o dono da casa (autenticado), não significa que você pode acessar todas as salas automaticamente. Você precisa verificar se tem a chave certa para a sala específica que deseja abrir. Se você tem a chave certa, você é autorizado a entrar. Se não, você não tem permissão. Portanto, autorização é sobre verificar se você tem permissão para acessar um recurso específico, mesmo depois de ter autenticado sua identidade.
# 📌 Organizar o Workspace do Postman e realizar os Requests
O [Postman](https://www.postman.com/) ofere a comunidade duas formas de utilização da plataforma, via Desktop ou WEB.
* Versão Desktop para download: [Windows](https://www.postman.com/downloads/?utm_source=postman-home) | [Mac](https://www.postman.com/downloads/?utm_source=postman-home) | [Linux](https://www.postman.com/downloads/?utm_source=postman-home)
* Versão WEB para login ou criar uma conta: [Postman WEB](https://identity.getpostman.com/login)

### Passo 1: Criando uma [Collection](https://www.postman.com/collection/)
O vídeo a seguir não possui áudio, apenas demostrativo.

https://github.com/developerbreno081/Documentacao_Request_Postman/assets/156582515/50a72b4f-a464-4e92-bf10-46cae0d34712

### Passo 2: Documentação da API Petstore
Iremos utilizar uma API de demonstração da plataforma Swagger o intuito é trabalhar com a categoria de "pet"
para executar nossos Requests. [Documentação Swagger Petstore](https://editor.swagger.io/?url=https://petstore.swagger.io/v2/swagger.yaml).

![print](https://github.com/developerbreno081/Documentacao_Request_Postman/assets/156582515/ab17953c-41c7-4f76-a7b4-a4d7b32381d4)

### Passo 3: Adicionando os Requests na [Collection](https://www.postman.com/collection/)
O vídeo a seguir não possui áudio, apenas demostrativo.

https://github.com/developerbreno081/Documentacao_Request_Postman/assets/156582515/9568e732-671d-4506-887d-b63fa1566e22

### Roteiro utilizado no vídeo para adicionar as Requests

Método de Autorização apikey

```
key: api_key
```
```
value: api_key
```
```
 in: Header
```

Base URL 

```
 https://petstore.swagger.io/v2
```
Verbos a serem utilizados (POST, GET, PUT e DELETE)  

Paths e seus Respectivos significados
```
 /pet (Add novo pet no store)
```
```
/pet/{petId} (Buscando pet por id)
```
```
/pet (Atualizando pet existente)
```
```
/pet/{petId} (Excluindo pet)
```









