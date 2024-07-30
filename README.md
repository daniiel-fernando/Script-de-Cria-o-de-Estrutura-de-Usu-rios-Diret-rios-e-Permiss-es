# Configuração Automática de Usuários e Permissões

Este script automatiza a criação de usuários, grupos, diretórios e configurações de permissões em um sistema Linux.

## Como usar

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Dê permissão de execução ao script:
    ```bash
    chmod +x setup.sh
    ```

3. Execute o script:
    ```bash
    sudo ./setup.sh
    ```

## Usuários e Grupos Criados

- **Usuários**: `user1`, `user2`, `user3`
- **Grupos**: `group1`, `group2`

## Diretórios Criados

- `/home/projects`
- `/home/shared`

## Permissões

- `/home/projects`: `group1` tem acesso de escrita, `group2` tem acesso de leitura.
- `/home/shared`: Ambos os grupos têm acesso de leitura e escrita.

## Contribuições

Sinta-se à vontade para enviar pull requests ou abrir issues para melhorar este script.
