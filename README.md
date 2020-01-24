# Bueiro+ inteligente
Aplicação de Iot com a framework Qt, a  e o microcontrolador ESP8266.

## O que é o Bueiro+ inteligente?

  Nos períodos de chuva,o escoamento da água nas ruas se torna uma problema, devido a falta de conscientização e má gestão da sociedade em relação ao descarte irregular do lixo, o que resulta na obstrução dos bueiros das cidades, aumentando o risco de alagamentos e enchentes.
  Por este motivo, em algumas cidades foram colocados uma espécie de rede nos bueiros, onde o lixo fica retido até que a coleta o recolha. Porém, hoje, o conceito 'Internet das coisas' nos possibilita conectar dispositivos de sistemas e serviços ao favor da humanidade. Com isso, surgiu o Bueiro+ Inteligente, o qual além da rede que retém os resíduos, ele contém um monitoramento através de sensores de carga e nível, ligados na Web para que juntos, emitam um sinal do tempo adequado e específico de cada bueiro, quando o mesmo estiver no seu cheio.

![LOGO](https://github.com/vanessadaluz6/bueiro_mais_inteligente/blob/master/fotos-bueirofofo/logo.png)

## Manual do Usuário

### Como Funciona o Bueiro+ inteligente?

#### Monitoramento

O site permite que o usuário tenha acesso remoto, apenas sendo necessário conexão com a internet.

### Informações técnicas


#### Materiais 

- [ESP8266](https://cdn-shop.adafruit.com/product-files/2471/0A-ESP8266__Datasheet__EN_v4.3.pdf)
- Sensor de Carga 50kg
- Sensor Ultrasonico HY-SRF05

#### O Circuito


#### A Página Web

A página web está hospedada gratuitamente no Heroku, uma plataforma cloud que permite o deploy de aplicações para desenvolvedores. Foi utilizado HTML e CSS, para poder organizar o site, como também Python, para reagir à eventos e fazer a comunicação com o software para computador e para a ESP8266. É notável indicar a importância da biblioteca Flask feita pela comunidade do Python, que é bastante crítica para a realização da comunicação e o deploy do servidor. 
