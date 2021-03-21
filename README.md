# SIGAAM
Sistema de Gestão e Auxílio a Associações de Moradores

## Introdução
Este repositório visa descrever as etapas, funcionamento, desenvolvimento do aplicativo Gerenciador de Bairro: Sistema de Gestão e Auxílio a Associações de Moradores. Tal aplicativo é resultado de um Trabalho de Conclusão de Curso (TCC) dos alunos:
- [Gabriel Campos](https://www.linkedin.com/in/gabriel-campos-ba891a1bb/)
- [Guilherme Augusto](https://www.linkedin.com/in/guilherme-augusto-de-oliveira-92a149144/)
- [Gustavo Ferreira](https://www.linkedin.com/in/gustavo-ferreira-a5b409199/)
- [Jordan Ítalo](https://www.linkedin.com/in/jordan-ítalo-amaral-7498511aa/) 

formandos do Curso de técnico informática, turma 2018. Como Orientador deste trabalho, o Doutor em Ciência da Computação e Diretor do CEFET-MG campus XI, Gustavo Campos Menezes. 
### Sobre o Trabalho propriamente dito

##### Resumo

O projeto consiste em um aplicativo criado para auxiliar a administração dos grupos de associações de bairros do Brasil, forma de organização que tem aumentado consideravelmente. Esse objetivo será cumprido fornecendo funcionalidades para gerir eventos e entender as necessidades dos membros, além de promover maior interação entre as pessoas através de fóruns e outros artifícios, como a presença de uma agenda compartilhada e uma tela de feedback que permite os moradores avaliarem a gestão da associação e enviarem sugestões a diretoria. O aplicativo foi desenvolvido de forma a possibilitar que cada associação crie o seu próprio ambiente na plataforma, evitando que as telas sejam compartilhadas entre mais de uma organização. Em relação ao formato de produção do aplicativo, esse foi feito através da plataforma Android Studio, por conta da facilidade de criar interfaces visuais e pela compatibilidade com a linguagem Java. Na parte de armazenamento foi utilizado o banco de dados não relacional Firebase. Com esse aplicativo almeja-se que haja uma maior interação entre membros e moradores, além de facilitar e organizar o controle acerca de eventos, feedbacks, sugestões dos moradores e a necessidade do bairro em geral.

#### Abstract

The project consists of an app created to help the administration of neighborhood groups all over Brazil, which type of organization is growing very fast. This objective will be reached through features that can manage events and understand the people’s needs, in addition, to promote more interaction between the members of the society through forums and other devices, like a shared agenda and a feedback screen that allow users to rate the director’s activity and send suggestions to the administrators. The application was developed to provide every association with creating their environment in the platform, avoiding sharing the screens between more than one society. The software product was done using the Android Studio integrated development environment because of its advantages concerning the creation of visual interfaces and the possibility of Java programming. It also strongly made use of the Firebase database. With this app, there will be way more interaction between the association members and helping the admins control everything regarding communication through the application.

### Etapas
1. A primeira etapa do desenvolvimento do aplicativo foi a definição do escopo do trabalho. A visão clara do objetivo faz com que o trabalho seja feito de forma organizada e minize os erros, uma vez que cada um dos integrantes sabem o que devem fazer. O fato do aplicativo ter surgido da demanda da associação de moradores do Bairro Cabral, Contagem, MG, fez com que tivéssemos um norte fixo. Embora tenha surgido de uma demanda, possibilitamos que nosso aplicativo seja usado por qualquer grupo de condomínio ou associação de moradores. 
2. A segunda etapa do trabalho foi a seleção das tecnologias a serem usadas para desenvolver o app. Definimos que o aplicativo seria feito através do Android Studio, com a Linguagem Java e também usaríamos o Firebase, por ser um BaaS. O Firebase facilita o desenvolvimento pois podemos focar na parte do aplicativo, não tendo que preocupar com sistema de autenticação, apis de consulta, armazenamento de dados. A escolha do Android Studio, juntamente com o java foi devido as matérias que possuímos: Tecnologias Emergentes, que nos dá uma base sobre o Android Studio e Linguagens e Técnicas de Programação II, que nos dá técnicas avançadas de programação em Java.
3. Como etapa final, temos o desenvolvimento em si, focado na implementação das tecnologias.

### Desenvolvimento
Para explicar o funcionamento do nosso aplicativo, o mais favorável é o diagrama de casos de uso:

#### Casos de Uso
Nosso aplicativo possui 2 atores, sendo eles: o administrador, responsável pela gerência e administração da associação de moradores e o membro/morador. Embora todo administrador seja um membro, no começo eles passam por um tipo de processo diferente para criar seu cadastrado em nosso aplicativo. Para que se cadastre um novo administrador, é necessário que crie-se, juntamente, uma associação. Então o administrador de uma associação é responsável pela criação da mesma em nosso aplicativo, como demonstra o diagrama abaixo:

![Diagrama de Casos de uso do cadastro de um administrador e de um membro da associação de moradores](https://github.com/JordanAmaralVicente/SIGAAM/blob/main/docs/Casos%20de%20Uso%20_%20cadastro.png "Casos de Uso do Cadastro")

O diagrama abaixo, demonstra quais funcionalidade do aplicativo um membro da associação, ou também um administrador, pode realizar:

![Diagrama de Casos de uso do funcionamento geral do aplicativo](https://github.com/JordanAmaralVicente/SIGAAM/blob/main/docs/Casos%20de%20Uso%20_%20geral.png "Casos de Uso do Geral")

Por fim, há funcionalidades que somente o administrador pode acessar, sendo essas funcionalidades muito importantes para a gestão do bairro. 

![Diagrama de Casos de uso das funcionalidades disponíveis ao administrador da associação](https://github.com/JordanAmaralVicente/SIGAAM/blob/main/docs/Casos%20de%20Uso%20_%20admin.png "Casos de Uso do Administrador")

Além desses, há também o [diagrama de classes](https://github.com/JordanAmaralVicente/SIGAAM/blob/main/docs/Diagrama%20de%20classes.pdf)

### Resultado

Como resultado, temos o aplicativo finalizado, 100% funcional. 
As imagens das telas podem ser encontradas nesta [pasta de imagens](https://github.com/JordanAmaralVicente/SIGAAM/tree/main/docs/images)
Em breve, o aplicativo também será publicado na [Play Store](#)


### Conclusão

O aplicativo consegue de forma satisfatória atingir os objetivos propostos no início deste documento. Com as funcionalidades implementadas, acredita-se que a forma com a qual as Associações Moradores interagem com seus moradores e dos próprios moradores entre si vão ser mais eficientes e versáteis.

Observa-se que aplicação se trata de uma ferramenta que auxilia o planejamento urbano,  uma vez que o usuário é constantemente atualizado a respeito dos eventos e acontecimentos relacionados ao seu bairro. Através da interface, é esperado que os usuário tenha mais conforto e uma certa melhora na qualidade de vida.

Seria apetecido que o aplicativo fosse utilizado por alguma Associação de Bairro, de preferência a Associação de Bairros do Cabral, a qual demandou tal projeto, para que de fato fosse posto em prática seu funcionamento e fosse retornado um feedback de sua utilização, para futuros aperfeiçoamentos.

[Relatório Técnico](https://docs.google.com/document/d/1bGxnpIKmH_V6yP-qoges0P-GuA9-rtxe7gBQzxuvuso/edit?usp=sharing)

última data de alteração: 21/03/2021
