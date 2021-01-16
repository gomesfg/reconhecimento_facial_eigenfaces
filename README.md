## Reconhecimento Facial Eigenfaces 

FURB - Pós Graduação em Data Science<br/>
Aprendizado não-supervisionado<br/>
Aluno: Felipe Eduardo Gomes

Repositório dos fontes do Trabalho Final de Aprendizado Não Supervisionado - FURB

### Passo-a-passo
Baixar o arquivo "trabalho_final_aprendizado_não_supervisionado.py"
```
docker pull dajobe/hbase
```
Ativar o ambiente pelo docker compose
```
docker-compose up hbase-server
```
Acessar o shell do hbase
```
docker-compose exec hbase-server hbase shell
```
<br/>

### Exercício 1 - Aquecendo com alguns dados

> 1. Crie a tabela com 2 famílias de colunas:
a. personal-data
b. professional-data

```
create_namespace 'italians'
Took 0.8345 seconds
```

