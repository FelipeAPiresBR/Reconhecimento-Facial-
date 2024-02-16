
## Criação de uma inteligencia artificial com Reconhecimento Facial🙎‍♂️

#### Neste Artigo,iremos resumir em detalhes como criar uma inteligencia Artificial utilizando ferramentas do [Azure](https://portal.azure.com) + [Vision Studio](https://portal.vision.cognitive.azure.com)


1️⃣ Crie um recurso de serviços de IA no  [Azure](https://portal.azure.com)

![Criar um Recurso](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/Criar%20um%20Recurso.png?raw=true)

2️⃣Selecione no canto esquerdo **IA + Machine Learning** depois Serviços Cognitivos
![Serviços Cognitivos](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/servi%C3%A7os%20cognitivos.png?raw=true) 
##### Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:           
* Assinatura : sua assinatura do Azure .
* Grupo de recursos : selecione ou crie um grupo de recursos com um nome de sua escolha .
* Região : Leste dos EUA que os preços estão mais baratos que no brasil .
* Nome : Insira um nome de sua preferencia .
* Nível de preços : Standard S0.
* Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado .   
* Clique em Examinar + Criar e aguarde de **05 a 10 minutos** .
Segue imagem de Exemplo :
![Config Serviços Cognitivos](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/Config%20Servi%C3%A7os%20Cognitivos.png?raw=true)   
3️⃣ Conecte seu serviço de IA do Azure ao Vision Studio .
* Abra uma nova guia de navegador e procure :https://portal.vision.cognitive.azure.com.
* Entre com sua conta do **Azure** e lembre-se de entrar com a mesma conta que está seu diretorio onde está localizado seu serviço que acabamos de criar .
* Clique em Ver Todos os Recursos 
![Vision Studo Ver Todos os Recursos](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/Vision%20Studio%20Ver%20todos%20os%20recursos.png?raw=true)

* Em Seguida,selecione o recurso que você criou,marcando a bolinha a esquerda e marque Selecionar como recurso padrão,depois feche a página no **X**  a direita no canto superior,isso irá fazer voltar a tela inicial . 
![Reconhecimento Facil](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/Selecionar%20Seu%20Arquvio.png?raw=true )

4️⃣ Selecione a opção **Face** em Seguida **Detectar Rostos em uma imagem**
![LegendaDetectar rostos em uma imagem ](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/Detectar%20Rostos%20em%20uma%20Imagem.png?raw=true)


5️⃣ Marque o quadrado a esquerda e faça upload de uma foto sua a fins acadêmico,execute-o e faça o teste .


![Legenda](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/Marcar%20op%C3%A7ao%20e%20fazer%20upload%20de%20uma%20foto.png?raw=true)

* OBS: Caso ocorra  o segunte erro : 
![ErrorCode:BadRequestInvalidResourceld](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/errorcodeBadRequestInvalidResourcelo.png?raw=true)
* Volte ao passo 3️⃣,conecte novamente e aguarde de **05 a 10** minutos,esse erro ocorre devido que seu serviço ainda não terminou de sincronizar .

5️⃣ Termine de realizar o upload e teste a ferramenta,a imaginação e o limites , mas lembre-se,utilize apenas fotos sem propriedades intelectuais para não ocorrer nenhum problema.
![Foto Minha Nadando com os peixes](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/foto%20minha%20nadando%20com%20os%20peixes.png?raw=true)

# Epílogo 
 Chegamos ao fim de mais um Resumão,simples,mas eficiente, de como Criar uma IA capaz de realizar o mapeamento fácial de suas imagens,esse tutorial foi dedicado a pessoas que ainda não conhecem a ferramenta e estão em busca de algo prático.

 Em breve será disponibilizado 	[novos artigos](https://github.com/FelipeAPiresBR/ReconhecimentoFacial_Metamorfose-De-Imagens-Em-Dados.git) sobre IA e criação dos mais variados tipos para te auxiliar no dia-a-dia.

 O máterial de apoio que utilizei para realizar esse artigo se encontra aqui :  
 https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html 
 https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html

#### Qualquer dúvida ou Sugestão e muito bem vinda!🔁

