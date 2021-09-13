## OPTIONS

    -> Vai ser vir para trazer informações a respeito da disponibilidade (dos métodos) da requisição (seja ela qual for)

    OPTIONS não é um verbo em inglês, é um substantivo

    curl -X é pra especificar o método http
    curl -X   http://localhost:3000/posts -i para mostrar com o header

    Access-Control-Allow-Methods:  vai ser a linha que vai mostrar quais são os métodos permitidos para aquela rota

⠀   **⠀CARACTERÍSTICAS⠀**

⠀       *SEGURO*              =  SIM (Não faz alteração no servidor)
        *IDEMPOTENTE*         =  SIM (Ao executar o método a resposta é sempre a mesma)
        *USO EM FORMULÁRIOS HTML*  =  NÃO
        *CACHEABLE*           =  NÃO (A cache geralmente é para guardar informações sobre alterações no servidor) 
        -------------------------------
         ⠀       **⠀ BODY ⠀**
        -------------------------------

            Não envia e não recebe

            -> Response:    Não
            -> Request:     Não
            
