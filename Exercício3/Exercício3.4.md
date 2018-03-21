# Frameworks

## Arquitetura baseada em componentes

### COM
Em essência, o COM é uma forma neutra, independente de linguagem, de se implementar objetos que podem ser utilizados em diferentes ambientes e através de fronteiras entre máquinas (servidores).
A aplicação mais popular de objetos COM é o de objetos de negócios em aplicações distribuídas.
Componentes COM permitem o uso/reuso de objetos sem o conhecimento prévio de sua implementação (normalmente conhecida em tempo de execução apenas).

### EJB
EJB é um dos principais componentes da plataforma Java Enterprise Edition (Java EE) para desenvolvimento de sistemas corporativos. Com ele é possível criar aplicações modulares, separar suas funcionalidades e as reutilizar de forma simples e objetiva. Ao utilizar EJB é possível construir aplicações distribuídas, totalmente seguras e com um eficaz tratamento de transações. Além disso, o EJB oferece serviços de persistência de dados, controle de concorrência, envio de mensagens, serviço de agendamento, chamadas a métodos remotos e a web services.

### CORBA
Disponibiliza meios de endereçamento transparentes e exatos, tornando o trabalho do programador da aplicação mais simples. Além disso, CORBA utiliza entidades intermediárias para a comunicação dos seus stubs, ao contrário dos métodos tradicionais, que não possuem uma facilidade deste tipo.

## Message Bus

### ESB
Baseado na estrutura da mensagem, um ESB utiliza serviços para comunicar o barramento e os componentes adicionados no barramento. Um ESB irá usualmente provê o serviço de transformação de mensagem de um formato para outro, permitindo que os clientes utilizem mensagens de formatos incompatíveis para se comunicar entre cada um deles.

### ISB
Similiar ao ESB, mas com aplicações em um host na nuvem de uma rede corporativa. O core do conceito ISB é de utilizar URIs e políticas para controle de roteamento da lógica das aplicações e serviços na nuvem.

## Service-Oriented Architecture

### JBoss EAP
O JBoss EAP 7 foi criado para fornecer uma implantação simplificada e o desempenho completo Java™ EE para aplicativos em qualquer ambiente. Seja no local, virtual ou em clouds privadas, públicas ou híbridas, o JBoss EAP apresenta uma arquitetura modular que só inicia os serviços quando necessário. O baixo volume de memória e os tempos de inicialização extremamente rápidos indicam que o JBoss EAP é ideal para ambientes em que a utilização eficiente dos recursos é prioridade, como é o caso do Red Hat OpenShift.

#### Fontes:
http://www.linhadecodigo.com.br/artigo/2864/o-component-object-model.aspx

https://www.devmedia.com.br/enterprise-javabeans/26402

http://www.inf.ufrgs.br/~johann/sisop2/GVGOgrupo2.htm

https://marcobaccaro.wordpress.com/2010/10/19/arquitetura-message-bus/

https://www.redhat.com/pt-br/technologies/jboss-middleware/application-platform
