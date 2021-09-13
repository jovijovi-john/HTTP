## HTTP

    HyperText Transfer Protocol

    -> Protocolo de Transferência de Hypertexto 
        * Protocolo = Conjunto de regras
        * Hypertexto = Textos que podem ter áudios, imagens, links, etc.
        E para transferencia desses hipertextos, usamos o protocolo HTTP
  
## Troca de mensagens do browser com o servidor

    - O browser inicia a 'conversa' fazendo um pedido(**request**)
    - E o servidor responde essa conversa dando um (**response**)

**Message**

⠀          *pedido(request)* {

 ⠀              `-> Methods` {
                    Quando começa um pedido, precisamos especificar qual a ação nos queremos executar com esse pedido, ou seja, vai definir o tipo do pedido (qual ação que queremos executar no servidor)

                        ex: 
                            
 ⠀                          **GET (Pegar um recurso)**
                            
                                resumidamente, é o caminho onde estamos indo pedir
                                    *Local que enviaremos o pedido
                                    *Usaremos url

                                    ex: https://www.google.com/ é um recurso, é um local onde estamos indo fazer um pedido. Neste caso, um pedido do tipo get. E aí, o servidor vai responder com uma página do google
                            
⠀                           **POST (Criar um recurso)**
                };

⠀               `-> Headers(Cabeçalho)`{

                };

⠀               `-> Body (Corpo)`{

                };
        };

⠀       *Resposta(response)*{

⠀           `->Status Code`{
                Resposta do servidor sobre o estado do pedido (se está disponivel ou não, se deu algum problema)

⠀                   **200** - Sucesso
                    **301** - Redirecionamento
                    **404** - Recurso não encontrado
                    **500** - Erro interno do servidor
            };

⠀           `Headers`{
                !OPCIONAL

⠀               **Campo informativo**
                Baseado em *Propriedade: Valor* (ou name: value, property: value, ou key: value);
                
                Exemplo:

⠀                   **Content-Type**: application/json;         //tipo de conteúdo
⠀                   **User-Agent**: Chrome                      // client (browser)
⠀                   **Request URL**: www.google.com             // url que fiz o pedido
            }

⠀           `Body`
                !OPCIONAL

⠀               **HTML**                
⠀               **Conteúdo**                
⠀               **JSON**                

        };

        


## Curl

⠀**Inicialmente o curl é nosso user-agente(client)**

    no git bash

⠀*curl https://www.google.com*      -> vai trazer a response
⠀*curl -i https://www.google.com*   -> vai pegar o header
⠀*curl -v https://www.google.com*   -> vai pegar todos os headers, até os headers de saída(GET)


## Cliente -> é quem dá inicio a comunicação

    Ações:

        GET
        POST
        PUT
        DELETE

## Servidor -> É uma máquina que vai ouvir e processar os dados para dar a resposta

    Varios servidores podem se apresentar como um único computador          ->    um computador pode ter varios servidores
    Pode ter varios computadores no mundo se apresentando como um servidor

## PROXIES

    São representantes

    Ficam entre o cliente e o servidor
    Ajudam a fazer o transporte dos dados

⠀**Diversas informações**

⠀   *cache -> devolver uma informação mais rápido*
⠀   *filtro -> tipo um antivirus, vai ter controle sobre qual site pode abrir*
⠀   *load balancing -> vai controlar o carregamento, para devolver algo de maneira mais rápida*
⠀   *autenticação e autorização*