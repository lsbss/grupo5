## Padrão de código
To do

## Repositório
To do

## Branches

Os branches devem ser criados sempre a partir do ‘main’ 
Lembre-se de sempre atualizar o seu repositório local usando ``git pull`` antes de criar um novo branch, caso contrário você estará trabalhando em um branch desatualizado, o que poderá causar conflitos ao submeter as novas alterações.

**Exemplo:**

feat(funcionalidade)
fix(bug-id - utilizar a referência do bug-id/issue) 
docs(documento que será atualizado)

___Para mais informações relacionado a commits semânticos:___

Referências:
https://blog.cubos.io/que-tal-comecar-a-usar-commits-semanticos/
https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
https://www.conventionalcommits.org/en/v1.0.0/

## Issues

Sempre que se for necessário abrir uma nova issue decorrente de uma falha observada, sugestão de melhoria ou situações derivadas a mesma deverá ser feita através da aba [Issues](https://github.com/lsbss/grupo5/issues/new). 

Segue exemplo da estrutura:

**Título do problema**

**Passos para reproduzir o problema:**

**Passo 1:**
**Passo 2:**
**Passo N:**

**Resultado esperado:**

**Resultado observado:**

_Se for possível inclua arquivos de log e/ou detalhes técnicos que possam ajudar no processo de depuração._

## Testes

Após a criação de cada pull request todo o conjunto de testes deverá ser executado, sendo testes unitários, integração e de sistema. Os mesmos serão acionados a partir da estrutura de pipelines que fará a integração e entrega contínua(CI/CD). Ao passo que o software contendo as novas funcionalidades e alterações, passar nos testes a que foi submetido o mesmo será lançado em produção.

## Deploy
To do

