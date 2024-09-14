# PROJETO 1 - Engenharia de Dados - Growdev
Análise de Instagram  de influenciadores para marca Vans.

## Contexto

O time de Marketing da VANS é responsável pelo gerenciamento de campanhas com influencers no Instagram. Para maximizar o impacto das campanhas, é fundamental que o time consiga monitorar e analisar os dados de performance dos influencers. Esses dados incluem métricas como engajamento, crescimento de seguidores, tipo de conteúdo que gera mais interações, entre outros.

Estamos considerando uma possível parceria com alguns influenciador e gostaríamos de realizar uma análise detalhada para avaliar a viabilidade dessa colaboração.

## Objetivos solicitado pelo cliente 

- Monitoramento do Número de Seguidores: Precisamos acompanhar o número de seguidores do influenciador em questão semanalmente, durante um período de duas semanas. O objetivo é mensurar o crescimento percentual dos seguidores ao longo deste período.

- Análise de Comentários: Solicitamos uma amostragem de 10 comentários por postagem das últimas 5 postagens do influenciador. Esta análise ajudará a avaliar a qualidade das interações e o engajamento do público com o conteúdo publicado.

# Desenvolvimento do projeto

## Influenciadores

Aqui escolhemos inicialmente dois influenciadores de gerações diferentes, tentando impactar mais públicos, Marcito Castro e Gui Khury.

-Marcito Castro: https://www.instagram.com/marcitocastro/
-Gui Khury: https://www.instagram.com/gui_khury/

Marcito Castro é um influencer do Rio Grande do Sul, o mesmo é comediante da períferia de Porto Alegre e tem em suas caractéristcas piadas e histórias da geração que foi adolescente entre os anos 90. Uma geração madura que busca conforto, mais casualidade e discrição, talvez optando por Vans Old Skool e Era.

Gui Khury é jovem skatista profissional do Paraná com 18 anos e já reconhecido mundialmente, o mesmo é detentor de três Guinness World Records e inúmeros títulos internacionais. O Jovem influencia principalmente o publico da geração e Z devido a identificação com a idade, mas também a geração Y nascida na primera metade dos anos 90 e muito influenciada por Tony Hawk, Bob Burnquist, Charlie Brown Jr,  e etc, podendo ser trabalhado um leque maior de produtos do portifólio.

## Análise de Requisitos

Ao estudar o projeto, foi avaliado inicialmente fazer um webscraping do instagram por perfis, mas há uma grande chace de bloqueios constantes e quebra de código devido ao número de requisições.
Então chegamos a conclusão que o mais interessante seria investir em uma estrutura paga, optamos pelo sitema de requisição por API com Instagram Scraper API localizada no hub RapidAPI.com

Link:https://rapidapi.com/mrngstar/api/instagram-scraper-api3

O plano que atende a nossa necessidade:

- Plano Pró $15,00/ mês
- 20k de requisições / mês

  ![{90EEEBF3-C12C-4535-8F2B-AB033237828E}](https://github.com/user-attachments/assets/de7bfe13-ab56-45c9-8689-56e1294e3185)

## Objetivo

O principal objetivo nesse momento foi escrever um código pra pegar informações principais de cada perfil, analisar comentários das ultimas postagens, com auxilo da API Gemini AI, classificamos a qualidade dos comentários em Postivo, Negativo, Humor, Neutro para o time de negócio partir para tomada de decisão.

# Biografia

![{5DA95129-1879-4FA4-A779-64AFDC795957}](https://github.com/user-attachments/assets/7d5bde3a-59c6-4328-9045-b78ebcb8caa9)

![{A17CCA23-47BB-4DB3-8B59-59A4F2731397}](https://github.com/user-attachments/assets/e27d2b34-e852-413c-b86c-97544231f7fb)

# Comentários das ultimas postagens

![{CE34866A-DBD5-4479-8C2C-AE9CB1E3C94E}](https://github.com/user-attachments/assets/944dc474-0222-4bea-b774-d17c0b5cb1d9)
![{87B560A9-1025-40BD-879E-679A1E3AC734}](https://github.com/user-attachments/assets/88a82c6a-a64c-4e14-af76-4b632cae2ab8)

# Ferramentas externas utilizadas

- Google
- Medium
- ChatGPT
- Perplexity
- Gemini AI
  
