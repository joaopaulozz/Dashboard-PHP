PAINEL SAC

O desenvolvimento do Painel surgiu da necessaidade do Setor do SAC ter uma ferramenta em que permite-se que os clientes a se cadastrarem online 24h por dia.

O painel é uma ponte que conecta um formulario Web(Wordpress) com o Logix(ERP Interno). O formulario sera de uso dos clientes para abertura do SAC(Serviço de atendimento ao consumidor). Quando o usuario enviar o formulario preenchido, ele esta fazendo um POST atraves de uma Api Rest(Python - Flask), que valida os dados que o cliente informiu, e insere no banco, tambem cria um cliente no BD se o CPF ainda não constar no BD, com total segurança, visando as medidas LGPD.

O Painel roda internamente e serve para consultar os dados do cliente e fazer n validações, e assim inserir o SAC no Logix.

Formulario Wordpress:
![form](https://user-images.githubusercontent.com/69809959/137145466-ed4d6428-fa67-4301-8b6a-2c12e998a864.PNG)

Tela de Login do Painel PHP:
![login](https://user-images.githubusercontent.com/69809959/137143684-c244215b-5131-405a-9b69-8ea15a434260.PNG)

Graficos:
![graficodepizza](https://user-images.githubusercontent.com/69809959/137181257-76a4a59c-e33a-4fe0-8bc9-d2b5befe4793.PNG)

![dashboard3](https://user-images.githubusercontent.com/69809959/137180952-e3eacd1f-7126-46c0-82b2-00a3839f9a8b.PNG)

OBS: Todos os dados das imagens são ilustrativos e fictícios, gerados apenas para demonstração do painel.
