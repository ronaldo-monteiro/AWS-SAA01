# AWS IAM: Acesso Somente Leitura ao S3

## 📌 Objetivo

### Criar um usuário IAM que pode apenas visualizar os conteúdos dos buckets S3, utilizando o console da AWS.

📍 Cenário

 ### Um analista de dados precisa visualizar os arquivos armazenados nos buckets S3, mas não deve modificar nada, nem ter acesso a outros recursos da AWS.

## ⚙️ Configuração

### Criar um usuário IAM no AWS.

Atribuir uma política personalizada com permissões somente leitura para o S3.

Garantir que o usuário tenha acesso ao console da AWS.

🛠️ Política IAM Exemplo

A seguinte política JSON concede permissão de leitura aos buckets S3: