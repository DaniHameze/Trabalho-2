<!DOCTYPE html>
<html lang="pt-BR">
    <head>
        <title>Básico Javascript</title>
        
    </head>

    <body>
        <h3>Básico de Javascript</h3>
        <script type="text/javascript">
            var nome;
            var idade;
            var opcao=0;
            var contador=0;
            var repete=1;
            nome=prompt("Informe seu nome: ")
            idade=prompt("Informe sua idade: ")
            //estrutura de decisão "if"
            if (idade>=18)
                {
                    alert(nome+" é maior de idade pois tem "+idade+" anos de idade!")
                }
            if (idade < 18)
                {
                    alert(nome+" é menor de idade pois tem "+idade+" anos de idade!")
                }    
            
              
            opcao=prompt("Informe sua opção (1 para carro - 2 para moto - 3 para Caminhonete): ")
            //estrutura de decisão "switch case"
            switch(opcao)
            {
                    case "1":
                        alert(nome+" você optou pelo carro")
                    break;
                    case "2":
                        alert(nome+" você optou pela moto")
                    break;
                    case "3":
                        alert(nome+" você optou pela caminhonete")
                    break;
                    default:
                        alert(nome+" você não escolheu uma opção válida!")   
                }
             
            //estrutura de repetição "while"
            contador=prompt("Informe o número de repetições para a estutura 'while': ")  
            while(repete <= contador) 
                {
                    alert(nome+" essa é a repetição número "+repete+" da estrutura 'while'")
                    repete = repete+1;
                }
            
            //estrutura de repetição "do while" 
            contador=prompt("Informe o número de repetições para a estrutura 'do while': ")
            repete=1;
            do {
                alert(nome+" essa é a repetição número "+repete+" da estrutura 'do while'")
                repete = repete+1; 
            }
            while(repete<=contador)
            
            //estrutura de repetição "for"
            contador=prompt("Informe o número de repetições para a estrutura 'for'");
            for(repete=1; repete<=contador; repete++)
                {
                    alert(nome+" essa é a repetição número "+repete+" da estrutura 'for'")
                    
                }

            //método "documento.write"
            document.write("Meu nome é ",nome," e tenho ",idade," anos de idade!") 
              
            </script>
        
        <h2>Fim do código</h2>
    </body>

</html>
