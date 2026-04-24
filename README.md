# jankenpo-php-cli

Jogo de pedra, papel e tesoura para jogar no terminal.

Os testes ficam na pasta de testes, e na raiz existe um script que aciona o executor de testes.

Há uma gravação mostrando a execução.

## Execução

Na raiz do projeto, execute o script de jogo:

```
./play.sh
```

## Testes automatizados

Instale primeiro o gerenciador de dependências, conforme a página oficial.

Por quê? Porque as dependências do projeto são administradas por ele, e o executor de testes é uma delas.

Depois de instalar, rode na raiz:

```
composer install
```

E então execute o script de testes:

### Note

Deixei este detalhe registrado porque me custou tempo para descobrir.


```
./test.sh
```