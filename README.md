# Shark

🛠 Sites usados:

- hycom

- copernicus

- earthdata

- csiro

🧠 Tecnologias e ferramentas:

- **Python** com bibliotecas científicas (Pandas, Matplotlib, NumPy, xarray).  
- **MiniConda** para controle de ambientes.  
- **Jupyter Notebook** para análise e experimentação.  
- **Inteligências Artificiais auxiliares**: Gemini, Manus, Claude e ChatGPT 

#Informacoes sobre o Tema

🌊 A Base Científica do Shark Sentinel: Decodificando os Oceanos para Proteger os Tubarões 🦈
O sucesso do Shark Sentinel reside na nossa capacidade de traduzir um universo de dados complexos de satélite em um indicador biológico claro e acionável: a probabilidade de encontrar um tubarão. Nosso modelo preditivo se baseia em uma premissa ecológica fundamental: os tubarões, como predadores de topo, concentram-se em áreas onde sua presa é abundante. A abundância de presas, por sua vez, é ditada por condições oceanográficas específicas que podemos medir do espaço, transformando o oceano em um livro aberto.


🌿 Fitoplâncton: O Coração Verde do Oceano
Por que é Relevante? 💡

O fitoplâncton é a base de toda a vida marinha. Essas microalgas, o verdadeiro "pasto do mar", formam o primeiro degrau da cadeia alimentar oceânica. Áreas com alta concentração de fitoplâncton atraem o zooplâncton, que por sua vez atrai peixes pequenos, que atraem peixes maiores e, finalmente, os tubarões. Portanto, um mapa de fitoplâncton é, essencialmente, um mapa do potencial de alimentação e um guia para os "restaurantes" preferidos dos tubarões.

Dados da NASA que Utilizamos: 🛰️

Utilizamos os dados dos espectrorradiômetros MODIS (Moderate Resolution Imaging Spectroradiometer), a bordo dos satélites Aqua e Terra da NASA. Este sensor revolucionário mede a concentração de clorofila-a na superfície do oceano. A clorofila é o pigmento que o fitoplâncton usa para a fotossíntese, e sua concentração é um excelente indicador da presença e da saúde dessas microalgas. Com 36 bandas espectrais, o MODIS nos permite monitorar a produtividade dos oceanos em escala global a cada 1-2 dias.

Sensor
Satélite(s)
O que mede
Relevância para o Modelo
MODIS
Terra & Aqua
Concentração de Clorofila-a
Indica a base da cadeia alimentar (fitoplâncton)



🔥 Temperatura da Superfície do Mar (SST): O Conforto Térmico dos Predadores
Por que é Relevante? 🌡️

Os tubarões, embora alguns consigam regular sua temperatura corporal, são sensíveis à temperatura da água. Cada espécie possui uma faixa de temperatura ideal onde seu metabolismo é mais eficiente e onde suas presas preferidas são encontradas. Mais importante ainda, as frentes térmicas — áreas onde massas de água fria e quente se encontram — são conhecidas por serem zonas de caça altamente produtivas. Essas frentes funcionam como barreiras naturais, concentrando nutrientes e presas, e criando "paredes" de alimentação para os tubarões.

Dados da NASA que Utilizamos: 🛰️

Sensores como o MODIS e o VIIRS (Visible Infrared Imaging Radiometer Suite) nos fornecem mapas globais e diários da SST com altíssima precisão. Ao analisar esses dados, nosso modelo identifica não apenas as "zonas de conforto" térmico para espécies-alvo, mas, crucialmente, localiza as frentes térmicas que funcionam como agregadores de vida marinha. Um estudo fundamental de Queiroz et al. (2016) na PNAS demonstrou que os tubarões preferem ativamente habitats caracterizados por fortes gradientes de temperatura, como as frentes.

"Os tubarões selecionam ativamente e se agregam em 'hotspots' de uso do espaço caracterizados por frentes térmicas e alta produtividade." - Queiroz et al. (2016)

Sensor
Satélite(s)
O que mede
Relevância para o Modelo
MODIS/VIIRS
Terra, Aqua, Suomi-NPP
Temperatura da Superfície do Mar (SST)
Identifica zonas de conforto térmico e frentes de caça



💨 Dinâmica Oceanográfica: As "Rodovias" e "Oásis" do Oceano
Por que é Relevante? 🗺️

As correntes, vórtices e, especialmente, os ventos, determinam como e para onde os nutrientes e o plâncton são transportados. Os ventos são o motor de um dos fenômenos mais importantes para a vida marinha: a ressurgência (ou upwelling).

Dados da NASA que Utilizamos: 🛰️

Conforme identificado no portal NASA Earthdata, utilizaremos conjuntos de dados como o "MetOp-A ASCAT Level 2 Ocean Surface Wind Vectors". Este produto nos fornece a velocidade e a direção dos ventos sobre o oceano com uma resolução de até 12.5 km.

A Conexão Crítica: Ventos e Ressurgência 🌪️➡️💧

A análise desses vetores de vento nos permite prever a ocorrência de ressurgência. Este é um fenômeno onde o vento, ao soprar paralelamente à costa (como os ventos de nordeste em Cabo Frio, Brasil, durante o verão), empurra a água da superfície para longe, permitindo que a água mais profunda, fria e extremamente rica em nutrientes, suba. Essa "fertilização" natural da superfície oceânica causa uma explosão na população de fitoplâncton, iniciando uma cascata de produtividade que sustenta toda a cadeia alimentar, culminando nos grandes predadores.

Sensor/Produto
Satélite(s)
O que mede
Relevância para o Modelo
ASCAT
MetOp-A/B/C
Vetores de Vento na Superfície
Permite prever a ocorrência de ressurgência (upwelling)



🔗 A Síntese Final: Unindo os Pontos para Encontrar os Tubarões
Nosso modelo integra esses três pilares de dados da NASA para criar um mapa dinâmico de probabilidade:

Ventos (ASCAT) ➡️ preveem a Ressurgência.

Ressurgência ➡️ traz Nutrientes à superfície.

Nutrientes + Luz Solar ➡️ causam a proliferação de Fitoplâncton (Clorofila-a / MODIS).

Fitoplâncton ➡️ atrai a Cadeia Alimentar (zooplâncton, peixes).

Frentes de Temperatura (SST / MODIS & VIIRS) ➡️ concentram as Presas.

Presas Concentradas + Zonas de Conforto Térmico ➡️ atraem os Tubarões 🦈🎯.

Ao combinar esses fatores, o Shark Sentinel não apenas prevê onde os tubarões estarão, mas entende por que eles estão lá, fornecendo uma ferramenta poderosa e cientificamente embasada para a conservação marinha e a segurança dos banhistas.

