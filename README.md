# Bem-vind@ ao Dev1!

Este *repositório* (isto é, este *projeto*, *conjunto de arquivos*, etc. Não precisa se preocupar exatamente com a definição de repositório agora, vamos aprimorá-la futuramente) tem como objetivo introduzir desde o **zero** tudo que uma pessoa precisa para estudar programação de maneira **efetiva e produtiva**.

Pra começar, é importante responder a pergunta: **o que exatamente é isso que você está lendo agora?**

Bem, ao contrário do que possa parecer, **este texto não é uma descrição do projeto**. Pelo menos, não oficialmente. Na verdade, ele é **um arquivo dentro do projeto**, chamado **README.md**. Grave o nome deste arquivo, pois ele é muito especial, e entendê-lo é um passo muito importante para seus estudos na área de tecnologia.

Vamos começar falando dos 3 últimos carácteres dele: **.md**. Como é comum na computação, esses caracteres representam a **extensão** de um arquivo. Por exemplo, você já deve ter ouvido falar na extensão **.png**, usada em imagens, ou da extensão **.txt**, para arquivos de texto. Bem, a extensão **.md** faz referência a um tipo de arquivo chamado **markdown**. Markdown é uma linguagem de marcação de texto, ou seja, ela permite formatar texto "de um jeito bonitinho", basicamente. Por exemplo, você pode fazer coisas como:


> ## Olha que legal!
---

1. ## Listas
2. ## Também?
3. ## Nossa!
---

```php
echo("Dá pra escrever código? Uau!")
```
---

