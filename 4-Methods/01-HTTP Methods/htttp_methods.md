## HTTP Methods

    ->  Define um conjunto de métodos HTTP
    ->  Indica a ação que o cliente deseja operar
    ->  Podem ser chamados de verbos HTTP
    ->  Cada um possui a sua semântica
    
⠀   **⠀Características⠀**

⠀       -> *⠀Seguro⠀*

            * Não altera o estado do servidor
            * Somente leitura
            * Cliente não aceita alterações
            * Não há carga extra para o servidor
            * O servidor é responsável em manter o método seguro
  
⠀           # Quais são?
                -> Get
                -> Head
                -> Options

⠀       -> *⠀Idempotente⠀*

            Idem == Igual

            * Ao executar o método, a resposta sempre deverá ser a mesma
  
            # Quais são?
                -> Todos os seguros (Get, Head, Options)
                -> Put
                -> Delete
                
                Obs: Put e Delete não são seguros
            
            * Status code pode ser diferente
            * O servidor tem a responsabilidade de retornar dados da mesma maneira (não é o método)
            * Essa especificação não é garantia de que todos os servidores irão aplicar o conceito corretamente 
              (mas deveria)