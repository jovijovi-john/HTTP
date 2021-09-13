## PATCH

    -> Serve para alterar parcialmente um recurso
    -> A diferença dele para o PUT, é que o PUT faz uma alteração completa (muda um recurso inteiro)

⠀   **⠀CARACTERÍSTICAS⠀**

        * Seguro                    = Não
        * Idempotente               = Nem sempre!
        * Cacheable                 = Não   
        * Uso em formulários HTML   = Não

        -------------------------------
⠀        ⠀       **⠀ BODY ⠀**
        -------------------------------

⠀       ->  *⠀REQUEST⠀*     =    SIM

                Pois no pedido quando eu for atualizar alguma coisa eu preciso enviar essas informações
⠀       
        ->  *⠀RESPONSE⠀*    =    SIM 
e

        curl -X OPTIONS http://localhost:3000/posts -i para ver se aceita PATCH
        O PATCH é para alterar apenas algumas coisas, o PUT é quando devemos alterar tudo
        entretanto, nao é uma regra absoluta.