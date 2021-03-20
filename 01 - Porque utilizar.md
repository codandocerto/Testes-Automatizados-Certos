## Porque utilizar  
- Imagine um cenário em que você necessita fazer uma alteração na parte principal do sistema, ou seja, no core domain de sua aplicação. Nesse lugar são encontradas as principais regras de negócio do seu sistema, regras que o cliente utiliza todos os dias, nos mais diferentes cenários... como você pode garantir que todos os cenários ainda estão funcionando?  
- Talvez a resposta do item acima seria: "Peço para um outro desenvolvedor testar". Claro, seria uma saída! Mas qual seria o custo disso?  
- Se o outro desenvolvedor não lembrou de testar um cenário e justamente esse estava com problema?  
- Quanto tempo levaria para você saber que o problema ocorreu?  
  
Complicado responder essas perguntas sem pensar em testes, não é?  
##  como ficaria com testes?  
  
- O core domain ou core  business é a parte principal de seu sistema, ou seja, se vamos criar testes, esse local seria onde a maioria deles estariam concentrados! Portanto, deveria estar com **todos os cenários de negócio** cobertos, caso fosse adicionado qualquer alteração que "quebrasse" um desses cenários você seria alertado imediatamente! Obviamente você criaria um teste para a sua alteração, garantindo que o próximo desenvolvedor não terá problemas nessa parte do código.  
- Pedir para um outro desenvolvedor testar é uma prática comum na maioria dos sistemas hoje em dia, poucos são os que possuem maturidade suficiente para não necessitar disso. Porém, dando a manutenção correta nos testes e garantindo que todos estão "passando", caso sua alteração "quebre" o código, você terá um feedback mais rápido, sem a necessidade de parar outro desenvolvedor para testar sua aplicação, descobrir o problema, devolver para você corrigir e ter que testar tudo de novo. Se mesmo assim, após todos os testes automatizados que foram feitos, o desenvolvedor ao testar manualmente sua aplicação ainda encontrar um erro, você pode criar um teste automatizado para o cenário efetuado por ele, garantindo que não haverá mais esse problema no futuro.  
- Não vai ser fácil fazer o computador esquecer um cenário depois que você ensinou ele, se tiver um problema ali, ele vai te avisar em segundos!  
- Como respondido no item acima, o tempo para você encontrar um erro é questão de segundos quando utilizamos testes  
- Um outro grande benefício que vejo nos testes é garantir que o desenvolvedor entendeu a regra de negócio, podendo até mesmo validar com o Product  Owner o fluxo de negócio dentro do teste (quando utilizado a linguagem ubíqua).  
  
 Outro ponto importante mencionar, é que quando entramos em uma empresa, devemos lembrar que todo o tempo gasto de um colaborador tem um custo que é pago pela empresa através do salário, portanto devemos sempre utilizar o tempo dos colaboradores da melhor maneira possível. Se você pode criar um teste automatizado para evitar que outro desenvolvedor gaste tempo efetuando o cenário manualmente, você está trazendo **redução de custos** para a empresa e será **valorizado** por isso!  

  
Não conheço hoje um motivo plausível para não utilizar testes, mas conheço milhares de situações que eles trazem benefícios e muitas em que são necessários!  
  
Espero que essas informações tenham ajudado a dar bons motivos para você utilizar testes!  

## Colabore
Faltou algo? Não tenha medo, colabore!