Viu quanta coisa legal? A propósito, você provavelmente não reparou, mas as linhas que dividem cada um dos exemplos também foram feitas com markdown. É a linguagem de texto perfeita para fazer anotações! Você pode aprender a fazer tudo isso em markdown [clicando nesse link aqui](https://support.zendesk.com/hc/pt-br/articles/4408846544922-Formata%C3%A7%C3%A3o-de-texto-com-Markdown). É super simples!

Bem, com isso, aprendemos o que significa usar a extensão **.md**. Mas, e o nome **README**, tem algo de especial com ele?

Tem sim! Este nome é como um "acordo" na área de tecnologia. Ele serve como o "guia" de um projeto. Por isso que, quando você abriu este repositório, esse texto foi a primeira coisa que apareceu. Então, o texto não é exatamente uma descrição do projeto, e sim o arquivo **README.md**, que, por causa desse "acordo", é utilizado como descrição em absolutamente todos os projetos. Fez sentido?

Por natureza, o GitHub sempre procura o arquivo README.md no seu projeto, e exibe ele aqui. Pra isso acontecer, entretanto, o seu arquivo não pode estar em nenhuma pasta do projeto. Ou seja, ele precisa estar *na raiz*, na pasta inicial mesmo. Também, variações no nome do arquivo não vão funcionar como esperado. **Ele precisa se chamar README.md**. Isso significa que readme.md, meleia.md, readmedomeuprojeto.md, ou qualquer coisa parecida, são apenas arquivos normais em markdown. A magia só acontece com o arquivo README.md, e quando ele está na raiz do projeto.

Talvez você já tenha chego a essa conclusão, mas vamos deixar ela bem clara: **arquivos em markdown são excelentes para fazer anotações, especialmente na área de tecnologia**. O objetivo aqui é te convencer de como seus estudos podem ser muito mais produtivos se você fizer anotações em markdown, já que além de fixar melhor seu conhecimento, você sempre vai poder voltar nas suas anotações quando precisar.

Mas agora que você já sabe o que é o markdown, e como ele está relacionado com seu arquivo README.md, você precisa encontrar um lugar onde você possa escrever textos em markdown com qualidade. A primeira solução, e mais adequada pra quem vai utilizar as anotações em markdown pra aprender programação, é escrever textos diretamente pelo **Visual Studio Code**, o *ambiente de desenvolvimento integrado* (IDE) da Microsoft. Você pode baixar ele [aqui](https://code.visualstudio.com/download).

Você também pode usar editores markdown mais simples, que não são necessariamente voltados para código. [Esse link aqui](https://kinsta.com/pt/blog/editores-markdown/) tem algumas opções legais de editores que você poderia usar.

Bem, agora que você já entendeu a teoria do que é markdown, e percebeu o quão útil ele pode ser para seus estudos, é hora de nós entendermos um pouco mais sobre o segundo fundamento que vai facilitar muito seus estudos (especialmente em tecnologia, mas também pode ser usado em qualquer área): **a ferramenta de versionamento chamada Git.**

Você está, nesse momento, no GitHub. Como o nome sugere, o GitHub é um "salão principal" para o Git. Ou seja, ele não é a mesma coisa que Git. Lembre-se bem disso: **Git é uma ferramenta, uma tecnologia. GitHub é apenas um site que hospeda o conteúdo que nós fazemos usando o Git**.

### Mas afinal, então, o que é Git?

Para poder desenvolver uma explicação melhor, vou contar uma história: imagine que Maria e João precisam fazer um trabalho juntos pra faculdade. É um trabalho muito importante, com dezenas de páginas, e que vai demandar muito estudo, conversa, escrita, reescrita, revisão e etc. Com certeza, esse trabalho não vai ficar pronto da noite pro dia, e vai demandar bastante trabalho dos dois.

Como Maria e João vão fazer pra pra concluir esse trabalho, então? Bem, eles se organizaram para escrever ele parte por parte, dividindo entre os dois o que cada um vai escrever. Além disso, eles também vão revisar as partes que foram escritas pelo outro, e quando tiverem certeza de que gostaram dos *textos* (no plural, porque serão **vários**), vão se juntar para escrever os textos responsáveis por "conectar" cada um dos tópicos que eles já escreveram sobre, além de revisar os textos já escritos pra fazer com que eles se encaixem bem entre si.

Com certeza, esse é um processo trabalhoso. Você já consegue imaginar que cada um deles vai ter múltiplos arquivos, cada um no seu computador, com múltiplos textos e partes diferentes. Além disso, eles vão precisar trocar os arquivos entre si para fazer a revisão e correção, e cada arquivo provavelmente vai fazer múltiplas viagens entre os dois até ser totalmente finalizado. Não só isso, mas eles ainda vão precisar conectar e adaptar tudo no fim, para que o trabalho fique realmente coeso. Nessa situação, você com certeza consegue imaginar que os arquivos terão nomes como "texto1_final", "texto1_final_corrigido", "texto1_ultima_correção", "texto1_agora_vai", etc. Todo mundo aqui já fez isso, okay? Sem julgamentos.

Agora, imagine um mundo onde Maria e João podem escrever seus textos de uma maneira que a outra pessoa sempre vai poder acompanhar o progresso e desenvolvimento de cada texto. Imagina que eles pudessem, pela internet, de maneira *assíncrona* (isto é, sem a necessidade de estarem se comunicando ao mesmo tempo, como por ligações, vídeo chamadas e etc, mas de uma maneira onde fosse possível resolver tudo apenas por mensagens), revisar o texto um do outro, apontar falhas em trechos específicos, e acompanhar em tempo real a correção de cada uma das falhas? Imagina que todos os dois podem ter acesso a **todas** as versões mais recentes de **todos**, na hora que eles quiserem, só tendo acesso a internet? Imagine, ainda, que eles pudessem **facilmente revisar, editar e comparar TODAS as versões de TODOS os textos que eles estão escrevendo?**

### Tudo isso é papel do Git.

Esse nosso exemplo fictício serve para chegar na definição final do que é Git: *é uma ferramenta de versionamento de projetos**. Simples assim. Não precisa se preocupar com os detalhes técnicos por agora. Você só precisa entender que **Git é a ferramenta que possibilita que pessoas de qualquer lugar do planeta, a qualquer horário, trabalhem no mesmo projeto, acompanhem em tempo real o desenvolvimento de cada uma das versões do projeto (independente do quão pequenas sejam as mudanças), e revisem e consertem todos os erros que acontecem ao longo do projeto.** É uma ferramenta capaz de criar uma linha do tempo que mostra exatamente cada versão do projeto, com todas as suas atualizações e novidades.
