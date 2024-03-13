# DIO - AZURE AI COMPUTER VISION


## Adicionar legendas a imagens
Através deste recurso podemos descrever o que esta presente em imagens, existem diversos casos de uso, como levantamento rapido de informações e ajuda para pessoas com dificuldades visuais.

Alguns casos de uso interessantes:
1 - Escanear imagens de uma camera de segurança para verificar se não existe alguma atividade suspeita
2 - Criar labels para imagens e textos, podendo ser integrados a websites a fim de melhorar a acessibilidade
3 - Integração com sites para realizar as legendas de imagens que podem usar outras IA's generativas a fim de descrever melhor o conteúdo via prompt de texto

### PASSO A PASSO
01 - Dentro do Vision Studio na guia Image analysis (Análise de imagens) clique na opção Add captions to imagens (Adicionar legenda a imagens).

02 - O recurso trás algumas imagens de exemplo para que você realize testes do serviço e até mesmo a possibilidade de realizar upload de uma foto sua e ter a descrição, no meu caso adicionei algumas fotos aleatórias (cortesia do usuário alexklenio) para testes e o serviço me retorna a descrição do que identificou na imagem.


## Optical character recognition (OCR) -> Reconhecimento de caracteres ópticos
Essa ferramenta converte uma imagem que possui textos em um formato de texto legível por máquina.
Por exemplo, podemos digitalizar um recibo, comprovante, conta de cobrança, fotos de diários, contratos, entre outros. Com essa imagem a IA realiza a leitura das informações e faz a transformação em caracteres de texto. Esses dados podem ser muito relevantes a fim de agilizar as validações de informações.

Um caso de uso interessante é um escritório de advocacia, que recebe muitos arquivos em formato PDF digitalizado, realizar a leitura do conteúdo para ter uma mais fácil visualização e manipulação das imagens

### PASSO A PASSO
Através deste recurso a Inteligência Artificial extrai o texto que conseguir identificar na imagem, extremamente util para o escaneamento de documentos e notas:

01 - Dentro do Vision Studio na guia Optical character recognition (Reconhecimento de caracteres ópticos) clique na opção Extract text from images (Extrair texto de imagens).
02 - O recurso trás algumas imagens de exemplo para que você realize testes do serviço e até mesmo a possibilidade de realizar upload de uma foto sua e ter a descrição, no meu caso adicionei algumas fotos aleatórias (cortesia do usuário alexklenio) para testes e o serviço me retorna a descrição do que identificou na imagem.


### Finalização
Essa ferramenta é muito útil em casos como os citados acima. Existe hoje em algumas companhias muito documento antigo que precisa ser escaneado e armazenado em forma virtual, muitos documentos técnicos que foram impressos e estão sendo usados de forma manual, podemos via chamadas de API, criar uma interface amigável para o usuário realizar os uploads dos arquivos escaneados para realização da leitura ou contextualização das imagens e com o uso de lógica de programação salvar o arquivo em locais adequados como uma rede privada ou numa cloud da empresa.
Abre espaço para ferramentas de manipulação de dados e aumenta bastante a quantidade de informação relevante de diversas companhias, podemos integrar com engenharia de dados para validar as vendas dos últimos 20 anos por exemplo, vendo cada nota fiscal emitida que pode ser que esteja em algum arquivo físico da empresa.
As possibilidades são imensas!