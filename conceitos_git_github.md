# GUIA DE CONCEITOS DE GIT E GITHUB
Criado por Dalmo Silva Mendes

**Colaboradores:** * Ao adicionar informações não se esquecer de indicar a fonte da consulta, informar a fonte é importante e da credibilidade para o projeto.

# Lista de Colaboradores:
* Marcelo CFSF

## O que é Git?

Então, o que é o Git em poucas palavras? Esta é uma parte que é importante aprender, porque se você entender o que Git é e os fundamentos de como ele funciona, em seguida, provavelmente usar efetivamente o Git será muito mais fácil para você. Enquanto você estiver aprendendo sobre o Git, tente esquecer das coisas que você pode saber sobre outros VCSs, como Subversion e Perforce; isso vai ajudá-lo a evitar a confusão sutil ao usar a ferramenta. Git armazena e vê informações de forma muito diferente do que esses outros sistemas, mesmo que a interface do usuário seja bastante semelhante, e entender essas diferenças o ajudará a não ficar confuso. (Perforce). (Pro Git, Scott Chacon e Bem Straub, p. 12, 2020).

## O que é GitHub?

GitHub é uma plataforma de hospedagem de código-fonte com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores. (https://pt.wikipedia.org/wiki/GitHub).

## TRABALHANDO COM BRANCH

### O que são Branching? 

Quase todo (VCS – Controle de Versão) tem algum tipo de suporte de ramificação. Ramificação significa que você diverge da linha principal de desenvolvimento e continue a trabalhar sem mexer com essa linha principal. Em muitos Ferramentas VCS, esse é um processo um pouco caro, geralmente exigindo que você crie uma nova cópia do seu diretório de código-fonte, que pode demorar muito para grandes projetos.

Algumas pessoas se referem ao modelo de ramificação do Git como seu "recurso matador" e certamente o diferencia do Git em a comunidade VCS. Por que é tão especial? A maneira como o Git se ramifica é incrivelmente leve, tornando operações de ramificação quase instantâneas e alternar entre ramificações geralmente tão rápido. Diferentemente de muitos outros VCSs, o Git incentiva fluxos de trabalho que ramificam e mesclam frequentemente, mesmo várias vezes em um dia. Compreender e dominar esse recurso oferece uma poderosa ferramenta única e pode mudar completamente a maneira como você desenvolve. (Pro Git, Scott Chacon e Bem Straub, p. 12, 2020).

Branches permitem que diferentes versões do mesmo conteúdo se desenvolvam ao mesmo tempo, porém de forma independente, enquanto você recombina periodicamente as contribuições de diferentes branches em um processo chamado “fusão” merging. (GIT Guia Prático, O’Reilly).
