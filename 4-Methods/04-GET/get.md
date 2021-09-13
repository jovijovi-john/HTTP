## GET

    -> Serve apenas para pegar um recurso
    -> Somente recebe dados

⠀   **⠀CARACTERÍSTICAS⠀**

        * Seguro                    = Sim
        * Idempotente               = Sim
        * Cacheable                 = Sim   
        * Uso em formulários HTML   = Sim

        -------------------------------
⠀        ⠀       **⠀ BODY ⠀**
        -------------------------------

⠀       ->  *⠀REQUEST⠀*     =    NÃO (Recomendado)
               
                Não posso enviar nada no body, entretanto, se enviar sem querer pode ser que algum serviço venha dar problema, então o recomendado é NÃO ENVIAR NADA
⠀       
        ->  *⠀RESPONSE⠀*    =    SIM 

                Eu recebo um body como resposta