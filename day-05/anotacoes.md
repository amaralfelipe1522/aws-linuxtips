# Day 05 - IAM

## Assume Role
Roles do tipo Account (Another AWS Account) que permitem assumir roles de contas diferentes, sem precisar usar a Root Account. Essa role é criada na conta de destino.
É possível ter permissões diferentes para cada conta acessada.
> Geralmente o padrão de nomenclatura é CrossRoleXXXXX

Na conta de origem é necessário informar:
- Alias ou ID;
- Nome da Role;
- Display Name é uma funcionalidade que te da uma melhor visão do papel assumido no destino naquele momento;
- Cor tem como objetivo complementar o mesmo controle de uso do Display Name.

## Indentity Providers
Usado quando você quer vincular sua base de usuários já existentes em algum outro provider como:
- SAML;
- OpenID Connect.

## Accounts Settings

Settings para definir para todos os usuários do IAM:
- Como será a senha;
- quanto tempo de expiração;
- Se pode usar senhas antigas;
- Definir regiões;
- Etc.

## Accounts Reports
Exibe relatório de todos os usuários do IAM, seus status e seus usos. Útil para criar automações de envio de alertas para os usuários.
