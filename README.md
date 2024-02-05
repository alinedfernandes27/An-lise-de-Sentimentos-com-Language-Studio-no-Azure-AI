# An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI
Desafio de projeto usando Azure Speech Studio e análise linguística proporcionada pelo Language Studio.

# Criar um recurso de Fala de IA do Azure


Você pode usar o serviço de Fala criando um recurso de Fala ou um recurso de serviços de IA do Azure.

Neste exercício, você criará um recurso de Fala de IA, a menos que já tenha um recurso que possa usar.

1. Em outra guia do navegador, abra o Azure AI Speech Studio, entrando com sua conta da Microsoft.

2. Selecione Configurações e Criar um recurso. Configure-o com as seguintes configurações:
   
• Nome do novo recurso: insira um nome exclusivo.

•Assinatura: sua assinatura do Azure.

•Região: selecione uma região com suporte.

•Nível de preços: FO gratuito (se disponível, caso contrário, selecione Standard S0).

•Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.

3. Selecione Criar recurso. Aguarde até que o recurso tenha sido criado e selecione Usar recurso. A página Introdução à fala é exibida.
   
# Explorar a conversão de voz em texto no Speech Studio

1. Selecione https://aka.ms/mslearn-speech-files para baixar speech.zip. Abra a pasta.

2. Na página Introdução à Fala, em Fala, localize Conversão de fala em texto em tempo real. Selecione Experimentar conversão de voz em texto em tempo real.
   
![try-out-speech-to-text](https://github.com/alinedfernandes27/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/115157598/88871f1e-e5cc-454b-a87b-25234de8bcf8)

3. Em Escolher arquivos de áudio, selecione Procurar arquivos e navegue até a pasta onde você salvou o arquivo. Selecione WhatAICanDo.m4a e, em seguida, Abrir.


![browse-files-speech](https://github.com/alinedfernandes27/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/115157598/4b104738-27ca-4a1e-9546-e0b6aa074e0a)

4. O serviço de Fala transcreve e exibe o texto em tempo real. Se você tiver áudio no computador, poderá ouvir a gravação enquanto o texto está sendo transcrito.

5. Revise a saída, que deve ter reconhecido e transcrito com sucesso o áudio em texto.
