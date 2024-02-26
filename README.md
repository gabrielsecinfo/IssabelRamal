# IssabelRamal
    Implementação do Ramal Virtual no Issabel desempenha um papel fundamental na expansão das capacidades de comunicação do sistema.
    Este guia fornece uma orientação passo a passo para instalar e configurar eficientemente um ramal virtual, otimizando a operação do Issabel PBX


#INTRODUÇÃO; 
Nessa atividade iremos criar uma máquina virtual para a instalação do 
sistema operacional do issabel e configurar esse ambiente, após isso iremos 
acessar o issabel pelo browser e configurar dois ramais com isso deveremos baixar 
um software sip que consiga receber chamada e ligar, assim iremos baixar um 
software no celular por exemplo e configurar-lo desse jeito podendo ligar para o 
computador ou ao contrário.

1. INSTALAÇÃO DO AMBIENTE;
Realizando a instalação do ambiente virtualizado do ISSABEL, aqui iremos inser o 
nome da VM(VIRTUAL MACHINE) a pasta de locação, ISO (IMAGEM DO 
SISTEMA) e o tipo do sistema

<img src="issabel/image1.png"/>

Nessa parte é para definir a quantidade de ram e cpu virtuais que deseja

<img src="issabel/image2.png"/>

`Tamanho do disco;

<img src="issabel/image3.png"/>
Depois de realizar a instalação da VM iremos colocar a rede dela no modo BRIDGE

<img src="issabel/image4.png"/>

Logo após iremos iniciar a virtual machine e logo após iremos instalar a imagem 
ISSABEL;

<img src="issabel/image5.png"/>
Seleciona o idioma da instalação:
<img src="issabel/image6.png"/>

Nessa parte do resumo de instalação a menus obrigatórios a ser configurados.

<img src="issabel/image7.png"/>

Seleção de software;


<img src="issabel/image8.png"/>
Seleção de destinação da instalação;
<img src="issabel/image9.png"/>

Aqui iremos selecionar para configurar a senha raiz ou a criação de usuário:
<img src="issabel/image10.png"/>

Configuração de senha;
<img src="issabel/image11.png"/>

Logo após você irá colocar uma nova senha;

<img src="issabel/image12.png"/>

Depois uma senha para o IssabelPBX (admin)

Nessa parte é para realizar o login com o usuário root e sua senha com isso você irá 
obter o IP do issabel;

<img src="issabel/image13.png"/>

2. CONFIGURAÇÃO;

Logo após obter o IP do Issabel, você irá colocar o ip no browser e pesquisar, vai 
entrar no site da issabel e nisso você irá entrar com o usuário admin e sua senha.

<img src="issabel/image14.png"/>

Nisso irá abrir o site da issabel.


<img src="issabel/image15.png"/>

Vamos configurar o PABX começando indo pelo PABX configuration logo após add 
extension e depois submit

<img src="issabel/image16.png"/>

Configuração do primeiro ramal:

<img src="issabel/image17.png"/>

Logo após ir em submit e depois em apply changes;
<img src="issabel/image18.png"/>

Depois iremos criar o segundo ramal

<img src="issabel/image19.png"/>
No dashboard mostra os dois ramais não registrados;
<img src="issabel/image20.png"/>

3. Ambiente em funcionamento;
Configuração do Microsip;

<img src="issabel/image21.png"/>

Ligando para o celular;

<img src="issabel/image22.png"/>

Chamada no celular;


<img src="issabel/image23.png"/>


3CX SOFTPHONE;

<img src="issabel/image24.png"/>

CELULAR;
<img src="issabel/image25.png"/>
OBS: A configuração do ramal no celular pelo sipdroid é o mesmo porém só altera o número. 


