# Criacao_de_grafico
Criação de gráficos de linha com Plotly Express.

# Importando as bibliotecas
import plotly.express as px
import pandas as pd
import matplotlib.pyplot as plt
import numpy np
#
eixo_y = np.random.randint(low = 100, high = 5000, size = 50)
eixo_y
eixo_x = pd.date_range(start = '2021-1-1', freq = 'D', Pperiods = 50)
eixo_x
#
plt.figure(figsize = (8,5))
plt.plot(eixo_x, eixo_y)
plt.itle('Minha Familia')
plt.show()
<img src="https://user-images.githubusercontent.com/98922466/165171785-55f3c433-25a8-4910-b27d-f82dd01987e7.png" width="500px">

fig = px.line(x = eixo_x, y = eixo_y, tile = 'Minha Figura')

<div 
<align="center">
<img src="https://user-images.githubusercontent.com/98922466/165169727-c7bcfb1d-dd88-433c-8f1e-37300c5f986a.png" width="500px">
</div>
