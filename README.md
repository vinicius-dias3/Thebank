# Thebank

Criei o site baseado nos conhecimentos que obtive até aqui, nos estudos.

Após a vizualização da resolução, pude aprender alguns detalhes que deixou o código mais simples e rápido de escrever, como a alteração do "flex-direction:column;" no .header para o responsivo (tablet).
```
@media (max-width: 690px){
    .header {
        flex-direction: column;
    }
```

Já no responsivo (smartphone), também utilizei a mesma técnica, alterando o .menu para "flex-direction:column;"
<img src="./src/images/Screenshot_2.png" alt="indicacao da parte do código"> 



Ficou mais simples que alterar o display.

Ah, considero uma correção também, na forma como inseri a font do "google". Eu costumava usar apenas o formato "@import". Inclusive, inseri no reset.css. Após a correção, importei a fonte através do método "link", inserindo direto no html.