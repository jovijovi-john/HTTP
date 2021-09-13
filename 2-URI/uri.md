## URI (Uniform Resource Identifier)    ->   Identificador de recurso de maneira única

⠀   *Vai identificar pelo nome e/ou pela localização*

⠀   **Exemplo:**

        Voce é um recurso

                -nome
                -localização

## Resource(Recurso)

    ## Alvo do pedido http

⠀   *Pode ser qualquer coisa identificável / identidade*

⠀       -> **Digital**
                ex: Email (acessado pelo protocolo mailto: email@dominio.com)

⠀       -> **Abstrata**
                ex: Seção e autenticação

⠀       -> **Física**
                ex: Produtos e usuários

    ! Se pudermos identificar, nomear, endereçar ou manipular, estamos falando de um recurso 

## Locator(localizador)   -> URL

    podemos procurar pelo localizador ou pelo nome

    pelo locator, nós usamos a :

⠀       **URL(Uniform Resource Locator)**

            ->  Tipo de localizador só pelo endereço

⠀           *Componentes*

                Obrigatórios(2):

                    -Protocolo(FTP, HTTP, MAILTO):
                                https://
                    -Dominio(somente uma parte da url):     
                            ex: google.com.br
                            o domínio pode ser escrito como um nome, ou como um ip
                
                Opcionais(5):

                    -Subdomínio(opcional as vezes):
                        Vem antes do dominio (ex: www)

                    -Path(caminho):
                        ex: /blog 

                    -Parâmetros: (?key=value);
                    
⠀                   Porta:
                        http://127.0.0.1:**3333**
                        127.0.0.1 é um dominio da maneira ip
                        3333 é a porta
                        A porta é algum lugar do servidor disponivel para eu chegar lá

                        quando nao especifico a porta no:
                            HTTPS:
                                a porta padrão é 443
                            HTTP:
                                a porta padrão é 80
                    
                    -Âncora:

                        local dentro do html
                        ex: 
⠀                           http://127.0.0.1:3333/index.html#**algumLugarDoHtml**

## Name    ->     URN

⠀    **URN(Uniform Resource Name)**

        geralmente a urn vai começar com urn:
        ex:
            urn:isbn:045192192
            urn:oasis:names:specification:docbook:dtd:xml:4.1.2
