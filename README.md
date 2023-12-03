# API 

## API REST↓

Uma **API REST** (Representational State Transfer) é um estilo arquitetural para sistemas distribuídos baseados nos princípios do protocolo HTTP. Ela busca criar serviços web que sejam simples, escaláveis e interoperáveis. Alguns dos princípios fundamentais de uma API REST incluem:
**Arquitetura Cliente-Servidor:** Separação entre cliente e servidor para permitir evolução independente.
**Sem estado (Stateless):** Cada requisição do cliente contém toda a informação necessária, e o servidor não mantém o estado da sessão.
**Recursos Identificáveis:** Entidades acessíveis ou manipuláveis através de URLs únicas.
**Operações com Métodos HTTP:** Utilização de métodos HTTP como **GET**, **POST**, **PUT** e **DELETE** para operações sobre recursos.
**Representações:** Recursos podem ter diferentes representações, como **JSON**, **XML** ou **HTML**.

## API RESTful↓

**API RESTful** refere-se a uma API que segue os princípios e práticas da arquitetura REST. Ela é considerada "*RESTful*" quando adere aos princípios de REST de forma eficaz, oferecendo um design claro e consistente. Isso implica em:

**Utilização correta dos métodos HTTP:** Cada método é utilizado para uma operação específica (**GET** para recuperar, **POST** para criar, **PUT*& para atualizar, **DELETE** para deletar).
**Recursos bem definidos e identificáveis:** URLs intuitivas que representam recursos específicos.
**Manipulação de Representações:** Oferece diferentes representações (**JSON**, **XML**, **etc**.) para atender a diferentes necessidades dos clientes.
**Independência de estado:** O servidor não mantém o estado entre requisições do cliente.

# DIFERENÇAS

| Característica            | API REST                                            | API RESTful                                      |
|---------------------------|------------------------------------------------------|--------------------------------------------------|
| **Definição**             | É um estilo arquitetural.                            | Refere-se a uma API que segue os princípios REST. |
| **Conformidade aos Princípios REST** | Nem todas seguem rigorosamente.          | Segue de forma eficaz os princípios REST.         |
| **Métodos HTTP**          | Utiliza métodos HTTP, mas pode não seguir corretamente sua semântica. | Utiliza corretamente os métodos HTTP para operações sobre recursos. |
| **Recursos Identificáveis**| Pode ter URLs confusas ou pouco intuitivas.         | Possui URLs claras e intuitivas que representam recursos específicos. |
| **Independência de Estado**| Pode manter estado entre requisições.                | Mantém-se sem estado entre requisições (stateless). |
| **Representações**         | Oferece diferentes representações, mas nem sempre de forma eficiente. | Manipula eficientemente diversas representações de recursos. |

# HTTP

## HTTP Verbs↓

Os HTTP verbs, também conhecidos como métodos HTTP, são utilizados em APIs REST para realizar diferentes operações nos recursos.
Cada método tem um propósito específico:

| MÉTODO | Explicação |
|-----------------------------------------------------------|---------------------------------------------------------------------------|
|GET| Recupera dados de um recurso específico ou uma lista de recursos.|
|POST| Cria um novo recurso com os dados enviados no corpo da requisição.|
|PUT| Atualiza um recurso existente com os dados enviados no corpo da requisição.|
|DELETE| Remove um recurso especificado.|
|PATCH| Atualiza parcialmente um recurso, permitindo enviar apenas os dados que precisam ser alterados.|
|HEAD| Retorna apenas os cabeçalhos de uma resposta, sem o corpo, utilizado para checar a existência de um recurso.|
|OPTIONS| Retorna os métodos HTTP permitidos para um recurso específico.|
|TRACE| Utilizado para testes, retorna uma mensagem de eco contendo os dados enviados no corpo da requisição, usado para debug.|


*Os métodos **GET**, **POST**, **PUT**, **DELETE** e **PATCH** são os mais comuns e amplamente utilizados em APIs RESTful para realizar operações sobre os recursos.*

## HTTP Status Codes↓

Os códigos de status HTTP são retornados como parte das respostas de uma requisição feita a um servidor. Eles indicam o resultado da solicitação e fornecem informações sobre o estado da operação. Alguns dos códigos de status mais comuns incluem:

CÓDIGO | EXPLICAÇÃO
|------|------------|
| 1xx Informacional | Indica que a requisição foi recebida e está sendo processada.|
| 2xx Sucesso | Indica que a requisição foi recebida, entendida e aceita com sucesso.|
| 200 OK | Indica que a requisição foi bem-sucedida.|
| 201 Created| Indica que um novo recurso foi criado com sucesso.| 
| 3xx  Redirecionamento | Indica que mais ações são necessárias para completar a requisição.|
|301 Moved Permanently| Indica que o recurso requisitado foi movido permanentemente para outra localização.|  
| 4xx  Erro do Cliente| Indica que ocorreu um erro por parte do cliente na requisição.|
| 400 Bad Request| Indica que a requisição possui sintaxe inválida.| 
| 404 Not Found| Indica que o recurso requisitado não foi encontrado.|
| 5xx  Erro do Servidor| Indica que ocorreu um erro no servidor ao processar a requisição do cliente.|
| 500 Internal Server Error | Indica um erro interno no servidor ao processar a requisição.|
  
*Os códigos de status ajudam a entender e diagnosticar problemas durante a comunicação entre clientes e servidores em APIs RESTful.*

## **Autor do Resumo**
### *Nome:* *Darllan Matos da Silva*
### *Matricula:* 01530533




