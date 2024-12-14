# sistema-streaming-der
"Diagrama ER para modelagem de banco de dados de um sistema de streaming de filmes desenvolvido no MySQL Workbench".

## Entidades e Relacionamentos
- **Usuário**: Armazena informações do usuário como ID, Nome, E-mail, CPF, e Endereço.
- **Endereço**: Representa os dados do endereço do usuário, incluindo Rua, Número, Cidade, Estado e CEP.
- **Conteúdo**: Dados sobre os filmes disponíveis no sistema, como Título, Gênero, Ano e Estúdio.
- **Estúdio**: Cada conteúdo está associado a um único estúdio, que pode estar relacionado a vários conteúdos.
- **Visualização**: Relaciona usuários aos conteúdos assistidos, armazenando o tempo de visualização.

## Regras de Negócio
1. Cada usuário deve ter um endereço único.
2. Cada conteúdo deve estar vinculado a um único estúdio.
3. Relacionamento n:n entre usuários e conteúdos via a tabela `Visualização`.

## Arquivos no Repositório
- `README.md
- `diagrama.mwb`: Arquivo do MySQL Workbench com o diagrama ER.
- `diagrama.png`: Imagem exportada do diagrama para visualização rápida.

## Como visualizar o Diagrama
1. Baixe o arquivo `diagrama.mwb`.
2. Abra no MySQL Workbench.
3. Opcionalmente, execute o script `script.sql` para criar as tabelas no banco de dados.

---

![Captura de tela 2024-12-14 161005](https://github.com/user-attachments/assets/04a76de4-e441-4ad6-8c24-5cae6e4c7771)


