# Gerador de Senhas

## Sobre o Projeto
Este é um gerador de senhas simples desenvolvido em C#. Ele permite ao usuário criar senhas personalizadas com diferentes critérios, salvar as senhas geradas em um arquivo e consultá-las posteriormente.

## Funcionalidades
- Gerar senhas com tamanho definido pelo usuário
- Opção de incluir números, letras maiúsculas e símbolos
- Salvar as senhas geradas em um arquivo (`senhas.txt`)
- Ler as senhas já geradas e salvas
- Interface baseada no terminal

## Requisitos
- Windows
- 
## Como Executar
1. Baixe o executável disponível no [GitHub](https://github.com/GabrielVesal/PasswordGenerator).
2. Execute o arquivo `GeradorDeSenhas.exe`.
3. Siga as instruções exibidas no terminal.

## Como Usar
Após iniciar o programa, será exibido um menu com as seguintes opções:

1. **Gerar uma senha**: O usuário pode definir o tamanho da senha e escolher se deseja incluir números, letras maiúsculas e símbolos.
2. **Ler as senhas geradas**: Exibe todas as senhas armazenadas no arquivo `senhas.txt`.
3. **Sair**: Encerra o programa.

## Estrutura do Código
- `GerarSenha(int tamanhodasenha, bool aceitaMaiuscula, bool aceitaNumero, bool aceitaSimbolo)`: Gera a senha conforme as preferências do usuário.
- `SalvarSenha(string senha)`: Salva a senha gerada no arquivo `senhas.txt`.
- `LerSenhas()`: Retorna uma lista com todas as senhas salvas.

## Download
Baixe o executável diretamente do repositório no GitHub: [Clique aqui](https://github.com/seu-repositorio)

