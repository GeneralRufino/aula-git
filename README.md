
# Desafio 01: 
# 📃–Definir o que é um *Sistema de Controle de Versões (VCS)* (mínimo de 10 linhas).📝
Resposta:
 → O VCS é um ágil sistema de controle de versões é um software utilizado que tem como função principal acompanhar cada uma das alterações feitas/catalogadas em um arquivo ou conjunto de arquivos ao longo do tempo, permitindo assim que o VCS possa rastrear, reverter e comparar as versões anteriores com as versões mais atuais. É usado para gerenciar o código de software, mas pode ser aplicado a qualquer tipo de arquivo.
Também, faz com que conforme o desenvolvedor for editando cada código.
O sistema de controle de versão tira um instantâneo dos arquivos. Em suma, o VCS sempre salva esses "setores" e versões antigas e editadas dos códigos de forma permanente, para que assim ele possa ser recuperado, revisado, documentado em momentos necessários.
—------------------------------------------------------------------------------------------------------------
— Cite 5 vantagens em utilizar um VCS:
Resposta:
→ Primeira Vantagem:
. Comparação entre arquivos e suas versões passadas e atuais. 
→ Segunda Vantagem:
. Compartilhamento/Documentação de arquivos. 
→ Terceira Vantagem:
. Desenvolvimento distribuído entre cada desenvolvedor para com um mesmo projeto/código.
→ Quarta Vantagem:
. Solução de problemas que possam vir a acontecer entre o desenvolvimento do código.
→ Quinta Vantagem:
. Rastreamento de modificações. Já que o VCS pode rastrear facilmente as modificações feitas em todo o projeto/código.
—------------------------------------------------------------------------------------------------------------
— Cite 3 vantagens do VCS:
Resposta:
→ Primeira Vantagem:
. Git
→ Segunda Vantagem:
. SubVersion
→ Terceira Vantagem:
. Mercurial
—------------------------------------------------------------------------------------------------------------
Status de ATV: 100% concluído

---------------------------------------------------------------------------------------------------------------
# ◇Desafio 02:◇
# ◇Defina o que é Programação Orientada a Objetos◇;
Resposta:
--> A programação Orientada a Obejtos (POO) é um fundamental paradigma usado no meio da programação que tem como sua principal função organizar os códigos em torno de objetos, que por sua vez, são representações de conceitos no mundo real ou conceitos mais abstratos. Cada objeto definido e catalogado tem e possui suas próprias caracteristicas/atributos e comportamentos/métodos que irão interagir entre sim em meio ás funções do próprio código para a conclusão de determinadas tarefas. A POO também surgiu como uma eficaz alternativa para as gerais caracteisticas em programação estruturada. Tal intuito de sua criação foi também de aproximar o manuseio das estruturas de um programa/código à uma alusão aos objetos da vida real, por isso vem a definição de "Objeto", que represente algo tangível e manipulável dentro do código. O principal paradigma da POO se baseia principalmente em dois funamentais conceitos chaves; ◇*Classes* e *Obejtos*◇
# *Nota;* Todos os outros de mais conceitos que são igualmente importants, são contruídos e baseados em cima desses dois principais.

## ◇Exemplifique e Explique um cenário de *ABSTRAÇÃO*;◇
### ◇Definição;◇
--> Abstração envolve a indentificação dos aspectos essesnciais de um objeto no código e a ocultação dos detalhes de implementações desnecessárias. Assim, permitindo criar/representar conceitos abstratos de objetos como "Livros" ou "Carros", ou "Clientes", e com isso, definir seus atributos e métodos relevantes, melhorando a modelagem de cada objeto e suas reutilizações no código central. 
### ◇*Cenário de Abstração:*◇
--> *Um exemplo prático de abstração em programação orientada a objetos (POO) é a criação de classes abstratas para representar tipos de objetos com comportamentos comuns, enquanto as classes concretas implementam os detalhes específicos. Considerando um sistema de vendas de livros, uma classe abstrata Livro pode definir métodos como getPreço() e getTitulo(), enquanto classes como LivroFisico e LivroDigital implementam esses métodos de acordo com as suas características particulares.*

