# Raiz-Quadrada
## Função que calcula raiz quadrada no Python

def sqrt(x):
	u_tentativa = x/2.0
	while True:
  	tentativa = (u_tentativa + x/u_tentativa)/2
    if abs(tentativa - u_tentativa) < .000001: # example de precisão
    	return tentativa
    u_tentativa = tentativa
