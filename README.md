
§ Segurança Via Reconhecimento Facial
explicação sobre o código

§ Cliente
   O que funciona:
    * captura de faces 
    * banco de dados 
    * histórico de resultados  
    * resultado planificado
    
  Servidores testados: DeepFace, PyCharm 
  
  Ainda não implementado: 
    * adição de novos usuários automáticamente
    * dados por medição gemétrica facial
§ Servidor 
   O que funciona:
    * histórico para alterações de dados 
    * manipulação dos códigos 
    * leitura da dados/resultados 

§ Execução do Servidor 
   Configurar o espaço de endereço padrão é uma das partes principais do funcionamento do código, feito via Python, utilizando também o DeepFace para a captura das
  imagens. A montagem dos códigos feito ordenadamente pela prioridade da função, para que quando fosse utilizado, o servidor executar de forma prioritária a necessidade 
  de busca e decodificação das informações.
   
§ Desenvolvimento
   A biblioteca com os dados dos usuários adicionados pela DeepFace foi adicionado junto aos códigos feitos em Python, com o scripting feito, o resultado mostrado
  ainda em códigos será transferido e traduzido para uma lista em Exel, mostrando assim um resultado compreensível e direto dos usuários, podendo ser visualizado e
  configurado caso haja a necessidade de alguma alteração.
    Todo código foi construído por partes
     * Programação do DeepFace para a captura da face atraves de uma camera
     * A confirmação de que aquela foto inserida está dentro do banco de dados
     * A detecção da interface do indivíduo
     * A busca no banco de dados para a verificação da existência dos dados coletados
     * Se confirmada a veracidade do usuário, partindo da detectação da informação no banco de dados, ela é enviada para uma planilha
     * Dentro dessa planilha ela será organizada por nome e matrícula, com sua diferença entre as aulas 
  
     
