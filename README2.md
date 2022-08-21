# Explorando padrões de projeto na prática com Java



### Padrões de projeto

São soluções consolidadas para problemas recorrentes no desenvolvimento e manutenção de software orientado a objetos.

O livro Design Patterns: Elements of Reusable Object-Oriented Software(1995) é a principal referência sobre o temas, a qual tornou dos autores Gamma, Helm, Johnson e Vlissides conhecidos como "Gang of Four" (GoF).

São comumente classificados nas seguintes categorias:

- ***Padrões Criacionais:*** Abstract Factory, Builder, Factory Method, Prototype, ***Singleton***.
- ***Padrões Comportamentais:*** Chain of Responsibility, Interator, Observer, ***Strategy***, Template Method.
- ***Padrões Estruturais:*** Adapter, Bridge, Composite, Decorador, ***Facade***, Flyweight, Proxy.

### Praticando com Java puro

- **Padrão Criacional** - ***Singleton*** - Permite a criação de uma única instância de uma classe e fornecer um modo para. Recupera-la.
- **Padrão Criacional** - ***Strategy*** - Simplificar. a variação de algoritmos para a resoluçãoo de um mesmo problema.
- **Padrão Criacional** - ***Facade*** - Prover uma interface que reduza a complexidade nas interações com subsistemas.

### Praticando com Spring

- ***singleton*** - @Bean e @Autowired;
- ***Strategy*** - @Service e @Repository;
- ***Facade*** - Construiremos uma API REST com o mesmo objetivo desse padrão, abstrair a complexidade das seguintes interações: ***Spring Data JPA e ViaCEP(Feign).***

### Desafio de Projeto

