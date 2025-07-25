# Passo 1: O "Cérebro" do Chatbot - A Chave Mágica

Pense no Gemini como o "cérebro" do nosso chatbot. Para que nosso programa consiga se comunicar com esse "cérebro", precisamos de uma chave secreta, que chamamos de API KEY. É como uma senha que permite o acesso.
1. Obter a Chave Mágica (API KEY):
   
   • Você vai precisar de uma conta do Gmail. Se não tiver, é fácil criar uma.
   
   • Acesse o site do Google Gemini (o link é https://ai.google.dev/gemini-api/docs?hl=pt-br). Lá, você vai seguir uns passos simples para gerar essa chave. É só clicar em alguns botões, e pronto!

# Passo 2: O Caderno de Rascunhos - Colab
Agora que temos o "cérebro" (Gemini) e a chave para acessá-lo, precisamos de um lugar para escrever as "instruções" para o nosso chatbot. Esse lugar é o Colab.

1. Acessar o Caderno (Colab):

   • O Colab é como um caderno de rascunhos online do Google. É super fácil de usar!
   
   • Você vai acessá-lo pelo seu navegador de internet, usando sua conta do Gmail (o link é https://colab.google/).

# Passo 3: Montando o Nosso Chatbot

Agora é a parte onde vamos "montar" o nosso chatbot usando as instruções. Imagine que estamos dando uma receita de bolo para o computador, mas com algumas dicas de como o bolo deve "se comportar".

1. Preparando os Ingredientes (Instalação):

  • No nosso "caderno" (Colab), a primeira coisa que faremos é "instalar" algumas ferramentas que o programa precisa para funcionar. É como preparar os ingredientes para a receita.

2. A Chave Secreta no Lugar Certo:

  • Vamos "avisar" ao nosso programa qual é a chave mágica (API KEY) que pegamos lá no Passo 1. Assim, ele sabe como se conectar ao "cérebro" do Gemini.

3. Dando Vida ao Chatbot e Dando a Ele uma Personalidade:

  • Vamos "dar a partida" no nosso chatbot e, ao mesmo tempo, já "ensinar" a ele como deve ser. Demos a ele o nome de Jarvis e instruímos que ele seja bem humorado ou mal-humorado por exemplo, sempre tentando falar o menos possível e se apresentando no início da conversa. É como dar uma "personalidade" inicial para ele.

4. A Hora da Conversa (Loop Principal):

  • Aqui, criamos um ciclo sem fim para o nosso chatbot, onde ele sempre vai esperar por uma pergunta sua.

  • Ele vai te cumprimentar (com a personalidade dele!) e dizer que você pode digitar "Sair" para encerrar a conversa.

5. Sua Pergunta e a Resposta do Chatbot:

  • Quando você digita uma pergunta:

	  • Seu programa "envia" sua pergunta, junto com a "personalidade" do Jarvis, para o "cérebro" 	do Gemini.

	  • O "cérebro" do Gemini "processa" sua pergunta, levando em conta o "Jarvis", e 	"formula" uma resposta.

	  • Essa resposta é "recebida" pelo seu programa e "mostrada" na tela para você.

6. Guardando a Conversa:

  • Tanto a sua pergunta quanto a resposta do chatbot são guardadas na "memória" (histórico) para que a conversa faça sentido e ele não se "esqueça" do que já foi falado, mantendo a "personalidade" ao longo do papo.

# Basicamente, estamos:

• Pedindo uma chave de acesso para usar o "cérebro" do Google (Gemini).

• Abrindo um caderno (Colab) para escrever as instruções do nosso chatbot.

• Escrevendo as instruções que fazem o chatbot:

	• Se conectar ao "cérebro" do Gemini.

	• Ter uma personalidade específica (humorado ou mal-humorado, falando pouco).

	• Lembrar do que foi conversado.

	• Receber suas perguntas e dar respostas.

É como ter um amigo virtual com uma personalidade bem definida que pode conversar com você!


# Critério
  Ter uma conta Gmail
  
Criar API KEY 
Documentação em: https://ai.google.dev/gemini-api/docs?hl=pt-br

Acessar Colab
https://colab.google/
