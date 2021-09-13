## DELETE

    -> Serve para remover um recurso

    Status code: 

        202 ->  Accepted (mas ainda não processado)
        204 ->  No content (Não tem conteúdo de resposta de corpo)
        200 ->  Ok, foi deletado (com um corpo de resposta)

⠀   **⠀CARACTERÍSTICAS⠀**

        * Seguro                    = Não   
        * Idempotente               = Sim
        * Cacheable                 = Não   
        * Uso em formulários HTML   = Não

        -------------------------------
⠀        ⠀       **⠀ BODY ⠀**
        -------------------------------

⠀       ->  *⠀REQUEST⠀*     =    Pode (Não é obrigatório)
⠀       
        ->  *⠀RESPONSE⠀*    =    Pode (Não é obrigatório)
        
        curl -X DELETE http://localhost:3000/posts/2