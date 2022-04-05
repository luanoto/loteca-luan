# Projeto Loteca
Este é um projeto de simulador de loteria, onde o usuário digita 6 números e realiza um sorteio de outros 6 números, no final é verificado quantos números ele acertou

## Tecnologias Utilizadas
- **HTML**: Estrutura do site
- _CSS_: Estilização do site
- _*JS*_: Funções do site
- ~~BootStrap~~: Não foi utilizado

### Melhorias Possíveis
1. [X] Subir para GitHubPages
2. [ ] Alterar os Alerts
3. [ ] Utilizar o Bootstrap
4. [ ] Deixar Responsivo  

### Disponibilizado em 
[GitHubPage](https://luanoto.github.io/loteca-luan/)

### Prints da Tela

| ID | Primeira tela | Segunda tela      |
|----|---------------|-------------------|
| 1  | Loteca Limpa  | Loteca Preenchida |
| 2  | ![tela loteca não preenchida](https://user-images.githubusercontent.com/79379492/161781594-31950f59-93f2-440d-9f1b-c9a10cd6a888.png)  | ![tela loteca preenchida](https://user-images.githubusercontent.com/79379492/161782397-3b658546-c376-4f1a-8573-57c69a06330e.png) |

#### Função Principal 
```js:
function sorteio() {
  var cont = 0;
  numSort = [];

  while (cont < 6) {
    let num = Math.random() * 60;
    num = Math.ceil(num);
    if (!numSort.includes(num)) {
      numSort[cont] = num;
      console.log(numSort);
      cont++;
    }
  }
```

#### comando git
Para iniciar o projeto
```bash:
git init
```
