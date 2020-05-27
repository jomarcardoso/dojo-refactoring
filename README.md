# Refactoring

O que eu aprendi até hoje sobre melhorar um código

>*“The cleaner and nicer the program, the faster it’s going to run. And if it doesn’t, it’ll be easy to make it fast.”*
— Joshua Bloch

Tudo deve ser uma vantagem para o negócio, e não um luxo do desenvolvedor.

Resolver uma coisa de cada vez. Frase bem clichê, mas é isso mesmo, cada tarefa deve resolver só uma coisa, senão ela cresce e fica difícil de entregar, pois vai gerando mais problemas e fica mais difícil de testar.

Não faça sozinho, se houver uma equipe engajada renderá mais e haverá maior aprovação.

Saber perder. Show dos clichês. Costumo chamar de "Iniciativa" quando preciso fazer uma tentativa de resolver algo maior, ou seja, quando uma melhoria para ser efetiva precisa da execução de várias tarefas, porém o caminho para chegar até lá é incerto, então várias iniciativas são criadas, mas nem todas precisam ser concluídas, pois você não deve levar adiante soluções ruins. Iniciativas são pequenos passos que podem as vezes dar certo. 

Informe todas as "partes interessadas" (stakeholders). Evite questionamentos sobre suas atividades.

Se vai dar um passo para trás depois precisa dar vários para frente. Se de certa forma algo que está sendo feito é um retrocesso, que este seja justificado por algo melhor que vem depois. Quanto tempo e qual o impacto desse passo para trás?

No desenvolvimento ágil fazemos pequenas entregas, logo uma melhoria ágil serão várias entregas validadas também.

Se precisas fazer uma gambiarra para resolver um problema, provavelmente o caminho está errado e virão outras gambiarras.

Quase todos os problemas são possíveis de resolver, porém as vezes falta, conhecimento, criatividade, tempo, coragem ou esforço para isso.

Planejamento 👌 mais um clichê na sua cara. Digamos que você pega um código que foi escrito como se não houvesse amanhã, cada página é uma hotsite, cada componente é... não pera não tem componente não tem nada é a desordem total, então você e a equipe se convencem que precisam refazer aquilo tudo, componentizar, unificar... O Zézinho começa fazendo a parte dele "ah tem 2 botões aqui, então vou fazer um componente de botão e vamos reaproveitar", a Mariazinha nem sabe que ele fez o botão novo e vai lá e cria outro botão com o mesmo intuíto que o Zezinho. Bom até agora tá facil de arrumar, só escolher um dos botões que foi criado e jogar fora, perdemos esforço, mas nada demais, agora tanto o Zezinho como a Mariazinha são novatos, eles passaram por vários outros possíveis componentes que poderiam ter sido refeitos, porém não enxergaram e fizeram da mesma forma que era feito, antes sem padrão nenhum e sem resolver nada, e daí vamos para o próximo capítulo.

### A culpa é sempre sua

Culpar os outros não vai te levar a nada. O outro errou? Culpa sua se ele errou, por que você deixou ele errar? Você não precisa controlar os colegas, fazer eles te seguirem e obedecer o que você mandar. Mas como vinha falando da história da Mariazinha e o Zezinho eles são novatos, as entregas ruins que eles fizeram provavelmente não foi porque eles são preguiçosos ou burros, mas simplemente não foi planejado por ninguém o que seria feito, então eles não conseguiram ver por algum motivo uma forma melhor de executar a tarefa que lhes foi dado. Então se você culpar os outros vai conseguir brigas, se culpar a si conseguirá resultados.

## Abordagens

Analisar antes de fazer. Mais um clichê. A importância aqui é analisar bem a situação para saber escolher a abordagem correta, refazer, melhorar, nem botar a mão...

### Melhorar

Apesar de não ser o que o desenvolvedor queira essa normalmente é a alternativa mais segura e mais prática. 

- continua funcionando
- reaproveita o que já foi pensado
- melhoria contínua
- pequenas entregas

O planejamento deve começar por estipular onde quer-se chegar, a meta, de preferência o cenário perfeito, bem longe. Após isso quebrar em outras metas menores e em sequência, pois lembrando que em um negócio é preciso "entrega de valor". A execução então será feita com o consentimento do time sobre essas metas. 

Deve ser substituída pelo refazer quando o esforço e o resultado final forem muito aquém de refazer.

### Refazer / nem botar a mão

O que o desenvolvedor mais gosta, refazer o trabalho dos outros achando que faz melhor, e por quê ele acha isso?

- Porque ele já viu as falhas do antigo código e sabe que aquele erro ele não pode cometer.
- Porque a tecnologia evolui para facilitar, então um código mais antigo normalmente com tecnologia defasada é menos prática.
- Há sempre a descoberta de novas boas práticas.

Nem botar a mão está diretamente associado a refazer, pois se a única opção é refazer e você não pode, então nem bota a mão.