## ◇Exemplifique e Explique um cenário de *Encapsulamento*;◇
### ◇Definição;◇
--> O encapsulamento é basicamente a técnica de proteger os dados e as operações de cada objeto catalogado, restrigindo assim o acesso direto aos seus atributos e expondo apenas uma parte de interface controlada. Todos esse segmento serve para garantir a integridade dos dados e facilitar a manutenção do código, tornando cada um deles mais seguros e robustos. 


### ◇*Cenário de Encapsulamento:*◇
--> *Um exemplo de programação orientada a objetos (POO) com encapsulamento é uma classe de ContaBancaria em que os atributos (saldo, número da conta) são privados e só podem ser alterados através de métodos públicos (deposito, saque, etc...). Isso garante a integridade dos dados e protege a implementação interna da classe.*

## ◇Exemplifique e Explique um cenário de *Herança*;◇
### ◇Definição;◇
--> A Herança Permite que uma classe (classe filha) herde os atributos e métodos de outra classe (classe pai). A herança promove a reutilização de código e a organização hierárquica das classes, facilitando a criação de estruturas de software complexas e aprimoradas. 

### ◇*Cenário de Herança:*◇
--> *Um exemplo simples de programação orientada a objetos com herança envolve criar uma classe base (Animal) e subclasses que herdam atributos e métodos da classe base (Cachorro, Gato). A classe base pode definir características genéricas de animais (como nome e tipo), enquanto as subclasses podem adicionar ou modificar características específicas (por exemplo, o som que um cachorro faz)*

## ◇Exemplifique e Explique um cenário de *Polimorfismo*;◇
### ◇Definição;◇
--> Polimorfismo é central a capacidade de objetos de diferentes classes responderem de forma diferente a uma mesma ação, ou seja, a mesma chamada de método pode ter comportamentos diferentes dependendo da classe do objeto que a está invocando. O polimorfismo é fundamental para criar sistemas flexíveis e adaptáveis, permitindo que as classes sejam substituídas sem afetar o funcionamento do código. 

### ◇*Cenário de Polimorfismo:*◇
--> *Polimorfismo significa "muitas formas", é o termo definido em linguagens orientadas a objeto, como por exemplo Java, C# e C++, que permite ao desenvolvedor usar o mesmo elemento de formas diferentes. Polimorfismo denota uma situação na qual um objeto pode se comportar de maneiras diferentes ao receber uma mensagem.*

---------------------------------------------------------------------------------------------------------------
## ◇*Cite 5 Principais Vantagnes da POO;*◇
#### ◇Primeira Vantagem◇
---> Modularidade de Código:
POO organiza os códigos em objetos, que ~sao por sua vez unidades lógicas com dados/atributos e comportamentos/métodos próprios. O que significa uma organização e entendimentos melhorado do código como um todo.

### ◇Segunda Vantagem◇
---> Reutilização de Código:
A herança e o polimorfismo permitem que objetos compartilhem funcionalidades de outros objetos, reduzindo a necessidade de reescrever código e acelerando o desenvolvimento. 

### ◇Terceira Vantagem◇
---> Modelagem Realista:
POO permite que os desenvolvedores modelem objetos e entidades do mundo real em software, facilitando a compreensão e a representação de sistemas complexos. 

### ◇Quarta Vantagem◇
---> Escalabilidade:
 A escalabilidade dos sistemas permite que sistemas os sejam construídos de forma mais modular, tornando-os mais fáceis de expandir e adaptar os mesmos a novas necessidades. 

 ### ◇Quinta Vantagem◇
 ---> Facilidade de Manutenção:
 A modularidade e o encapsulamento dos dados e métodos em objetos facilitam a identificação e correção de problemas, pois as modificações em um objeto não afetam diretamente outros objetos. 
 -------------------------------------------------------------------------------------------------------------
=======
... 
