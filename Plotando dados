import matplotlib.pyplot as plt
import numpy as np

# Dados para plotar
t = np.arange(0.0, 2.0, 0.01)
s = 1 + np.sin(2 * np.pi * t)

fig, ax = plt.subplots()
ax.plot(t, s)

ax.set(xlabel='time (s)', ylabel='voltage (mV)',
       title='Muito simples plotar um gráfico!')
ax.grid()

fig.savefig("teste.png")
plt.show()
