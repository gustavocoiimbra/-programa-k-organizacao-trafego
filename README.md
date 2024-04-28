# Organização Tráfego - Detecção de Veículos

## Visão Geral
Este projeto faz parte do *Programa K* da UFG - Universidade Federal de Goiás e tem como objetivo desenvolver um modelo de Inteligência Artificial/Visão Computacional para reconhecimento de veículos no trânsito. O projeto visa, criar um sistema capaz de identificar as condições de tráfego e fornecer orientações aos motoristas por meio de texto em painéis eletrônicos, com o intuito de otimizar o fluxo do tráfego e melhorar a segurança viária, buscando um auxílio diário ao condutor, sem a necessidade de um agente de transito para situações adversas.

## Contexto
Atualmente, o foco está na escolha e implementação de modelos de detecção de objetos que sejam adequados ao contexto do problema geral. Dado que a detecção de veículos é apenas uma parte do sistema, é crucial selecionar modelos que possam ser integrados de forma eficiente com outras formas de detecção, como faixas de trânsito.

O projeto foi estruturado em três frentes principais: Pesquisa, Implementação e Documentação.

## Funcionalidades
- *Detecção de Objetos Avançada*: Utiliza YOLOv8 e Faster R-CNN, entre os modelos de detecção de objetos mais eficientes, adequados para processamento em tempo real.
- *Compatibilidade com Múltiplas Fontes*: Capaz de processar entradas de imagens estáticas, arquivos de vídeo e transmissões em tempo real de webcams.
- *Alta Precisão e Velocidade*: Garante detecções de veículos rápidas e precisas, cruciais para aplicações em tempo real.
- *Integração Fácil*: Projetado para ser facilmente integrado em sistemas maiores ou aplicações que requerem capacidades de detecção de veículos.

## Pesquisa
A equipe de pesquisa é responsável por avaliar e selecionar os modelos de detecção de veículos mais adequados ao contexto do problema. Isso envolve a análise de diversos modelos disponíveis, como YOLO, Faster R-CNN, entre outros, considerando critérios como precisão, velocidade de processamento e capacidade de integração com outros sistemas de detecção.

## Implementação
A equipe de implementação trabalha na integração dos modelos selecionados com o código existente, bem como na adaptação e otimização dos algoritmos para atender às necessidades específicas do projeto. Para isso, utilizamos uma variedade de tecnologias e abordagens, incluindo:

### Tecnologias Utilizadas
Este projeto é implementado usando Python com as seguintes bibliotecas:
- *Python*: A linguagem de programação principal do projeto, conhecida por sua
simplicidade e flexibilidade.
- *PyTorch*: Um framework de aprendizado de máquina de código aberto que
fornece ferramentas e bibliotecas essenciais para desenvolver modelos de
visão computacional.
- *Ultralytics YOLO*: Uma implementação eficiente e de alto desempenho do
algoritmo YOLO (You Only Look Once) para detecção de objetos em tempo
real.
- *OpenCV*: Para processamento de imagens e tarefas gerais de visão computacional.
- *Pillow (PIL)*: Para abrir, manipular e salvar diversos formatos de arquivos de imagem.
- *NumPy*: Para operações de alto desempenho com arrays multidimensionais e funções matemáticas.

### Abordagens e Técnica
- *Transfer Learning*: Aproveitamos modelos de detecção de objetos
pré-treinados, como YOLOv9, treinados em grandes conjuntos de dados, e
ajustamos esses modelos para atender às especificações do nosso problema
específico.
- *Processamento de Imagem e Vídeo*: Utilizamos técnicas avançadas de
processamento de imagem e vídeo, como segmentação de objetos, análise
de movimento e rastreamento de objetos, para identificar e acompanhar os
veículos no trânsito.

## Documentação
A equipe de documentação é responsável por registrar todo o processo de desenvolvimento, desde a pesquisa inicial até a implementação final. Isso inclui a criação de documentos técnicos, tutoriais e manuais de usuário, bem como a organização e manutenção do repositório no GitHub.

## Como Usar

### Utilização
- Python 3.x
- Bibliotecas Python listadas no arquivo requirements.txt
- Modelos de detecção de objetos treinados, como yolov9c.pt

### Instalação
1. Clone este repositório para o seu ambiente local.
2. Instale as dependências do projeto executando o comando pip install -r requirements.txt.
3. Baixe os modelos de detecção de objetos necessários, como yolov9c.pt, e coloque-os na pasta apropriada do projeto.

### Como Usar
Para executar a detecção de carros, siga estas etapas:

1. Execute o notebook detecção-carros-v.1.1.ipynb ou detecção-carros-v1.0.ipynb usando Jupyter ou outro ambiente compatível.
2. Siga as instruções dentro do notebook para carregar o vídeo desejado e iniciar a detecção de carros.
3. Se necessário, ajuste os parâmetros de detecção ou rastreamento no código do notebook.

## Exemplos
Para ver exemplos de como usar este projeto, consulte os notebooks detecção-carros-v.1.1.ipynb e detecção-carros-v1.0.ipynb.
