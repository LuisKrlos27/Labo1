LABO 1


## 1. [Preguntas reflexivas de ambientacion](#) ✔

<ol type="a">
<li>¿Cual es la dirección de red y de broadcast de un host que tiene una ip 192.168.10.10/30?.</li>

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

---
<li>¿Que información se puede inferir de un host con la dirección 169.254.255.200/26?.</li>

---

 la dirección IP 169.254.255.200/26 indica que el host está tratando de configurar automáticamente una dirección IP en un enlace local debido a la falta de una asignación de IP válida a través de DHCP u otras configuraciones manuales. Esta práctica es común en situaciones en las que un dispositivo necesita comunicarse en una red local, pero no puede obtener una dirección IP válida de otros medios.

---
<li>¿Cuantas sub-redes puede lograr con la mascara 172.16.0.0/22?

---

la máscara de subred /22 significa que los primeros 22 bits están reservados para la parte de red, y los 10 bits restantes son para la parte de host.

Para calcular el número de subredes posibles, podemos utilizar la fórmula 2^n, donde "n" es el número de bits de host que tenemos disponibles. En este caso, tenemos 10 bits para hosts.

2^10 = 1024

Por lo tanto, con la máscara de subred 172.16.0.0/22, puedes lograr un total de 1024 subredes posibles. Cada una de estas subredes tendría un rango de direcciones IP disponibles para asignar a los dispositivos conectados a ellas.

---
</li>
<li>¿Cuantos clientes puede tener la sub red 172.16.0.0/22?

---

Teniendo en cuenta lo dicho anteriormente la cantidad de sub-redes calculadas son 1024.

- Dirección de red: 172.16.0.0
- Rango de direcciones IP utilizables: 172.16.0.1 a 172.16.3.254
- Dirección de broadcast: 172.16.3.255

Por lo tanto, en la subred 172.16.0.0/22, puedes tener hasta 1024 - 2 = 1022 clientes únicos utilizando direcciones IP dentro del rango de direcciones IP utilizables.
</li>

---

<li>¿Que clase y tipo de dirección es 10.10.10.0/24?

---
La dirección IP 10.10.10.0/24 pertenece al rango privado de direcciones IP clase A.


</li>
</ol>

## [Caracterización de los adaptadores ✔](#)

|Parámetro||Valor|
|--|:--:|--:|
|Número de adaptadores Físicos|-->|2|
|Número de adaptadores Virtuales|-->|1|
|Tipo de Adaptador principal|-->|Wi-fi|
|Fabricante del Adaptador principal|-->|Dual Band Wireless-AC 8265|
|Código MAC del fabricante|-->|3C-A0-67|
|MAC|-->|F8-E4-3B-03-5F-4E|

