# BlinkIt Dashboard
*Dashboard de 1 página. 4 KPI's e 7 regras de negocio atendidas.*

<img width="1392" height="767" alt="image" src="https://github.com/user-attachments/assets/e46b1ce9-c450-4a74-bfc0-a894c0a41a7e" />

Este dashboard foi desenvolvido em PowerBI, utilizando uma base de dados pública da empresa indiana de comércio alimentício, a BlinkIt.

### Dados
Os dados utilizados são de uma única fonte, com o schema deles da seguinte forma:

- *Item Fat Content*: Conteúdo de Gordura do Item.
- *Item Identifier*: Identificador do Item.
- *Item type*: Tipo do Item.
-  *Item Visibility*: Visibilidade do Item (ou procura pelo item).
-  *Item Weight*: Peso do Item.
-  *Outlet Establishment Year*: Ano de criação da loja.
-  *Outlet Identifier*: Identificador da loja.
-  *Outlet Location Type*: Categoria de localização da loja.
-  *Outlet Size*: Tamanho da loja.
-  *Outlet Type*: Tipo da loja.
-  *Rating*: Nota (Avaliação dos Clientes).
-  *Sales*: Vendas.

### Medidas

As medidas utilizadas para os cálculos estão dentro da pasta `measures`

### Parametros das Medidas

Foi utilizado a ferramenta de criação de parâmetros para que alguns gráficos pudessem ser 
analisados de acordo com os KPI's.

<img width="339" height="26" alt="image" src="https://github.com/user-attachments/assets/524eb36e-4edd-4802-94f0-1118b9567b5e" />


#### KPI's:
1. Vendas totais
2. Média de Vendas
3. Número de Itens Vendidos.
4. Média de Nota.

<img width="364" height="150" alt="image" src="https://github.com/user-attachments/assets/4dd5219c-793f-4bc6-aa80-c3f80c06dbb2" />

#### Análise Granular:

##### 1. Vendas Totais por Conteúdo de Gordura:
       Analisar o impacto do percentual de gordura em relação ao total de vendas.
       Verificar como outros KPI's (Média de Vendas, Items Vendidos e Média de Notas) variam com o conteúdo de gordura.
##### 2. Vendas Totais por Tipo de Item:
       Identificar a performance de diferentes tipos de itens em relação ao total de vendas.
##### 3. Conteúdo de Gordura segmentando Loja por Vendas Totais:
       Comparar o total de vendas em diferentes lojas, segmentados por conteúdo de gordura.
       
<img width="360" height="321" alt="image" src="https://github.com/user-attachments/assets/631cf8d1-9665-4df2-ae59-b364299ec320" />
       
##### 4. Total de Vendas por Idade da Loja:
       Verificar se a idade da loja influencia o total de vendas.
       
<img width="397" height="187" alt="image" src="https://github.com/user-attachments/assets/cd259d74-02e7-4237-9b79-417a164709da" />

#### Regras de Negócio

##### 5. Percentual de Vendas pelo tamanho da loja:
       Analisar a correlaçao entre tamanho da loja e total de vendas.

<img width="188" height="149" alt="image" src="https://github.com/user-attachments/assets/6b988e5f-c4b2-4c26-aed2-ee0a36f9ef56" />
    
##### 6. Vendas pela Localização da Loja:
       Verificar a venda das lojas dentro dos tipos de localização das lojas.

<img width="206" height="141" alt="image" src="https://github.com/user-attachments/assets/b5278e73-461b-49f5-abed-ed7523b4e78c" />
  
##### 7. Todas as Métricas pelo Tipo de Loja
       Verificar todas as métricas segmentadas por diferentes tipos de lojas.

<img width="394" height="139" alt="image" src="https://github.com/user-attachments/assets/d906672c-abd3-4c29-8910-4c62333a5e08" />


### Conclusão

- Supermarket Type1 é disparado o principal formato, tanto em faturamento quanto em volume.
- Type2 tem o melhor Média de Vendas, mas por pouca diferença
- Média de Nota é praticamente igual entre todos
- A diferença entre tipos de loja está muito mais em escala e volume do que em ticket médio ou nota.

As vendas são puxadas principalmente por itens Regular, categorias como Fruits and Vegetables e Snack Foods, lojas maiores, em Tier 3, e principalmente pelo formato Supermarket Type1. O ticket médio e a avaliação variam pouco entre segmentos; o que realmente explica as diferenças de faturamento é o volume vendido e a escala da operação.
       
       
