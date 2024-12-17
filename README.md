Cenário de teste criado utilizando o postman para automatizar usuário rondomico ,
depois criar automação de produto rodomicamente além de
buscar este produto e depois deletar produto criado rondomicamente.

Este cenário foi exportado da "collections" direto do postman 

[Download Postman](https://www.postman.com/downloads/)

Cenário criado apartir do site 

[Serverest](https://serverest.dev/)


Baixe o arquivo .json do repositório no GitHub.  [Automacao-Api-Postman-Testes](https://github.com/ElizabethGomes-QAEngineer/Automacao-Api-Postman-Testes/blob/main/Severest%20API.postman_collection.json)
Baixe o arquivo da coleção do Postman:
Abra o Postman, clique em Import e faça o upload do arquivo.
Execute os testes.


# Passo a Passo para Importar a Coleção do Postman

**1. Acesse o Repositório no GitHub**
   
Abra o seu repositório no GitHub onde a coleção do Postman foi salva.
Navegue até o arquivo .json da sua coleção (por exemplo, Severest API.postman_collection.json).

**2. Baixe o Arquivo .json**
   
Clique no arquivo para abri-lo no GitHub.
Clique no botão Raw (em cima do arquivo).
O navegador exibirá o conteúdo do arquivo. Para baixar, clique com o botão direito do mouse e selecione Salvar como... para fazer o download do arquivo .json para o seu computador.

**3. Abra o Postman**
   
Execute o Postman no seu computador.

**4. Importe o Arquivo no Postman**
 
Na tela inicial do Postman, clique em Import (canto superior esquerdo).
Escolha a opção Upload Files.

Selecione o arquivo .json que você baixou (por exemplo, Severest API.postman_collection.json).
Clique em Open para importar.

**5. Coleção Importada**
Sua coleção do Postman aparecerá na aba Collections. Agora você pode rodar os testes de API



# Como Realizar os Testes Dentro do Postman

Em "environments" configurar **globals** 

**1. "Variable"**

```bash
baseURL
```

**"Initial Value"/Current Value**

```bash
https://serverest.dev
```

**2. "Variable"**

```bash
user
```

**"Initial Value"/Current Value**

```bash
"qaenginieer419@qa.com.br"
```


**3. "Variable"**

```bash
password
```
**"Initial Value"/Current Value**

```bash
teste
```

**4. "Variable"**

```bash
accessToken
```

**5. "Variable"**

```bash
randomProductTest1
```

**"Initial Value"/Current Value**

```bash
randomProduct123
```

**6. "Variable"**

```bash
newProductId27
```

**7. "Variable"**
```bash
nome
```
**"Initial Value"/Current Value**

```bash
Elizabeth
```

# Passo a Passo Para Executar os Testes 


1. Em **POST** Cadastro Usuario em **cadastrar usuário** alterar o email para  **"qaenginieer419@qa.com.br"**
   depois clicar em **"save"**

2. Em **POST** Login em **Automação Login Gera Diferentes Tokens**
  alterar o email para  **"qaenginieer419@qa.com.br"**
  depois clicar em **"save"**

3. Em **POST** Produtos em **Automação Login Criar Produto Rondomico** na aba **scripts** em **pre-request**
   alterar o email para  **"qaenginieer419@qa.com.br"**
   depois clicar em **"save"**

   vai gerar um Id do produto clicar neste ID e **copia**

5. Em **GET** produtos em **Automação Encontrar Produto ID** {{baseURL}}/produtos/ o id do produto que foi copiado
   depois clicar em **"save"**

6. Em 
   
