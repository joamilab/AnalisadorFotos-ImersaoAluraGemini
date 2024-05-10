# Analisador de fotos para perfis profissionais desenvolvido com Google Gemini
Analisador de fotos para perfis profissionais. Projeto desenvolvido para desafio da Imersão Alura em Gemini.

## Pré-requisitos
* Ter uma Google API Key obtida no Google AI Studio.

## Para executar no Google Colab
Necessário ter pelo menos uma foto disponível seguindo uma das opções abaixo:

* Adicionar foto via upload na sessão ativa do Google Colab.

<img src="https://github.com/joamilab/AnalisadorFotos-ImersaoAluraGemini/blob/main/foto-upload-colab.png">

* Adicionar foto no Google Drive e em seguida conectar o Google Drive e o Google Colab.

<img src="https://github.com/joamilab/AnalisadorFotos-ImersaoAluraGemini/blob/main/conectar-drive-colab.png">

## Entrada (prompt)
"Analisar se esta foto é adequada para usar em um perfil profissional.
 Se a foto for adequada, enumerar os pontos fortes, em tópicos.
 Se a foto não for adequada, enumerar os pontos fracos, em tópicos.
 Enumerar até 5 dicas para uma boa foto profissional, em tópicos."

 ## Saída
 * Análise em texto feita pelo 'gemini-pro-vision'.
 * A foto submetida em escala reduzida.

### Exemplos de saída

* Exemplo 1 - Foto adequada para um perfil profissional:

<img src="https://github.com/joamilab/AnalisadorFotos-ImersaoAluraGemini/blob/main/exemplo-saida-1.png">

* Exemplo 2 - Foto inadequada para um perfil profissional:

<img src="https://github.com/joamilab/AnalisadorFotos-ImersaoAluraGemini/blob/main/exemplo-saida-2.png">

