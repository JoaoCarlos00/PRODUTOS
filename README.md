# ETAPA 1 AC1

Nesta etapa 1 irei apresentar a criação de um produto e seus atributos e a criação de classe pesssoas com um desafio

## 🚀 Enunciados
Crie uma classe que representa um produto. A classe deve ter os atributos, nome, marca, preço de custo e preço de venda. Deve ter também um método que calcula e retorna o lucro.
Crie objetos dessa classe e escreva na tela seus atributos e o valor do lucro.
Crie uma classe para representar pessoas. O construtor da classe deve receber como parâmetros o nome completo, altura e a data de nascimento. Os objetos, logo após criados, devem criar automaticamente um email no formato nome.sobrenome@dominio.
Desafio: A data de nascimento não pode ser posterior à data atual.


### 📋 Códigos
public class ProdutoTênis { //nesta primeira etapa eu criei a classe e determinei seus atributos sendo usado String para aquilo que for nome e double para número
	  String nome;
	  String marca;
	  String item;
	  double venda;
	  double custo;
	  double lucro
	      ProdutoTênis(String nome, String item, String marca, double venda, double custo) {       //Nesta segunda etapa eu usei o metodo constructor para inicializar o objeto no qual acabei de criar, iniciando atributos e alocando recursos
	          this.nome = nome;
	          this.item = item;
	          this.marca = marca;
	          this.venda = venda;
	          this.custo = custo;
	          this.lucro = venda - custo;

	      }
	      String descricao()  { //Na terceira etapa eu criei o retorno que vai ser o visual do código quando ele for gerado pelo aplicativo 
	          return
	              "Nome: " + this.nome + "\n" +
	              "Item: " + this.item + "\n" +
	              "Marca: " + this.marca + "\n" +
	              "Venda: " + this.venda + "\n" +
	              "Custo: " + this.custo + "\n" +
	              "Lucro: " + this.lucro + "\n" ;


	       }
	       public static void main (String[]args) {  //Por último criei os 3 produtos e pedi para o aplicativo printar para rodar
	           ProdutoTênis t1 = new ProdutoTênis( "Jcz", "Tênis", "Puma", 800, 800);
	           ProdutoTênis t2 = new ProdutoTênis( "Jcz.01", "Tênis", "Puma", 900, 800);
	           ProdutoTênis t3 = new ProdutoTênis( "Jcz.02", "Tênis", "Puma", 1000, 800);
	           System.out.println(t1.descricao());
	           System.out.println(t2.descricao());
	           System.out.println(t3.descricao());
	}
	} 
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

public class Pessoas { //Criei um classe de pessoas e adicionei os atributos
	
	    String nome;
	    String sobrenome;
	    String altura;
	    String datadenascimento;
	    String email;
	        Pessoas (String nome, String sobrenome, double altura, String datadenascimento) { //Semelhante ao código anterior usei o metodo constructor e inicializei o objeto recem criado
	          this.nome = nome + " " + sobrenome;
	          this.sobrenome = sobrenome;
	          this.altura = altura + " " + "m";
	          this.datadenascimento = datadenascimento;
	          this.email = nome + "." + sobrenome + "@" + "facens";


	    }
	    String descricao() {  //Usei o retorno para moldar o visual do codigo quando rodar
	      return 
	          "Nome: " + this.nome + "\n" + 
	          "Altura: " + this.altura + "\n" + 
	          "Data de Nascimento: " + this.datadenascimento + "\n" +
	          "Email emitido: " + this.email + "\n" ;

	  }
	    public static void main(String[]args){  //Especifiquei o que era para mostrar ao gerar o código

	    	  Pessoas p1 = new Pessoas("Miguel", "Palhares", 1.67, "21/03/2004");
	    	  Pessoas p2 = new Pessoas("Aiury", "Nunes", 1.70, "04/01/2004");
	    	  System.out.println(p1.descricao());
	    	  System.out.println(p2.descricao());
	    	  }
	    	  }
	//NOTA: não consegui fazer o desafio e ao pesquisar no chatgpt não compreendi o código portanto não achei válido somente copiar para ganhar nota
## 🛠️ Construído com

Ferramentas utilizadas e bibliotecas

* IDE Eclipse

## 📌 Versão

* **Versão 1.0** caso seja atualizado manter a descrição inicial e inserir uma nova linha com descrição da atualização.
* **Versão 1.1** - *Refatoração* *data 09/09/24*

## ✒️ Autores
João Carlos Ferreira de Araujo RA 248152 - AC1 de Programação Orientada à Objetos


