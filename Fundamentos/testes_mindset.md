# Como pensar como um "testador de software"?

# Tester Mindset
Teste não é uma habilidade inata do ser humano, nós não nascemos "testadores". Teste é uma habilidade desafiadora que requer prática e experiência para ser bem realizada.

Listo aqui 5 coisas que distinguem bons "testadores", estas são fáceis de entender, porém difíceis de dominar, mas podem ser aprendidads por qualquer um que se dedicar.

## 1. Pensamento invertido e "Ônus da prova"
Ao testar um software devemos assumir que ele não funciona e que está completamento errado. Com isso em mente, o software deve nos provar que estamos errado. Ao realizar cada ação e analisar cada comportamento dele, devemos deixar que o próprio software nos convença completamente do contrário. 

> *"Software should be assumed guilty until proven innocent."*

## 2. Empatia e "Interpretação de papel"
Bons testadores possuem a habilidade de imaginar eles mesmos como o usuário final, para tentar prever o que o usuário pode fazer e como pode ficar confuso e/ou frustado ao utilizar o software. Essa compreensão, permite aos testadores encontrar erros antes que eles causem problemas aos usuários reais.

Nesse contexto, ter empatia é algo mais profundo do que "O usuário quer realizar uma compra, então eu também vou realizar uma compra", é sobre compreender seu incentivo, sua história e objetivos.

## 3. Desafiar os pressupostos
Ao testar uma funcionalidade numa aplicação não trivial, há um número infinito de ações e caminhos possíveis de ser testados. Utilizamos os pressupostos para reduzir este âmbito infinito de testes ao conjunto razoável com grande probabilidade de encontrar problemas. Devemos utilizar todas as ferramentas a nossa disposição para entender melhor quais os pressupostos a desafiar, quando e como os desafiar.

> Exemplo: "A aplicação utiliza uma biblioteca de código aberto... Não vou assumir que ela funciona, vou testá-la também!". Podemos desafiar essa suposição, fazendo perguntas como: É utilizada por milhões de pessoas ou foi criada por alguém aleatório? Tem comunidade ativa?

A mentalidade do testador reconhece e avalia constantemente os pressupostos para determinar se são válidos.

## 4. Pensamento Intuitivo e Comportamento Exploratório
Teste de software é uma atividade não linear e imprevisível, requer pensamento crítico, e dependem também de instinto, intuição e execução algorítmica de ações. Bons testadores utilizam a natureza intuitiva e exploratória dos testes.

Grandes referências falam sobre testes exploratórios:

- Elizabeth Hendrickson, no livro: [Explore It!: Reduce Risk and Increase Confidence with Exploratory Testing]

- James A. Whittaker, no livro: [Exploratory Software Testing: Tips, Tricks, Tours, and Techniques to Guide Test Design]

- Lisa Crispin e Janet Gregory, no livro [Agile Testing: A Practical Guide for Testers and Agile Teams 1st Edition]

- James Bach e Michael Bolton, no artigo: [Exploratory Testing 3.0]

## 5. Reconhecimento da natureza humana
Como testador, devemos reconhecer que um software é apenas o produto final de um longo processo, é o resultado final da colaboração de um grupo de pessoas para criar algo maior e mais complexo do que qualquer um deles poderia criar individualmente.

Os defeitos de um software são sintomas de problemas ocorridos no processo. Portanto, como testadores devemos nos preocupar também com os processos de desenvolvimento e com o comportamento dos seres humanos envolvidos tanto quanto com o produto final.

Enquanto humanos, nós nos distraimos, esquecemos, nos aborrecemos, ficamos frustados, cansados, com inveja, e etc. Temos nossas próprias agendas, ambições, motivações e objetivos de vida, dos quais o desenvolvimento de um software específico para uma empresa específica nem sequer faz parte. Todas essas falhas estão presentes quando os desenvolvedores desenvolvem, quando os analistas analisam, quando os executivos executam e por ai vai...

Ao testar um software devemos reconhecer que estamos olhando para um produto final de atividades humanas e que os erros que procuramos serão mais frequentemente sintomas das deficiências humanas do que de implementações incorretas de um algoritmo ou requisito conhecido por parte do programador.

# Referência
https://medium.com/@blakenorrish/how-to-think-like-a-tester-7a174ff6aeaf

[Explore It!: Reduce Risk and Increase Confidence with Exploratory Testing]: https://www.amazon.com/Explore-Increase-Confidence-Exploratory-Testing-ebook-dp-B00I8W50T8/dp/B00I8W50T8

[Exploratory Software Testing: Tips, Tricks, Tours, and Techniques to Guide Test Design]: https://www.amazon.com/Exploratory-Software-Testing-Tricks-Techniques/dp/0321636414/

[Agile Testing: A Practical Guide for Testers and Agile Teams 1st Edition]: https://www.amazon.com/Agile-Testing-Practical-Guide-Testers/dp/0321534468/

[Exploratory Testing 3.0]: https://www.satisfice.com/blog/archives/1509