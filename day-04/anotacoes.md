# Day 04 - IAM

IAM é um produto vinculado a todas as contas por default. É um recurso responsável em gerenciar usuários e seus respectivos acessos, utilizando switch roles.

## IAM Dashboard

- Secury Status: Exibe os status baseados nas boas praticas da AWS;
- User sing-in link: Usuário de IAM, que passará a ser a URL de acesso de sua equipe. É possível customizar o nome;
- ARN (Amazon Resource Name): Todo recurso, grupo, usuário criado na AWS possui um ARN, no qual pode ser vinculado a outros recursos;
- Groups:
    - Group name;
    - Attach Policy;
    - Review.
- Users:
    - Programmatic access: Usuário de serviço para Infra-as-code e automações;
    - AWS Management Console access: Usuário para humanos;
    - É possível incluir uma política diretamente ao usuário além das liberações vinculadas ao grupo.
- Roles: 