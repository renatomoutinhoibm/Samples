# Samples

Versão WEB (Geral Web) - Este é o exemplo que te falei que dá pra colocar o fundo do site do cliente (estático) e ele abre uma janelinha de chat. É legal para DEMOS. Veja abaixo instruções para fazer o deploy no IBM Cloud
 
1. Mudar o nome do host no manifest.yml e se quiser também o da aplicação
2. Na pasta public, a imagem com nome background.png será o fundo estático da sua página
3. Dentro da pasta Controllers acesse o arquivo chamado Conversation e insira as credenciais do seu serviço: username, password e workspace ID.
4. Acesse a pasta onde está o seu arquivo manifest pelo cmd e execute o comando: cf push
 
Os demais arquivos são referentes ao exemplo que te mostrei ontem. Lembrando que ele tem um código para o front-end e um para o back-end. Neste caso vc precisa de 2 runtimes. Para fazer o deploy na cloud basta seguir as instruções do tutorial (GIT) enviadas pelo Francis anteriormente.
 
OBS: Antes de fazer o "cf push" você precisa seguir as instruções do link abaixo para utilizar os comandos do Cloud Foundry através da linha de comando:
 
https://console.bluemix.net/docs/cli/index.html#overview
