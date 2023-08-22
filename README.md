# Projeto Integrador - Modelo

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Aluno: Raí Vericimo Gaudereto

# Modelos de Sistemas: Empréstimo
# Situação Problema
**Gerenciamento de uma Quadra de Esportes**

Uma empresa de empréstimos de materiais esportivos, chamada RAÍGatão, ajuda atletas que não possuem dinheiro para empréstimos de materiais para praticar esportes. Atualmente, comprou mais de 1000 itens para esporte, desde bolas, joelheiras, calçados, obstáculos entre outros. Eles querem emprestar os materiais para os atletas, os atletas precisam comprovar situação de carência econômica para poderem ter acesso aos itens. Possuem um computador para arquivar os itens de estoque. Precisam de um sistema que gerencie todo o estoque, empréstimos, materiais disponíveis, etc. mas para que isso ocorra de maneira simples e sem necessidade de novos gastos. Também é importante que haja relatórios, permitindo o controle dos empréstimos e dos materiais disponíveis no acervo.

O nome da empresa é RaíGatao, nosso objetivo é incentivar e divulgar o esporte, por meio de materiais que disponibilizamos para empréstimo para atletas carentes, existe a possibilidade de empréstimo para pessoas com boa renda fianceira, porém, é cobrado um valor variando de cada item, diferente dos atletas carentes que não precisam pagar. Estamos abertos a mais de 5 anos, o idealizador do projeto e criador da RaíGatão foi Valdevino Padilha, conta atualmente com 3 funcionários. Um responsável pelo controle do estoque, um pela limpeza e conservação dos itens, outro recepciona os atletas e entrega os itens aos clientes. A empresa funciona atualmente apenas com meios manuscritos para controle de empréstimos através de caderno, algo que se torna muito confuso, trabalhoso e falta de organização.
    
Com a chegada de novos itens a demanda aumentou, a empresa quer tornar o sistema de empréstimos *inteiramente* digital, fazendo com que apenas a retirada dos itens seja na locação física. 
    
A empresa precisa de um sistema que seja capaz de cadastrar usuários, controlar o estoque de itens, cobrança, isenção de taxa para pessoas baixa-renda, prazo e taxas adicionais para atrasos

# Descrição da proposta

Analisando o funcionamento da empresa e os problemas destacados, chegamos a uma solução possível. 

Criaremos um site onde o usuário-cliente irá efetuar um cadastro, feito pelo recepcinista presencialmente e assim terá acesso aos itens para locação, podendo atráves de poucos cliques marcar a data de retirada e devolção do item.

irão existir 3 níveis de conta: conta-cliente, funcionário e administrador

O usuario-recepcionista irá cadastrar as novas contas dos clientes, será o responsável por checar se o item realmente foi alugado antes da retirada física (conta de funcionário)

o usuario-estoquista irá fazer o cadastro de novos itens e retirar os itens que não estão mais em condições de uso (conta de funcionário)

O usuario-administrador terá acesso a todos os relatórios de empréstimos, itens novos cadastrados e excluídos do sistema, ao lucro e gastos mensais da empresa e a todos os benefícios das contas anteriores

Regras De Negócio;

R.F. 01 - Cadastro de Usuários:
Permitir que o recepcionista cadastre novos usuários no sistema, classificando-os como cliente, funcionário ou administrador.

R.F. 02 - Itens Disponíveis para Empréstimo:
Possibilitar o cadastramento de itens esportivos disponíveis para empréstimo, como bolas, joelheiras, calçados, obstáculos, etc.

R.F. 03 - Cobrança e Isenção de Taxas:
Gerenciar a cobrança de taxas para empréstimo de itens esportivos, incluindo isenção de taxas para atletas carentes e cálculo de taxas variáveis para pessoas com boa renda financeira.

R.F. 04 - Empréstimos e Devoluções:
Permitir que usuários-clientes solicitem empréstimos de itens esportivos através do site, definindo datas de retirada e devolução. Registrar empréstimos e devoluções no sistema.

R.F. 05 - Controle de Estoque:
Possibilitar ao usuário-estoquista cadastrar novos itens no sistema e marcar itens que não estão mais em condições de uso. Manter um registro atualizado do estoque disponível.

R.F. 06 - Níveis de Acesso:
Implementar três níveis de acesso: cliente, funcionário e administrador. Cada nível terá diferentes permissões e funcionalidades.

R.F. 07 - Relatórios e Controle Financeiro:
Fornecer ao administrador a capacidade de acessar relatórios detalhados, incluindo informações sobre empréstimos, itens cadastrados e excluídos, lucros e gastos mensais.

R.F. 08 - Atendimento ao Cliente:
Oferecer meios para que os usuários possam entrar em contato com a empresa, fazer perguntas ou relatar problemas relacionados aos empréstimos e aos itens.

R.F. 09 - Interface Amigável:
Desenvolver uma interface de usuário intuitiva e de fácil navegação, acessível a partir de diferentes dispositivos, garantindo a usabilidade para todos os níveis de usuários.

R.F. 10 - Segurança e Privacidade:
Implementar medidas de segurança para proteger os dados pessoais dos usuários, incluindo o armazenamento seguro de senhas.

R.F. 11 - Integração Física e Digital:
Integrar o sistema digital ao processo físico de retirada dos itens na locação, garantindo uma experiência fluida para os usuários.

R.F. 12 - Acesso por Funcionários:
Permitir que funcionários acessem o sistema com suas credenciais para realizar funções específicas, como cadastrar clientes, verificar itens, etc.

R.F. 13 - Registro de Atividades:
Registrar todas as atividades realizadas no sistema, criando um registro para fins de auditoria e rastreamento das ações realizadas.


**Alguns pontos importantes a se destacar são:**

-   **Qual o foco de ação do software** relacionado com os problemas levantados na análise da situação-problema. O que realmente o software vai fazer. Por exemplo, o foco de ação do Gmail é permitir o envio e recebimento de e-mails.
-   **Os níveis de usuário do sistema**. Somente o gestor tem acesso? E os funcionários? Talvez seja para ambos, ou para funcionários de cargos
    diferentes, etc.
-   **O que poderá ser feito no software**.Apenas o principal, sem pensar em
    telas ou detalhes específicos, pois isso será feito em outro momento.
    -   **Se houver mais de um nível de usuário**, ressaltar as diferenças entre
        eles na descrição da proposta.

Tenha em mente que essa é uma etapa relativamente breve. Não é necessário um texto gigantesco, apenas dar uma noção do funcionamento do sistema. Mais adiante
precisaremos ser bem detalhistas, todavia agora a intenção é apenas fazer algo que permita ao cliente nos dizer se estamos no caminho certo.
