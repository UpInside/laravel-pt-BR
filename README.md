# Tradução Laravel - Português do Brasil (pt-BR)
Esse repositório tem a finalidade de abrigar as traduções dos arquivos contidos em `/resources/lang/en` para o português brasileiro.

## Pré-requisito
O laravel deve estar instalado e rodando normalmente dentro do seu ambiente (independente se é desenvolvimento ou produção).

### Aviso
Esse procedimento pode sobrescrever os seus atuais arquivos de tradução caso existam! Portanto, tenha certeza de ter feito o backup do seu projeto antes de continuar com qualquer passo.<br />

Cada versão tende a ter sua própria **release/tag**. Você deve efetuar o **download/clone** de acordo com a versão do framework correspondente.

## Instalação

Acesse o diretório referente aos arquivos que serão copiados

```
$ cd resources/lang/
```

Efetue o clone deste repositório setando a versão do framework

```
git clone https://github.com/UpInside/laravel-pt-BR.git ./pt-BR
```

Nesse momento será feito o clone do repositório para dentro do seu projeto!<br />

> Lembre-se que nesse momento os arquivos serão substituídos

Agora basta remover os arquivos gerados automaticamente pelo git para ter a tradução disponível na sua aplicação

```
$ rm -rf pt-BR/.git/
```

Agora basta informar ao Laravel de que há outro idioma. Para isso, edite o arquivo `/config/app.php` e altere o valor da propriedade `locale` para `pt-br`

```
'locale' => 'pt-br',
```

## Contribuição
Deseja enviar correções de alguma tradução? Só efetuar um pull-request deste repositório e efetuar a alteração dentro de uma nova branch (que não seja a `master`).<br />

Crie uma branch com seu nome e a versão (`gustavo-web-5.6`) com as correções para que seja aprovada.<br />
Maiores informações, você pode ter através de [cursos@upinside.com.br](cursos@upinside.com.br).<br />

[@guhweb](https://github.com/guhweb) que mantém esse projeto rodando!