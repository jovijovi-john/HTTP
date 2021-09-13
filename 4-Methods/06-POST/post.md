## POST

    -> Serve para publicar / cadastrar um recurso

⠀   **⠀CARACTERÍSTICAS⠀**

        * Seguro                    = Não
        * Idempotente               = Não
        * Cacheable                 = Sim   
        * Uso em formulários HTML   = Sim

        -------------------------------
⠀        ⠀       **⠀ BODY ⠀**
        -------------------------------

⠀       ->  *⠀REQUEST⠀*     =    SIM

                Pois no pedido quando eu for cadastrar alguma coisa eu preciso enviar essas informações
⠀       
        ->  *⠀RESPONSE⠀*    =    SIM 

                pode receber um body mas tambem pode receber apenas um status code

        curl -d '{"id": 2, "title": "json-server-2", "author": "john"}' -H "Content-type: application/json" -X POST http://localhost:3000/posts 

        -d é de data, vai servir para enviar o body da requisição
        -H para configurar os HEADERS nesse caso um header somente, avisando que o que eu estou enviando como dado é um JSON
        -X especifica o método que vai ser utilizado que no caso será POST
