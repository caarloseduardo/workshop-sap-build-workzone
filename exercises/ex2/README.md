# Exercício 02 - Adicionar um App SAPUI5 no seu site

### Primeiro passo: Abrir o Gerenciamento de Conteúdo (Content Manager)
1. Dentro do **diretório de sites (Site Directory)**, navegue para o **gerenciamento de conteúdo dos sites (Content Manager)**.
  ![Open Content Manager](images/img01.png)

### Segundo passo: Crie e configure um novo app
1. Clique em **"Create"**, e selecione **"App"**.
  ![Create App](images/img02.png)

2. Preencha os seguintes campos com os valores:
  * **Title**: `Novas Ordens`
  * **Open App**: In place
  * **URL**: `https://sapui5.hana.ondemand.com/test-resources/sap/m/demokit/cart/webapp/index.html`
  ![Content Manager Configuration](images/img03.png)

3. Vá para a aba **"Navigation"**.
  ![Navigation](images/img04.png)

4. Preencha os seguintes campos com os valores:
  * **Semantic Object**: `Order`
  * **Action**: `display`
  ![Intent](images/img05.png)

5. Vá para a aba **"Visualization"**.
  ![Visualization](images/img06.png)

6. Preencha os seguintes campos com os valores:
  * **Subtitle**: `Carrinho de compras`
  * **Information**: `Compre  agora!`
  * **Icon**: `Compre  agora!`
  ![Visualization Configurations](images/img07.png)
    > Na direita, você pode ver a pré-visualização de como ficará sua aplicação no WorkZone. Após isso, clique no botão **"Save"**.

### Terceiro passo: Atribuír a permissão todos (Everyone) ao seu app
> Para que seu app fique visível para todos os usuários, é necessário atribuír a permissão "Everyone" à ele, o que será ensinado nesse passo.

1. Clique eu **"Content Manager"** para retornar à listagem de conteúdos.
  ![Content Manager](images/img08.png)

2. Selecione a linha **"Everyone"**, na listagem.
  ![Everyone](images/img09.png)

3. Na tela, clique no botão **"Edit"**, à direita.
  ![Edit Everyone](images/img10.png)

4. Ao entrar na edição, procure a linha correspondente ao seu app **"Novas Ordens"**. Clique no botão **"Assignment Status"** na respectiva linha, e após clique em **"Save"**.
  ![Assignement Status](images/img11.png)

5. Agora você pode visualizar seu app na listagem. Clique em **"Content Manager"** para retornar.
  ![Content Manager](images/img12.png)

### Quarto passo: Criar um grupo e atribuir o app à ele
> Um grupo é um conjunto de um ou mais apps que são apresentados juntos no site. Ao atribuir apps aos grupos, deixamos eles visíveis ao usuário.

1. Clique em **"Create"**, e selecione **"Group"**.
  ![Create Group](images/img13.png)

2. Preencha o campo **"Title"** com o valor **"Compras"**. 
  Procure a linha correspondente ao seu app **"Novas Ordens"**. Clique no botão **"Assignment Status"** na respectiva linha, e após clique em **"Save"**.
  ![Group Informations](images/img14.png)

## Revisão
Pronto! Agora você já pode visualizar o app que adicionamos no seu site, no grupo "Compras" 

![Site](images/img15.png)
![App Fiori](images/img16.png)

## Próximo Passo:
[Exercício 03 - Adicionar um App Fiori do BAS](/exercises/ex3/README.md)