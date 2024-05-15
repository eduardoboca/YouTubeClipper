<div align=center>
    <img src="https://github.com/eduardoboca/YouTubeClipper/blob/main/assets/YouTubeClipper.png" width="20%" height="20%" />
    <hr>
</div>

# YouTubeClipper
Uma ferramenta em Python para extrair informações sobre vídeos do YouTube

## 📱 Projeto
O YouTubeClipper é uma ferramenta que facilita a extração e o resumo de informações de vídeos do YouTube. Ele expande as capacidades do Gemini, permitindo o processamento de vídeos de qualquer tamanho e fornecendo uma solução abrangente para análise de conteúdo de vídeo em larga escala.

## ⚙️ Tecnologias
- Python
- Google Colab
- YouTube API
- Gemini API

## 🤔 Como Funciona
O YouTubeClipper integra-se ao YouTube para baixar vídeos e extrair transcrições usando a YouTube API. Em seguida, utiliza a Gemini API para resumir automaticamente as transcrições dos vídeos processados. O resultado é uma linha do tempo automática dos vídeos, facilitando a compreensão e análise do conteúdo.

## 🧪 Como Testar
Para testar o YouTubeClipper, siga estas etapas:
1. Clone o repositório.
2. Abra o notebook [`YouTubeClipper.ipynb`](https://colab.research.google.com/drive/1cnvPna6JC4nO0vm0Eu5dm4cx2FoRm-kQ?usp=sharing) no Google Colab.
3. Siga as instruções fornecidas no notebook para processar um vídeo do YouTube e visualizar os resultados.

## 🎉 Exemplo de Resultado
### Neste vídeo: <br>
<div align="left">
    <a href="https://www.youtube.com/watch?v=KG3Or6IydNo" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/eduardoboca/YouTubeClipper/blob/main/assets/alepe.png" width="30%" height="30%" />
    </a>
    <hr>
</div>

O resultado do processamento foi o seguinte:
#### Resumo:
O vídeo aborda a estrutura e o funcionamento das frentes parlamentares e comissões especiais na Assembleia Legislativa de Pernambuco (Alepe). Ele explica o processo de criação, composição e objetivos desses colegiados, destacando seu papel crucial na discussão e acompanhamento de questões de interesse público..

#### Timeline:
00:00:13 - [Frentes parlamentares e comissões especiais na Alepe](https://www.youtube.com/watch?v=KG3Or6IydNo&t=13s)

00:00:30 - [Criação de frentes parlamentares](https://www.youtube.com/watch?v=KG3Or6IydNo&t=30s)

00:01:03 - [Formação de comissões especiais](https://www.youtube.com/watch?v=KG3Or6IydNo&t=63s)

00:01:37 - [Acompanhamento das atividades legislativas na TV Alepe e no YouTube](https://www.youtube.com/watch?v=KG3Or6IydNo&t=97s)


## 🔜 Próximos passos

O próximo passo do projeto é implementar uma nova funcionalidade: a capacidade de buscar qualquer palavra ou frase nos vídeos. O usuáro informa uma palavra e o YouTube Clipper retorna uma timeline com todos os momentos em que a palavra foi citada. 

Já existe um colab separado pronto funcionando com essa nova feature: 
[`YouTubeClipper_Next.ipynb`](https://github.com/eduardoboca/YouTubeClipper/blob/main/src/YoutubeClipper_Next.ipynb)

Mas ainda há alguns ajustes necessários para lidar com casos especiais, então decidimos deixar para versões futuras.
