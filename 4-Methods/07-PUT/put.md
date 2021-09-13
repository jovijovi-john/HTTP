## PUT

    -> Serve para criar um novo ou atualizar um recurso
    -> A diferença dele pro POST é que o POST só serve para criar 
    -> Usa-se MUITO MAIS PARA ATUALIZAR
    -> Se usar para criação o Status code retornado será 201
    -> Se usar para atualização o Status code retornado poderá ser 204 ou 200
    
    204 significa que ta tudo ok mas não tem conteudo de volta
    200 significa que esta tudo ok e tem conteudo de volta

⠀   **⠀CARACTERÍSTICAS⠀**

        * Seguro                    = Não
        * Idempotente               = Sim
        * Cacheable                 = Não   
        * Uso em formulários HTML   = Não

        -------------------------------
⠀        ⠀       **⠀ BODY ⠀**
        -------------------------------

⠀       ->  *⠀REQUEST⠀*     =    SIM

                Pois no pedido quando eu for cadastrar/atualizar alguma coisa eu preciso enviar essas informações
⠀       
        ->  *⠀RESPONSE⠀*    =    NÃO (Recomendado)

        curl -d '{"name": "Victor"}' -H 'Content-type: application/json' -X PUT http://localhost:3000/profile