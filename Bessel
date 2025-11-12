import numpy as np
import matplotlib.pyplot as plt
from scipy.special import jn # jn(n, x) es J_n(x)


x = np.linspace(0, 10, 500)

ordenes = [0]

plt.figure(figsize=(12, 8))

for n in ordenes:
    plt.plot(x, jn(n, x), label=f'$J_{n}(x)$')


plt.title('Funciones de Bessel', fontsize=20)
plt.xlabel('$x$', fontsize=15)
plt.ylabel('$J_n(x)$', fontsize=15)
plt.legend(fontsize=12)
plt.grid(True, linestyle='--', alpha=0.5)
plt.axhline(0, color='black', linewidth=0.5)
plt.ylim(-0.5, 1.1)
plt.show()
