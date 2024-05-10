# Obsidiana com Gemini

Esta é a minha tentativa de criar um plugin para [Obsidian](https://obsidian.md). Eu uso o Obsidian como meu aplicativo de anotações diárias para criar minha base de conhecimento seguindo alguns sistemas de gestão de conhecimento pessoal, mas com meu toque pessoal. Eu nunca tentei programar nada em javascript e Typescript então este foi um grande desafio. 

A ideia de criar este Plugin surgiu da participação no [Imersão Alura + Google](https://www.alura.com.br/artigos/imersao-ia) que é um evento criado em parceria entre [Alura](https ://www.alura.com.br/) escola de tecnologia e Google. O código criado aqui é baseado em um [plug-in de exemplo para Obsidian](https://github.com/obsidianmd/obsidian-sample-plugin) e no [Guia de início rápido para a API Google Gemini](https://ai.google.dev/gemini-api/docs/ai-studio-quickstart).

# Demonstração das funcionalidades deste plugin. 



# Como usar este plugin no Obsidian. 

Este plugin ainda não está disponível na comunidade de plugins do Obsidian, então você precisa instalá-lo localmente. Pretendo solicitar a aprovação do plugin quando algumas funcionalidades estiverem mais elaboradas. Para executar este plugin localmente utilize o seguinte passo a passo:

## Etapa 1: Instale o Obsidian e crie um novo cofre

Baixe o aplicativo [Obsidian](https://obsidian.md) e instale-o em seu computador, se ainda não estiver instalado. Crie um novo cofre (recomendado) ou abra um dos seus cofres. Um cofre é apenas uma pasta no seu computador, portanto você pode acessá-lo fora do aplicativo Obsidian.

## Etapa 2: Baixe este projeto.

Baixe ou clone este projeto para o seu computador. Para baixar basta clicar no botão verde com `<code>` e clicar em download. Para clonar use o seguinte comando:

```shell
git clone https://github.com/rafaelalvesitm/obsidian-with-gemini-plugin.git
```
Uma vez baixado extraia os arquivos para o seu computador.

## Etapa 3: Mova a pasta plugins para o Obsidian

Abra a pasta que você definiu como cofre do Obsidian. Nesta pasta, existirá uma pasta chamada `.obsidian`. Mova a pasta plugins deste repositório para esta pasta. 

## Etapa 4: Defini as configurações do plugin. 

Abra seu cofre no próprio Obsidian e clique nas configurações (ícone de engrenagem no canto inferior esquerdo). Vá para os plug-ins da comunidade e habilite-os se eles já não estiverem habilitados. Veja se o aplicativo `Google Gemini Integration` é mostrado e está habilitado, se não estiver habilite-o aqui. Clique no ícone de engrenagem deste plugin. 

Nesta página você deve definir as configurações do Plugin, incluindo:

- Chave de API para a API Google Gemini - [Crie uma aqui caso não tenha](https://aistudio.google.com/app/u/1/apikey). 
- Frase padrão para resumir textos.
- Frase padrão para expandir textos.
- Frase padrão para reescrever textos. 
- Frase padrão para pedir respostas.

## Etapa 5: Use o plugin

Para usar este plugin, basta selecionar algum texto que deseja enviar ao Gemini e abrir  Paleta de Comandos (CTRL + P) e procurar um dos seguintes comandos:

- Resumir texto: Resume o texto selecionado incluindo a frase padrão definina para resumos nas configurações do plugin. 
- Expandir texto: Expande o texto selecionado incluindo a frase padrão definina para expansão de textos nas configurações do plugin. 
- Reescrever texto: Reescreve o texto selecionado incluindo a frase padrão definina para reescrita de textos nas configurações do plugin.
- Responder texto: Responde o texto selecionado incluindo a frase padrão definina para questionar nas configurações do plugin.

Você também pode definir atalhos para cada um destes comandos no próprio Obsidian. 

# Como contribuir para este projeto

Para contribuir com este projeto acesse o repositório https://github.com/rafaelalvesitm/obsidian-with-gemini-plugin. 