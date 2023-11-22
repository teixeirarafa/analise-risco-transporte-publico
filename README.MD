

<h1 align="center">
  Análise de Risco no Transporte Público
</h1>


# :pushpin: Lista de Conteúdo 
* [Sobre](#recycle-sobre)
* [Tecnologias Utilizadas](#clipboard-tecnologias-utilizadas)
* [Licença](#scroll-licença)

# :recycle: Sobre
Quais incidentes de trânsito ocorrem com mais frequência? Qual a faixa 
etária que mais se envolve em incidentes de trânsito? Qual o evento mais comum 
nos incidentes? Passageiros ou pedestres são as maiores vítimas dos incidentes?
Essas e outras perguntas devem ser respondidas através da análise de dados
reais disponíveis publicamente. Este projeto não requer Machine Learning e o 
trabalho é aplicar habilidades de análise e responder diversas perguntas de 
negócio através de gráficos e storytelling.

Dataset disponível para download no link abaixo, conjunto de dados lista incidentes de trânsito ocorridos na cidade de Londres
https://data.world/makeovermonday/2018w51


1- Qual a quantidade de incidentes por gênero?

`df_incident['Victims Sex'].value_counts().reset_index()`

2- Qual faixa etária esteve mais envolvida nos incidentes?

`df_incident['Victims Age'].value_counts().reset_index()`

Confira as outras respostas no jupyter notebook

# :clipboard: Tecnologias Utilizadas
* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/docs/)
* [Numpy](https://numpy.org/doc/)
* [Plotly](https://plotly.com/python/)

# :scroll: Licença
Este projeto está sob a [LICENÇA](https://opensource.org/licenses/MIT) do MIT
