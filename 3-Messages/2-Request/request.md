## Requests

⠀   **⠀Request Line⠀**

⠀       -> Method
            
            é um verbo http que diz a intenção dos pedidos(pedido simples, cadastrar, deletar, atualizar...);
        
        -> Protocol Version 

        -> URI
        
⠀   *⠀BODY's NEM SEMPRE SÃO ENVIADOS⠀*

⠀   *⠀HEADERS SEMPRE SÃO ENVIADOS⠀*

    ->>> EXEMPLO:

        https://www.google.com
        
        https      -> é o protocolo
        www        -> é o subdomínio
        google.com -> é o domínio
        ainda tem a barra escondida ( quando nao coloca o path o caminho default é a barra)

        no git:     curl -v http://www.google.com
