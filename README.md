# Design Patterns
## 1. Padrões Criacionais (Criação)
- Factory Method: Encapsula a escolha da classe concreta a ser utilizada na criação de objetos de um determinado tipo.
- Abstract Factory: Encapsula a escolha das classes concretas a serem utilizadas na criação dos objetos de diversas famílias.
- Builder: Separa o processo de construção de um objeto de sua representação, permitindo sua criação passo a passo.
- Prototype: Possibilita a criação de objetos a partir de objetos existentes.
- Singleton: Permite a criação de uma única instância de uma classe e fornece um modo de recuperá-la.
- Multiton: Permite a criação de uma quantidade limitada de instâncias de determinada classe e fornece um modo de recuperá-las.
- Object Pool: Possibilita o reaproveitamento de objetos.
## 2. Padrões Estruturais (Composição e Estrutura)
- Adapter: Permite que um objeto seja substituído por outro que, apesar de realizar a mesma tarefa, possui uma interface diferente.
- Bridge: Separa a abstração de sua implementação, de forma que ambos possam variar independentemente.
- Composite: Agrupa objetos que fazem parte de uma relação parte-todo, tratando-os de forma uniforme.
- Decorator: Adiciona funcionalidade a um objeto dinamicamente.
- Facade: Fornece uma interface simplificada para a utilização de várias interfaces de um subsistema.
- Front Controller: Centraliza todas as requisições a uma aplicação web.
- Flyweight: Compartilha, de forma eficiente, objetos que são usados em grande quantidade.
- Proxy: Controla as chamadas a um objeto através de outro com a mesma interface.
## 3. Padrões Comportamentais (Comunicação entre Objetos)
- Command: Controla as chamadas a um determinado componente, modelando cada requisição como um objeto. Permite que as operações possam ser desfeitas, enfileiradas ou registradas.
- Iterator: Fornece um modo eficiente para percorrer sequencialmente os elementos de uma coleção, sem expor sua estrutura interna.
- Mediator: Reduz a quantidade de dependências entre objetos, introduzindo um mediador através do qual toda a comunicação é realizada.
- State: Altera o comportamento de um objeto de acordo com o estado em que ele se encontra.
- Strategy: Permite a variação dos algoritmos utilizados na resolução de um problema de forma simples.
- Template Method: Define a ordem na qual determinados passos devem ser realizados na resolução de um problema, permitindo que esses passos sejam implementados de maneiras diferentes conforme a situação.
- Visitor: Permite realizar operações específicas em uma coleção de objetos, de acordo com o tipo particular de cada objeto atualizado.
