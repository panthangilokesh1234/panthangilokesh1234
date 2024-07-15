# @title Default title text
import numpy as np
import matplotlib.pyplot as plt


def temperature_calculate_hardcoded(time):
    a = float(input("enter the value of a"))
    b = float(input("enter the value of b"))
    c = float(input("enter the vale  of c"))

    temperature = a * time**2 + b * time + c
    return temperature


time = np.linspace(1, 10, 50)
temperatures = temperature_calculate_hardcoded(time)

plt.plot(time,
         temperatures,
         label='Weather Modelling using Quadratic Hard-coded Coefficients')
plt.xlabel('Time')
plt.ylabel('Temperatures')
plt.grid(True)
plt.title('Hard-coded Quadratic Temperature Model')
plt.legend()
plt.show()
- 👋 Hi, I’m @panthangilokesh1234
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
panthangilokesh1234/panthangilokesh1234 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
