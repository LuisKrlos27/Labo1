LABO 1


## 1. [Preguntas reflexivas de ambientacion](#) ✔

<ol type="a">
<li>¿Cual es la dirección de red y de broadcast de un host que tiene una ip 192.168.10.10/30?.
</li>

---
Para encontrar la dirección de red, necesitamos tomar los primeros 30 bits de la dirección IP y poner los bits restantes a 0. Luego, para encontrar la dirección de broadcast, ponemos esos mismos 30 bits en la dirección de red a 1, y los últimos 2 bits a 1.

Dado que tenemos la dirección IP 192.168.10.10/30:
<ol type = 1>
<li>
Convertimos la dirección IP a binario:

- Dirección IP: 192.168.10.10 -> 11000000.10101000.00001010.00001010
</li>
<li>
Tomamos los primeros 30 bits para la dirección de red y los ponemos a 0 para los bits restantes:

- Dirección de red: 11000000.10101000.00001010.00001000 -> 192.168.10.8

<li>
</li>Tomamos los primeros 30 bits para la dirección de broadcast y los ponemos a 1 para los bits restantes:

Dirección de broadcast: 11000000.10101000.00001010.00001111 -> 192.168.10.15
Entonces, para la dirección IP 192.168.10.10/30:

- Dirección de red: 192.168.10.8
- Dirección de broadcast: 192.168.10.15
</li>
</ol>
<li>¿Que información se puede inferir de un host con la dirección 169.254.255.200/26?.</li>
<li>¿Cuantas sub-redes puede lograr con la mascara 172.16.0.0/22?.</li>
<li>¿Cuantos clientes puede tener la sub red 172.16.0.0/22?.</li>
<li>¿Que clase y tipo de dirección es 10.10.10.0/24?.</li>
</ol>
