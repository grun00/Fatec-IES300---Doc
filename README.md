# Sobre

Repositorio da documentacao do projeto de IES300 na Fatec Sao Paulo

# Git Flow

* Nomear as branchs com o seguinte formato: [iniciais]-[nome_feature]
* Exemplo:
  ```
    $> git branch
    lg-feature-login
    af-feature-deletar-usuario
    ks-feature-adicionar-campo-valor-ao-model-usuario
  ```
* criar a branch a partir da branch `dev`
* merge na master somente com aprovacao de 2 outras pessoas

# Comandos basicos:
   * Cria branch com nome lg-feature-login
   ```bash
     $> git checkout -b lg-feature-login
   ```
   * lista arquivos modificados:
   ```bash
     $> git stats
   ```
   * adiciona um arquivo para a area de staging
   ```bash
    $> git add README.md
   ```
   * Comita mudancas
   ```bash
    $> git commit -m 'minha mensagem de commit'
   ```
   * sobe a branch para o github:
   ```
     $> git push origin lg-feature-login
   ```


