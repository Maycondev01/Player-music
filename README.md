# Documentação do Player de Músicas
## Estrutura do Projeto
O projeto é composto por três partes principais: os arquivos de músicas (songs.js), o arquivo HTML (index.html), e os scripts JavaScript (script.js).

## Arquivo songs.js
O arquivo songs.js contém uma lista de objetos, cada um representando uma música. Cada objeto possui dois campos:

- src: O caminho relativo para o arquivo MP3 da música.
- name: O nome da música junto com o artista.
  
## Arquivo HTML (index.html)
O arquivo HTML define a estrutura da página do player de músicas. Ele inclui elementos para exibir o nome da música, controles de reprodução, uma barra de progresso, e informações de tempo.

## Scripts JavaScript (script.js)
O script JavaScript manipula a lógica de reprodução e interação com o usuário. Ele utiliza o arquivo songs.js para obter informações sobre as músicas e atualizar dinamicamente a interface.

### Utilização do Player
**Controles de Reprodução:**

- Play/Pause: O botão com o ícone "play" ou "pause" inicia ou pausa a reprodução da música.
Anterior/Próxima: Os botões "anterior" e "próxima" permitem navegar entre as músicas.
Barra de Progresso:

- A barra de progresso exibe visualmente a posição atual da música em relação à sua duração total.
Informações de Tempo:

- A seção inferior exibe o tempo decorrido (currentTime) e a duração total (duration) da música.
Inicialização Automática:

- O player é iniciado automaticamente com a primeira música ao carregar a página.

## Estrutura do Script JavaScript
**O script script.js possui as seguintes funcionalidades:**

- Play/Pause:

- O botão de play/pause alterna entre iniciar e pausar a reprodução da música.
Atualização de Tempo:

- Atualiza dinamicamente o tempo decorrido, a duração total e a barra de progresso durante a reprodução.
Navegação entre Músicas:

- Permite a navegação entre músicas, automaticamente reiniciando do início quando a última música é atingida.

## Barra de Progresso Interativa:

- Permite clicar na barra de progresso para pular para uma posição específica na música.
  
## Personalização
O projeto utiliza o conjunto de ícones FontAwesome para os botões de controle. Certifique-se de incluir a biblioteca FontAwesome em sua página para a correta exibição dos ícones.

`<script src="https://kit.fontawesome.com/4ad8e2c939.js" crossorigin="anonymous"></script>`
