#Relatório de Redes (TCP/IP) sobre VLANs

##Questões

### Seção 3.1

#### Questão 1

- Quantos domínios de broadcast existem na topologia criada na Seção 3.1?
	
	Depois de ter realizado os passos da Seção 3.1, a topologia criada possui apenas 1 domínio de broadcast. Como visto na figura, criamos apenas uma VLAN no switch (VLAN001), a qual abrange as 52 portas (GE1/0/1 - GE1/0/52).

	[q1]

#### Questão 2

- Apresente um log da execução do comando ping para o endereço do switch 1 (192.168.0.1) e aponte qual o valor médio observado para o RTT (Round Trip Time) do ping.
	
	O valor médio  observado para o RTT foi calculado pelo próprio comando ping. Assim, como pode ser visto na figura, em média os pacotes demoraram 1.972 segundos.


#### Questão 3

- Apresente os log de execução do comando ping para os endereços de duas bancadas sendo utilizadas no laboratório e aponte qual o valor médio observado para o RTT (Round Trip Time) do ping para cada uma das estações.
	
	olha na imagem professor.


#### Questão 4

- Abra a ferramenta wireshark utilizando o comando sudo wireshark no
terminal da sua máquina virtual e ative a captura de pacotes na interface eth0. Na sequência, solicite que um dos colegas de seu grupo, utilizando outra bancada do seu grupo, dispare comandos ping para os endereços IP do seu grupo, porém substituindo a parte final do endereço IP por 2XX. Por exemplo, se o grupo possui a bancada 8, configurada com o endereço IP 192.168.0.108, o colega deverá efetuar
ping para o endereço 192.168.0.208. Apresente um log do wireshark que
demonstra a recepção destas requisições ARP.


### Seção 3.2

#### Questão 5

- Quantos domínios de broadcast existem na topologia criada na Seção 3.2?
	
	Depois de ter realizado os passos da seção 3.2, e considerando que o laboratório foi especificado para 6 grupos e cada grupo criou uma VLAN, temos entao no total 7 VLANs criadas

#### Questão 6

- Apresente um log da execução do comando ping entre as duas bancadas do grupo que fazem parte da nova VLAN e aponte qual o valor médio observado para o RTT (Round Trip Time) do ping.
	
	olha a imagem FDP



#### Questão 7

- Apresente um log da execução do comando ping a partir de uma bancada do grupo para uma bancada de outro grupo. Por que não há alcançabilidade entre as bancadas?
	
	Porque elas estão em VLANs diferentes.



### Seção 3.3

#### Questão 8

- Quantos domínios de broadcast existem na topologia criada na Seção 3.3?
	
	Na seção 3.3 fizemos modificações no switch 2; criamos as mesmas VLANs que criamos no switch 1. Assim, nessa topologia, também existem 7 domínios broadcast.


#### Questão 9

- Apresente um log da execução do comando ping entre as duas bancadas do grupo que fazem parte da nova VLAN segmentada fisicamente e aponte qual o valor médio observado para o RTT (Round Trip Time) do ping.


#### Questão 10

- Apresente um log da execução do comando ping a partir de uma bancada do grupo para uma bancada de outro grupo. Por que não há alcançabilidade entre as bancadas?

### Seção 3.4

#### Questão 11

- Quantos domínios de broadcast existem na topologia criada na Seção 3.4?
	
	2

#### Questão 12

- Apresente um log da execução do comando ping entre duas bancadas quaisquer do grupo e aponte qual o valor médio observado para o RTT (Round Trip Time) do ping.


#### Questão 13

- Apresente um log da execução do comando ping a partir de uma bancada do grupo para uma bancada de outro grupo. Por que agora há alcançabilidades entre as bancadas?


[q1]: img/IMG_1654.JPG