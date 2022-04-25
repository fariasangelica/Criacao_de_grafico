# Criacao_de_grafico
Criação de gráficos de linha com Plotly Express.

# Importando as bibliotecas
import plotly.express as px
import pandas as pd
import matplotlib.pyplot as plt
import numpy np

eixo_y = np.random.randint(low = 100, high = 5000, size = 50)
eixo_y
eixo_x = pd.date_range(start = '2021-1-1', freq = 'D', Pperiods = 50)
eixo_x

plt.figure(figsize = (8,5))
plt.plot(eixo_x, eixo_y)
plt.itle('Minha Familia')
plt.show()

fig = px.line(x = eixo_x, y = eixo_y, tile = 'Minha Figura')
