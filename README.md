# What-Is-A-Black-Box?
What Is A Black Box? <br>
O que é uma caixa preta?


## Black Box
![black](https://github.com/eoqthiago/What-Is-A-Black-Box-/assets/90149848/a3f5bf26-eb5b-45fb-9ccc-517f49aeac54)
<br><br><br><br>
<p> "À medida que você começa a trabalhar com classes e objetos, você pode se deparar com o termo programação de caixa preta. Muitas vezes, os programadores escrevem métodos como se fossem caixas pretas — o programador sabe o que está acontecendo dentro da caixa, mas todos esses detalhes de implementação são escondidos do usuário.
O usuário deve estar ciente da entrada da caixa preta, e eles devem ser capazes de prever uma saída dada a entrada, mas os detalhes de como essa entrada é transformada na saída podem ser escondidos dos usuários." </p>
<br>

"Black box" é um termo que se refere a uma abordagem em que o usuário não precisa conhecer os detalhes internos de como um sistema ou componente funciona para utilizá-lo. Em outras palavras, a implementação é ocultada, e o usuário apenas interage com a entrada e a saída do sistema.

Por exemplo, uma biblioteca de funções pode ser considerada uma black-box, em que o usuário apenas utiliza as funções para realizar determinadas tarefas, sem precisar saber como as funções foram implementadas internamente. Isso permite que os usuários se concentrem em suas próprias tarefas, em vez de se preocuparem com a implementação de detalhes de baixo nível. <br>
<br><br><br><br>
"Black box" é um conceito em programação que se tornou popularizado por Gerald Weinberg e Edward A. V. Abelson em seu livro "The Psychology of Computer Programming".
<br><br><br><br>

![CO QUE É BLACK-BOX](https://github.com/eoqthiago/What-Is-A-Black-Box-/assets/90149848/b635cf59-d996-42fc-b076-9f8b96a5026f)


<br><br>

### Exemplo de Uso

```
# Exemplo de utilização de uma black-box em Python

# Importando uma biblioteca como uma black-box
from minha_biblioteca import funcao_a, funcao_b

# Utilizando as funções sem conhecer a implementação interna
resultado_a = funcao_a(parametro1)
resultado_b = funcao_b(parametro2)

# Concentrando-se apenas nos resultados, sem se preocupar com os detalhes de implementação

```

```
# Exemplo de utilização de uma black-box em java

public class BlackBox {
    public int add(int a, int b) {
        return a + b;
    }
}

# Neste exemplo, a classe BlackBox contém um método add que recebe dois números inteiros
 como entrada e retorna sua soma. O método add é um exemplo de programação de caixa preta
 porque oculta os detalhes internos da implementação da soma. O usuário só precisa saber que o método add()
 recebe dois números inteiros e retorna sua soma, sem se preocupar com os detalhes de como a soma é realizada.

```
<br>

## Contribuição
Se você deseja contribuir para a compreensão e aplicação do conceito de "black box", sinta-se à vontade para enviar pull requests. Aceitamos contribuições em forma de exemplos de uso, aprimoramentos na documentação ou qualquer outra forma que possa enriquecer o entendimento deste conceito na comunidade de desenvolvimento.

## Referências
Weinberg, Gerald M., and Abelson, Edward A. V. "The Psychology of Computer Programming." (1971). <br>
[What Is A Black Box](https://www.codecademy.com/article/black-box-programming).
