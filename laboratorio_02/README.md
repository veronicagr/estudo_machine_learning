# Explore o Vision Studio Azure

Este é um tutorial de estudo solicitado pela Digital Innovation One - [DIO](https://www.dio.me/) para praticar os conceitos aprendidos no curso de 
Introdução ao Aprendizado de Máquina' [Microsoft Azure AI Fundamentals](https://web.dio.me/track/microsoft-azure-ai-fundamentals).

Neste exercício, usaremos o recurso de reconhecimento Facial e transformação de imagens em Dados no Azure ML.

## Pré-requisitos

* Ter uma conta no Microsoft Azure.

#### Se você não possui conta no Microsoft Azure siga os passos abaixo:

* Acesse o site da [Microsoft Azure](https://azure.microsoft.com/pt-br)
* Clique em Experimente gratuitamente.
* Será necessário colocar os dados de sua conta da Microsoft, caso não possua criar.
* Será necessário cadastrar um cartão de crédito para aderir ao plano gratuito.
* Você terá $200 dólares de crédito ou 30 dias para testar os serviços.

## Explorando Azure Machine Learning

1. Entre no [Portal da Azure](https://portal.azure.com) com suas credenciais da Microsoft.

2. Na aba Azure Services procure por 'Criar recurso'.
![Alt text](/laboratorio_02/assets/image.png)

3. Em categorias selecione o item IA + Machine Learning.
![Alt text](/laboratorio_02/assets/image-1.png)

4. Clicar em Azure AI services

![Alt text](/laboratorio_02/assets/image-2.png)

5. Depois em Azure AI services multi-service account clicar em create

![Alt text](/laboratorio_02/assets/image-3.png)

6. Abrirá um painel com algumas informações para preencher

        Assinatura: sua assinatura do Azure
        Grupo de recursos: Crie ou selecione um grupo de recursos da sua assinatura
        Nome: Insira um nome exclusivo para seu espaço de trabalho
        Região: Selecione a região geográfica mais próxima
        Tipo de preço: Standard S0
        Clicar em examinar e criar
![Alt text](/laboratorio_02/assets/image-4.png)


7. Após a criação do recurso acessar o [Portal da Azure](https://portal.vision.cognitive.azure.com/) com suas credenciais da Microsoft. .

8. Clicar View all resources, aqui mostrará to resource que você acabou de criar na etapa anterior.

![Alt text](/laboratorio_02/assets/image-5.png)

9. Selecione o seu resource e clique em select as default Resource.

![Alt text](/laboratorio_02/assets/image-6.png)

10. Voltar para pagina inicial e ecolher a opção Detect faces in an image.

![Alt text](/laboratorio_02/assets/image-7.png)

11. Aceitar os termos e já pode começar a realizar os testes

![Alt text](/laboratorio_02/assets/image-9.png)

Obs: Se aparecer o error: BadRequestInvalidResource - Visio studio, aguarde alguns minutes e tente novamente.

### Extract text from images
Agora trabalharemos com extração de textos em imagens

1. clicar no item Extract text from images

![Alt text](/laboratorio_02/assets/image-10.png)

2. Inicie seus estudos explorando a IA 
![Alt text](/laboratorio_02/assets/image-11.png)  


# Deletando os serviços após o uso

O serviço web que você criou está hospedado em uma instância de contêiner do Azure . Se não pretender usa-lo, deverá eliminar para evitar utilização desnecessária do Azure.

Na pagina inicial do azure selecionar todos os recursos.

![Alt text](/laboratorio_02/assets/image-13.png)

Excluir as instâncias não utilizadas, pois isso garante que sua assinatura não será cobrada por recursos..

![Alt text](/laboratorio_02/assets/image-12.png)

Para excluir seu espaço de trabalho:

No portal Azure , na página Grupos de recursos , abra o grupo de recursos que especificou ao criar o seu espaço de trabalho Azure Machine Learning.
Clique em Excluir grupo de recursos , digite o nome do grupo de recursos para confirmar que deseja excluí-lo e selecione Excluir .