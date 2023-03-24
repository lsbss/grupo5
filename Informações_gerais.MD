## Padrão de código

    Identação e espaços em branco
    1.1 Use quatro espaços para cada nível de recuo.
    1.2 Não misture espaços e tabs para alinhar o código.
    1.3 Remova espaços em branco no final de cada linha.
    1.4 Deixe uma linha em branco no final do arquivo.

    Nomes de variáveis e funções
    2.1 Use nomes descritivos e significativos para as variáveis e funções.
    2.2 Use camelCase para nomes de variáveis e PascalCase para nomes de funções.
    2.3 Evite nomes genéricos, como "temp" ou "aux".
    2.4 Não use caracteres especiais nos nomes de variáveis ou funções.

    Comentários
    3.1 Adicione comentários ao código sempre que necessário para explicar o que está acontecendo.
    3.2 Use comentários para documentar funções e métodos.
    3.3 Mantenha os comentários atualizados conforme o código evolui.

    Formatação de código
    4.1 Limite cada linha a 80 caracteres.
    4.2 Use uma linha em branco para separar blocos de código relacionados.
    4.3 Mantenha o código simples e legível, evitando linhas muito longas ou complexas.

    Conclusão
    5.1 Esta política se aplica a todos os desenvolvedores da empresa.
    5.2 Qualquer violação desta política deve ser relatada ao líder técnico da equipe.
    5.3 Esta política será revisada regularmente para garantir sua eficácia e relevância.

## Repositório
Este repositório irá concentrar código, documentações, testes, scripts de configuração e outros artefatos necessários para o ciclo de vida da aplicação incluindo o seu processo de manutenção corretiva e evolutiva.

Leia as seções abaixo sobre branches, issues, testes e deploy para maiores informações. 

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
O lançamento das versões em produção será feito através da estrutura de entrega contínua _(CD - Continuous Delivery)_ já configurada e estabelecida na ferramenta definida para este fim. O lançamento de novas funcionalidades será gradativo seguindo uma estratégia Blue/Green e será monitorado.Em caso observadas falhas um rollback poderá ser acionado para reverter as mudanças sem que cause prejuízo para os usuários.

