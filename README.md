# dio-java-poo
Criando um Aplicativo de Controle de Transações Financeiras com POO

#### Esse projeto tem como objetivo de consolidar conceitos fundamentais da programação orientada a objetos (POO), como herança, encapsulamento, polimorfismo, abstração e reuso de código. A aplicação simula um sistema bancário básico que permite a criação de contas, depósitos, saques, transferências via PIX, criação de investimentos e acompanhamento de histórico de transações.

---
#### Paradigma de Programação Orientada a Objetos (POO) com Java.
Podemos afirmar que Java atua como espinha dorsal do POO, não é apenas uma escolha tecnológica popular, mas uma **necessidade estratégica** para o desenvolvimento de sistemas financeiros. Sua capacidade de modelar a complexidade do mundo real de forma organizada, segura e escalável, juntamente com a vasta gama de ferramentas e a maturidade do ecossistema Java, o tornam a solução preferencial para impulsionar a inovação e a eficiência no setor bancário e financeiro global.

O **Paradigma de Programação Orientada a Objetos (POO)** é uma abordagem fundamental na engenharia de software que se baseia na organização do código em "**objetos**" – entidades que combinam dados (atributos) e funcionalidades (métodos) relacionadas. Diferente da programação procedural, que foca em sequências de instruções, a POO busca modelar o mundo real de forma mais intuitiva, representando conceitos como pessoas, produtos ou transações como objetos interconectados.

No coração da POO estão quatro pilares principais:

* **Encapsulamento:** É o princípio de agrupar dados e os métodos que operam sobre esses dados dentro de uma única unidade (a classe), ocultando os detalhes internos da implementação e expondo apenas uma interface controlada para interagir com o objeto. Isso protege a integridade dos dados e facilita a manutenção do código.
* **Herança:** Permite que uma classe (subclasse ou classe filha) herde atributos e métodos de outra classe (superclasse ou classe pai). Isso promove a reutilização de código e estabelece uma hierarquia de classes, representando relações "é um tipo de".
* **Polimorfismo:** Significa "muitas formas". Em POO, refere-se à capacidade de objetos de diferentes classes responderem à mesma mensagem (chamada de método) de maneiras diferentes, dependendo de sua própria implementação. Isso permite que o código seja mais flexível e extensível.
* **Abstração:** Foca em apresentar apenas as informações essenciais para o usuário, escondendo os detalhes complexos da implementação. Ao invés de lidar com todos os detalhes de como algo funciona, você interage com uma representação simplificada e relevante.

---
#### Java como Tecnologia Dominante em POO

**Java** é uma das linguagens de programação mais robustas e amplamente utilizadas no mundo, e sua popularidade se deve, em grande parte, à sua forte adesão e implementação eficiente dos princípios da POO. Criada pela Sun Microsystems (hoje parte da Oracle), Java foi projetada com a filosofia "**Escreva uma vez, execute em qualquer lugar**" (Write Once, Run Anywhere - WORA), graças à sua Máquina Virtual Java (JVM). Isso significa que o código Java compilado pode ser executado em qualquer dispositivo que possua uma JVM, tornando-o extremamente versátil.

Alguns dos motivos que consolidam Java como uma tecnologia de mercado para diversas soluções são:

* **Portabilidade:** A JVM garante que as aplicações Java rodem em diferentes sistemas operacionais sem modificações.
* **Escalabilidade:** Java é capaz de lidar com grandes volumes de dados e processamento, sendo ideal para sistemas de grande porte.
* **Segurança:** Possui um modelo de segurança robusto que, desde o seu design, oferece mecanismos para proteger aplicações contra ameaças.
* **Vasta Comunidade e Ecossistema:** Uma enorme comunidade de desenvolvedores, bibliotecas, frameworks (como Spring e Hibernate) e ferramentas tornam o desenvolvimento em Java mais rápido e eficiente.
* **Orientação a Objetos Nativa:** A linguagem foi construída com a POO em sua essência, tornando a implementação de conceitos orientados a objetos intuitiva e eficaz.

---
#### POO com Java em Sistemas Financeiros

Sistemas financeiros são notoriamente complexos, exigindo alta confiabilidade, segurança e capacidade de processamento de transações em massa. O paradigma POO, com Java como sua principal implementação, oferece uma base sólida para o desenvolvimento desses sistemas por várias razões:

* **Modelagem de Entidades Complexas:** A POO permite modelar entidades financeiras como **contas bancárias**, **clientes**, **transações**, **investimentos** e **produtos financeiros** como objetos distintos. Por exemplo, uma classe `ContaCorrente` pode ter atributos como `saldo`, `numeroDaConta` e `titular`, e métodos como `depositar()`, `sacar()` e `transferir()`.
* **Reusabilidade e Manutenção:** A **herança** é crucial para criar hierarquias de produtos financeiros (e.g., `ContaPoupanca` e `ContaCorrente` herdando de `ContaBancaria`), reutilizando lógica comum e facilitando a adição de novos produtos. O **encapsulamento** garante que os dados sensíveis, como saldos e informações de clientes, sejam acessados e modificados apenas por métodos controlados, aumentando a segurança.
* **Flexibilidade e Extensibilidade (Polimorfismo):** Em um sistema financeiro, diferentes tipos de transações (saque, depósito, transferência) podem ser processados por uma interface comum de `Transacao`, com cada tipo de transação implementando a lógica específica de seu método `executar()`. Isso é um exemplo clássico de **polimorfismo**, que permite adicionar novos tipos de transações sem modificar o código existente que processa transações.
* **Confiabilidade e Auditoria:** A modularidade proporcionada pela POO e a robustez do Java contribuem para a construção de sistemas mais confiáveis, facilitando a identificação e correção de erros. A capacidade de auditar cada transação e o estado de cada objeto financeiro é fundamental para a conformidade regulatória.
* **Integração com Sistemas Legados:** Muitos bancos e instituições financeiras possuem sistemas legados complexos. Java, com sua vasta gama de bibliotecas e frameworks de integração, é altamente eficaz na conexão e interação com esses sistemas, garantindo uma transição e modernização mais suaves.
* **Processamento de Transações de Alto Volume:** A performance e a capacidade de processamento distribuído do Java, aliadas a frameworks como Spring Boot para microsserviços, são ideais para lidar com o enorme volume de transações que ocorrem diariamente no setor financeiro.
