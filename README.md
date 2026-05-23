
# Criatividade e Estratégia com o uso de Inteligência Artificial

Este repositório contém um conteúdo de estudo sobre a utilização de Inteligência Artificial no cenário criativo audiovisual, passando por áreas como __Composição de cena, utilizaçao de modelos, fotografia de produtos, utilizaçao de equipamentos e Story board.__

## Contexto e Objetivos: 

#### Sobre o notebook 
📔 Este caderno aborda a **utilização estratégica da Inteligência Artificial** na criação de campanhas publicitárias e na produção audiovisual de alta fidelidade, explorando desde a pesquisa de branding e escrita de roteiros até a geração de imagens e vídeos.

🎮 O material detalha técnicas avançadas para combater a __"deriva de identidade"__ e garantir a consistência visual de personagens e produtos através do uso de "DNA de personagem", LoRAs e ControlNet.

🎯 Os principais objetivos de estudo incluem o __domínio de workflows híbridos que integram ferramentas como GPT, Midjourney e Nano Banana Pro__, visando uma direção criativa autoral e o controle determinístico sobre alucinações e instabilidades temporais

❗ Ao final, busca-se capacitar o usuário a transformar ideias em narrativas visuais coesas e profissionais, otimizando prazos e custos de produção

## 🌐 Curadoria de Fontes: 

### Abaixo estão disponibilizadas algumas das fontes utilizadas para a criação do notebook.

#### Links úteis

✅ [___Consistencia de Personagem___](https://academypass.ai/blog/personagem-consistente-ia)

✅ [___Da idéia ao movimento___](https://www.youtube.com/watch?v=XQjD2m3L-AY)

✅ [___Edicao Pontual com Uso de IAs___](https://academypass.ai/blog/edicao-pontual-imagens-ia)

✅ [___Story Board - Composição de cena e camera___](https://www.youtube.com/playlist?list=PLeSL3Fj-4bOhyRxRGR4XbIB9t4iKgfMk5)


✅ [___Iluminação e tonalidades de pele___](https://academypass.ai/blog/iluminacao-natural-imagens-ia)


## 🔨 🪛 Engenharia de Prompts e "Cicatrizes": 

Com base no conteúdo explorado sobre planejamento estratégico, consistência visual e produção audiovisual com IA, ___aqui estão algumas perguntas-chave___ que devem ser usadas para guiar em um estudo e aprofundar o domínio técnico:

1. ___Direção Criativa vs. Geração Automática:___ 
Como a transição do papel de "usuário de prompts" para o de Diretor Criativo, utilizando ferramentas de Deep Research e a estruturação de Dossiês da Marca, pode alterar a precisão e a originalidade dos resultados entregues pela IA em uma campanha?

2. __Combate à Deriva de Identidade:__
O que define o fenômeno da __"deriva de identidade" (identity drift)__ e de que forma a criação de um DNA do Personagem (como folhas de rotação e imagens âncora) serve como base indispensável para as técnicas de LoRA e Referência de Personagem?

3. __Diferenciais do Nano Banana Pro:__
Quais são as vantagens técnicas exclusivas do __modelo Nano Banana Pro (Gemini 3 Image)__ ao lidar com a inserção de produtos em cenários mais complexos e a manutenção de múltiplas referências visuais (até 14 imagens) simultaneamente?

4. __Estabilidade Temporal em Vídeo:__
Por que o __"flicker de iluminação"__ e o __"derretimento de rostos"__ ocorrem em gerações de vídeo puramente baseadas em texto (TEXT TO VIDEO), e como o workflow de __"Imagem-Mestre de Referência"__ (IMAGE TO VIDEO) estabelece âncoras determinísticas para garantir fluidez cinematográfica?

5. __Workflow Híbrido e Eficiência:__ 
Como a integração de ferramentas distintas em um fluxo baseado em nós __(como o Spaces dentro do Magnific ou ComfyUI)__ permite separar a exploração estética do refino estrutural, e quais são os ganhos reais em termos de custos e prazos de produção?

## Miniguia de Estudo

### 💻  Abaixo um miniguia de estudo e uso ideal do Notebook

Este __Miniguia de Estudo__ consolida as estratégias para transformar a Inteligência Artificial em uma aliada na criação de campanhas e produções audiovisuais de alta fidelidade. O foco está na transição do papel de __"digitador de prompts"__ para o de Diretor Criativo, utilizando IAs para amplificar a visão humana com controle e intenção. 
Ao dominar o conceito de __DNA do Personagem e workflows baseados em referências determinísticas (Image2Video)__, o profissional elimina a imprevisibilidade e garante a integridade da marca. 
Este material serve como base pragmática para revisar processos que reduzem custos de produção em até 80% enquanto mantêm resultados de nível cinematográfico. A consistência visual deixa de __ser sorte e passa a ser uma consequência direta da metodologia aplicada.__

### ✍️ Resumos Estruturados do Assunto

1. Planejamento e Estratégia __(Fase de elaboração via texto):__ 
A campanha começa com a criação de um Dossiê da Marca e o uso de ferramentas de Deep Research para entender o posicionamento. O __uso de Projetos no GPT__ permite que a IA mantenha uma memória contínua de todo o contexto, evitando que o conceito se perca entre as conversas.
2. __Consistência e Identidade Visual:__ Para evitar a "deriva de identidade", é essencial estabelecer o DNA do Personagem antes da geração, incluindo proporções faciais e __a criação de imagens âncoras em fundo neutro.__ Ferramentas como o Nano Banana Pro permitem usar múltiplas referências (até 14 imagens) para garantir que modelos e produtos permaneçam 95% consistentes em diferentes cenas.
3. __Produção Audiovisual (Movimento):__ O workflow profissional prioriza o modelo Image-to-Video (I2V) sobre o Text-to-Video para eliminar o "flicker" de iluminação e manter a estabilidade temporal. A utilização de ControlNet permite que a estrutura de uma imagem guie a composição e pose no vídeo com precisão cirúrgica

### 🔐 Glossário de Conceitos Chave utilizados

1. __Para Cocriação de Briefing (GPT/Gemini):__
"Estou planejando uma campanha para __[NOME DA MARCA]__. Quero que você atue como meu estrategista de marca e ou Diretor Criativo. Antes de começarmos, o que você precisa saber sobre o público é: __tom de voz, objetivos, persona e referências de mercado__ para me ajudar a criar o manifesto e o roteiro mais assertivo possível?"
2. __Para Criação de DNA de Personagem (Midjourney/Flux):__
"Full-body neutral portrait of [DESCRIÇÃO DO PERSONAGEM], wearing [VESTUÁRIO ESPECÍFICO], neutral background, clean studio lighting, 8k resolution, shot on 85mm lens, --style raw --ar 16:9."
3. __Para Inserção de Produto (Nano Banana Pro/Gemini Editor):__
"Utilize a [IMAGEM DO PRODUTO DE REFERENCIA] e a [IMAGEM DO CENÁRIO]. Insira o produto no centro da cena de forma totalmente integrada, respeitando a direção das sombras, a textura dos materiais e a temperatura de cor original do ambiente."
4. __Para Direção de Movimento em Vídeo (Director Assistant):__
"A partir desta imagem, crie um movimento de câmera [TIPO DE MOVIMENTO, ex: slow tracking shot] focando na reação do personagem. Mantenha a iluminação estável e evite alterações na identidade facial, focando apenas no deslocamento cinematográfico."











