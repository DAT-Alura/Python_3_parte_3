## Aula 1

1 - Com base no vídeo, selecione a alternativa que expressa a ideia central do paradigma da Orientação a Objetos.

- Getters e setters devem ser usados em suas classes.
- Todo código deve estar dentro de uma classe.
- __Dado e funcionalidade (comportamentos) andam juntos.__
> Correto! No exemplo do vídeo, se Conta e, por exemplo, o método deposita estivessem juntos, ai sim teríamos aplicado OO.

2 - De acordo com as situações citadas no vídeo, escolha a única alternativa que não é sinal de programação procedural.

- Copy & Paste e Ctrl + F como prática regular do desenvolvedor para propagar mudanças no projeto.
- Códigos confusos e duplicados.
- __Comportamento e dados caminhando juntos, o que auxilia na manutenção e legibilidade do código.__
> Correto! Para que várias equipes consigam trabalhar em um mesmo projeto, é necessário que as responsabilidades de cada código estejam bem definidas e claras, evitando conflitos na hora de realizar mudanças e evoluções. Código com responsabilidades coesas é sinal do paradigma OO.

3 - Paulo é novo na equipe da empresa ByteBank. Ficou responsável por uma tela de cadastro, onde existe um campo que deve ser validado conforme a regra de negócio XYZ. Ele pergunta ao seu gerente onde pode obter informações sobre a tal regra. Marque as alternativas que podem ser identificadas como respostas de quem usa o paradigma procedural em seus projetos.

- __Paulo deve entrar em contato com alguém da equipe de analistas de negócio da empresa, para ele entender a regra e implementá-la.__
> Correto! Essa resposta indica que Paulo deve implementar novamente a regra, gerando mais um local caso a regra precise ser alterada. Tipicamente procedural.
- __Dependendo do módulo, Paulo deve perguntar ao responsável técnico do mesmo.__
> Correto! Essa resposta denota que a regra está implementada em vários lugares. Quem é o responsável por ela? Como diz o ditado popular "Cachorro que tem muitos donos acaba morrendo de fome". Tipicamente procedural.
- Basta que Paulo consuma uma classe que representa a informação a ser cadastrada pelo campo.
- __"Copie o código de validação que está no formulário ABCD."__
> Correto! Resposta típica de quem usa o paradigma procedural para não arriscar inserir erros em códigos que já estão funcionando ou em produção.