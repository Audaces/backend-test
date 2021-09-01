# backend-test
Teste para a vaga de Backend Developer na Audaces.

### Sobre o desafio:
Você deverá desenvolver uma API com C#/.net Core e, preferencialmente, GraphQL. 
A API recebe uma lista de números, chamada de Sequence, e um número alvo, chamado de Target.  
Por exemplo: 
```
{
 "Sequence": [5, 20, 2, 1],
 "Target": 47
}
```

A API deverá então checar se é possível atingir o número alvo com uma combinação das pontuações e, se possível, retornar essa combinação.  
No nosso exemplo, a API poderia retornar: 
```
[2, 5, 20, 20]
```
Além disso, chamadas para a API devem ser gravadas.

### Requisitos mínimos: 

* Um endpoint que recebe as pontuações e o número alvo, retornando uma combinação possível;

* Um endpoint que receba duas datas e retorne todos as consultas na API naquele período;
 

### Extras: 
* Readme

* Testes, sejam unitários ou de comportamento; 

* Deploy em algum serviço como Heroku; 

* Qualquer feature que você julgar legal :) 

 

Não se preocupe com uma interface para o usuário, a ideia é consultar a API diretamente pela linha de comando. Sinta-se à vontade para comentar qualquer decisão de projeto tomada durante o desafio. 

Qualquer dúvida, estamos à disposição. Lembre-se que quanto antes o desafio for terminado, mais cedo poderemos continuar com o processo.  
