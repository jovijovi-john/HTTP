## Status code 

    Servem para fazer uma comunicação um pouco mais clara entre o servidor e o client

⠀   **⠀100⠀** : Continue


        É tipo um, "blz irmão, segue o baile"
⠀   
    **⠀200⠀** : Ok (GET, POST)

⠀       *⠀201⠀* : Created (PUT)
⠀       *⠀204⠀* : No content (PUT, DELETE)

⠀   **⠀300⠀** :

⠀       *⠀301⠀* : Moved Permanently
            
                -> Aquele recurso foi movido. Geralmente vem com header-location pra nova localização (GET)

⠀       *⠀308⠀* : Permanent redirect
            
                -> Parecido com o 301. Geralmente vem com header-location pra nova localização (POST)

⠀       *⠀302⠀* : Found
            
                -> Encontrado mas movido temporariamente (Parecido com 307) do recurso. Geralmente vem com header-location pra nova localização. (GET)
            
⠀       *⠀307⠀* : Temporary Redirect

                -> Parecido com 302. Geralmente vem com header-location pra nova localização. (outros que não GET)

⠀   **⠀400⠀**

⠀       *⠀400⠀* : Bad Request
            
                -> Pedido mal efetuado (pedido de maneira ruim)

⠀       *⠀401⠀* : Unauthorized

                -> Você não está autorizado a receber esse recurso, falta enviar algum token ou key de autenticação

⠀       *⠀403⠀* : Forbidden

                -> Não tem permissão para acessar aquele recurso.

⠀       *⠀404⠀* : Not Found

                -> Recurso não encontrado

⠀       *⠀405⠀* : Method Not Allowed

                -> Método não está permitido para aquele escopo

⠀       *⠀429⠀* : Too many requests
            
                -> Muitas requisições feitas ao servidor

⠀   **⠀500⠀**

⠀       *⠀500⠀* : Internal Server Error

                -> Não sabe especificar qual erro ocorreu no servidor 

⠀       *⠀503⠀* : Service Unaivaiable

                -> Serviço não está disponível naquele momento
    
    Mais informações, acessar: https://devdocs.io