# Loteca
se alterar é gay

Um simulador de loteria, onde o usuario escolhe 6 numeros e o programa
sorteia outros 6 numeros e apos isso verifica a quantidade de acertos.

## Tecnologias Utilizadas
- **HTML: ** Estrutura do site
- **CSS: ** Estilos do site
- **JS** Funções do site
- ~~BootStrap~~: Nao foi utilizado

1. [x] Subir no github pages
2. [ ] Trocar o Alert por mensagens mais amigaveis 
3. [ ] Realizar testes para descobrir bugs 

#### Disponivel em:
[GitHubPages](https://mikaa69.github.io/Loteca/)
### Codigo Principal
```
function verificaAcertos() {
    let cont = 0
    numDig.forEach(function (valor, index) {
        if (numSort.includes(valor)) {
            cont = cont + 1
        }
    })
    document.getElementById("total").innerText = cont
}
```

### Prints da tela do WepApp

|tela inicial|Primeira rodada|
|------------|---------------|
| ![tela inicial do site](/img/print.png) |   ![tela da primeira rodada](/img/print2.png)   |
