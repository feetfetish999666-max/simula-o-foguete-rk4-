## 📊 Resultados

### Altitude ao longo do tempo
![Altitude](docs/altitude_example.png)

### Velocidade ao longo do tempo
![Velocidade](docs/velocity_example.png)
import matplotlib.pyplot as plt

t = [0, 1, 2, 3]
h = [0, 10, 18, 25]

plt.plot(t, h)          # plota os pontos (t, h)
plt.xlabel("Tempo (s)") # nome do eixo X
plt.ylabel("Altura (m)")# nome do eixo Y
plt.title("Altura do foguete ao longo do tempo")
plt.show()
