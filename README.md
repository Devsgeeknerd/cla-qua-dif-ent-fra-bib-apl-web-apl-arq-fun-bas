<!-- Título -->
# Qual a Diferença Entre Framework e Biblioteca?

***Conteúdo da Aula:***

Vamos entender melhor as características de cada um para finalmente entender do que se tratam.

## O que são Bibliotecas?

![Biblioteca](https://dkrn4sk0rn31v.cloudfront.net/uploads/2020/06/biblioteca-estantes.jpg "Biblioteca")

Vamos imaginar que precisamos calcular quantos dias existem entre duas datas utilizando ***JavaScript***.

Mas no momento não há uma funcionalidade da linguagem que faça este cálculo para nós.

Então teremos que criar uma função em que a gente passe duas datas e ela nos retornará a quantidade de dias.

E depois pode aparecer a necessidade de pegar uma data e adicionar um certo número de dias.

Que data teremos como resultado?

E se precisarmos adicionar horas ou minutos?

A princípio podem parecer funções sem conexão, mas note que estamos falando de cálculos que nos remetem a tempo.

Com o intuito de deixar o código mais organizado, podemos juntar estas funções em uma **“coleção”** de funções relacionadas ao cálculo de tempo.

Em conclusão, podemos dizer que uma **biblioteca** (do inglês ***library***, não confundir com **livraria** que em inglês é ***book store***) é uma coleção de códigos voltados a resolver um determinado tipo de problema.

### Exemplos de Bibliotecas JavaScript

* ***Moment.js***:
  * Biblioteca para converter, validar, manipular e exibir datas e horários.
* ***Chart.js***:
  * Biblioteca para a criação de gráficos.
* ***Voca***:
  * Biblioteca para trabalhar com *Strings*.
* ***mo.js***:
  * Biblioteca para criar animações incríveis com SVG.
* ***React***:
  * Biblioteca para criar interfaces de usuário.

## O que são Frameworks?

Um ***framework*** possui várias funcionalidades prontas, e normalmente já possuem um fluxo de trabalho ou estrutura a serem seguidos.

É algo bem mais abstrato do que uma biblioteca.

Isso realmente confunde muitas pessoas.

Por exemplo, o ***jQuery*** se autodenominava um *framework*, mas já faz um bom tempo que ele se chama de biblioteca.

O foco dos *frameworks* é mais amplo que das bibliotecas.

Aliás, um *framework* pode ser feito a partir de uma coleção de padrões, APIs e até mesmo de bibliotecas.

Só para exemplificar, o ***Angular***, ***framework*** ***JavaScript*** para desenvolvimento de aplicações, é feito a partir de bibliotecas de animação, requisições **http**, internacionalização, testes, tratamento de dados em formulários, reatividade, roteamento, etc.

### Exemplos de Frameworks JavaScript

* ***Angular***:
  * Framework para criação de aplicações *web*.
* ***Vue.js***:
  * Framework também para criação de aplicações *web*.
* ***Ionic***:
  * Framework para criar aplicativos *mobile* com *Angular*, *React* ou *Vue*.
* ***Express***:
  * *Framework* para criar aplicações com *Node.js*.
* ***LoopBack***:
  * *Framework* para criar *APIs* e microsserviços com *Node.js*.

## Mas então, qual a diferença entre Framework e Biblioteca?

Por mais que a gente tenha visto características de *framework* e biblioteca, ainda assim há confusão, pois nem sempre as funções do ***software*** deixa claro a sua natureza.

É provável até que não seja nenhum dos dois.

Bem como também é comum ver lugares chamando ***Angular*** de biblioteca e ***React*** de *framework*, sendo que na verdade é ao contrário.

Antes de tudo, algo que podemos notar além das diferenças já mostradas aqui é que normalmente as bibliotecas são usadas pelos nossos códigos, enquanto os *frameworks* é quem costumam utilizar os nossos códigos.

Por isso podemos diferenciar *React* de *Angular*.

Se acaso você já usou os dois verá as seguintes diferenças:

* No *React* nós temos basicamente funções para a criação de componentes e criação de estados.

Estamos no controle o tempo todo, nós chamamos as funções do *React*, podemos decidir qual será a estrutura da nossa aplicação e o fluxo com o qual ela funciona.

Se acaso a gente precisar de funcionalidades de roteamento, animações, internacionalização, etc, precisaremos buscar bibliotecas para isso.

```javascript
function App(props) {
    return (
      <div>
        Olá, {this.props.name}!
      </div>
    );
}

ReactDOM.render(
  <App name="Taylor" />,
  document.getElementById('hello-example')
);
```

Em contrapartida no *Angular* todas essas funcionalidades já vêm inclusas.

Há uma estrutura que devemos seguir (componentes, serviços, pipes, rotas, módulos), e o *Angular* é quem vai chamar o nosso código seguindo seu próprio fluxo.

Essa característica de já ter uma estrutura é o principal diferencial entre um *framework* e uma biblioteca.

Você pode notar que em nenhum momento nós chamamos alguma função como `Angular.nomeFuncao()`.

Eventualmente, caso queira fazer algo num fluxo ou estrutura diferente, o *Angular* não vai entender e você terá um erro.

```javascript
@Component({
  selector:    'app-hero-list',
  templateUrl: './hero-list.component.html',
  providers:  [ HeroService ]
})
export class HeroListComponent implements OnInit {

}
```

Veja como já temos uma estrutura a seguir.

É como se no *framework* nós precisássemos preencher os campos que ele pede, é ele quem está no controle de tudo.

### Qual o melhor? Framework ou Biblioteca?

Podemos concluir que enquanto na biblioteca nós mesmos criamos a base e o fluxo, no *framework* já temos toda a estrutura pronta para utilizarmos e seguirmos.

Mas isso não significa necessariamente que um é melhor do que o outro.

São ferramentas diferentes para propósitos diferentes.

Ao passo que no *Angular* nós já temos toda a estrutura pronta, nos poupando desse trabalho, teremos menos liberdade para certas escolhas.

Em contrapartida, no *React* temos que definir coisas comuns como arquitetura e fluxo, mas teremos mais liberdade de escolher cada biblioteca responsável por cada funcionalidade em nossa aplicação.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-qua-dif-ent-fra-bib-apl-web-apl-arq-fun-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-qua-dif-ent-fra-bib-apl-web-apl-arq-fun-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-qua-dif-ent-fra-bib-apl-web-apl-arq-fun-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-qua-dif-ent-fra-bib-apl-web-apl-arq-fun-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-qua-dif-ent-fra-bib-apl-web-apl-arq-fun-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-qua-dif-ent-fra-bib-apl-web-apl-arq-fun-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
