# Simu5G-tutorial-de-simulacao
Tutorial de como fazer simulações iniciais no Simu5G usando Linux. Tutorial desenvolvido colaborativamente como parte da avaliação da matéria MAC0463 do IME-USP no 2osem/2021.

# Introdução ao 5G

A cada geração de redes móveis, importantes avanços são feitos e novas possibilidades surgem. A chegada da rede móvel de quinta geração é um importante passo para muitas aplicações que exigem uma **baixa latência** e uma **banda maior** do que as soluções baseadas em LTE. Dessa forma é importante entender mais sobre essa rede que em breve vai fazer parte do nosso dia a dia, e ainda, entender suas principais limitações e desafios.

Simuladores são um ótimo jeito de se testar novas tecnologias para prever como elas poderiam se comportar no mundo real e identificar possíveis problemas e soluções. **O Simu5G é um simulador novo baseado no OMNET++ e INET**, que possibilita simulações de uma rede 5G NR (New Radio) e que possui fácil utilização e análise dos resultados.



---------------------

# Simu5G

## A. Instalação do Simu5G

1. **Baixar**

   Para realizar a instalação do Simu5G, basta acessar o site:

   http://simu5g.org/simu5g-pnp.html

   e clicar na opção de download do [Simu5G PnP](https://unipiit-my.sharepoint.com/:u:/g/personal/a018358_unipi_it/EdHpWTI7LGFLjnaUf6qwEaYBa30v5lrt5qF2uoxJPqn5tg?e=wrgT0f). 

2. **Criar ambiente virtual / Virtual Machine**

   Após o download, é necessário que o usuário instale um ambiente de virtualização (como o [Oracle VM VirtualBox](https://www.virtualbox.org/)) para rodá-lo.
   
   Importe a imagem do Simu5G no ambiente de virtualização.



## B. Inicialização

1. Após a importação da imagem da VM do Simu5G no ambiente de virtualização, clique para iniciá-la.

2. Na tela inicial, clique do ícone do OMNet++ Open Simulator na aba de tarefas — esse é o software necessário para rodar as simulações. 

3. Já com o OMNet++ aberto, clique na pasta ‘simu5G’ do Project Explorer.
4. Dentro da pasta, siga clicando na sequência: simulations > NR. Na pasta NR, há uma gama de opções que se pode escolher para rodar uma simulação (com exceção das opções ‘cars’ e ‘bgTraffic’).



## C. Primeira Simulação

A tela de simulação é aberta após clicarmos no botão de Run na barra de tarefas, ao se selecionar o arquivo ‘omnetpp.ini’ da simulação desejada. 

Dentro da tela de simulação há algumas opções — simulação rápida (com o botão >>>), simulação em tempo real (botão > na barra de tarefas), etc. 

Após simulada a rede 5G, a pasta ‘results’ será criada dentro do diretório do experimento simulado. Essa pasta contém os dados da simulação, podendo-se gerar gráficos a partir desses dados

Obs: (no momento em que testamos, um problema de versão impossibilitou a criação dos gráficos por inconsistência em uma biblioteca do OMNet++). 



## D. Alterando parâmetros da simulação

Caso seja interessante, pode-se fazer a simulação com novos parâmetros — o usuário deve clicar no arquivo ‘omentpp.ini’ e selecionar a aba ‘Form’ logo abaixo da tela de edição de texto. Dentro de ‘Configuration’, o usuário deve clicar em ‘Parameters’, podendo, assim, alterar os valores das variáveis.

Assim feito, o arquivo ‘omentpp.ini’ está pronto para ser usado com novos parâmetros de simulação.



---------------------------

# Outros simuladores 5G

- Simu5G PnP - http://simu5g.org/simu5g-pnp.html
- Simu5G-Cars Pnp - http://simu5g.org/simu5g-pnp.html
- 5G-LENA - https://apps.nsnam.org/app/nr/
- mmWave - https://apps.nsnam.org/app/mmwave/
- NetSim - https://netsim.boson.com/
- 5G-air-simulator - https://telematics.poliba.it/5G-air-simulator
- UERANSIM - https://github.com/aligungr/UERANSIM
- pysim5g - https://github.com/edwardoughton/pysim5g
- 4G/5G/Satellite Wireless Network Simulator - https://github.com/trunk96/wireless-network-simulator
- free5GC - https://github.com/free5gc/free5gc
- my5G-RANTester - https://github.com/my5G/my5G-RANTester



----------------------------

# Colaboradores

Julia Leite, @JuliaLeite

Lara Ayumi Nagamatsu, @lurara

Lucy Anne de Omena Evangelista, @lune-omena

Nathan Nunes, @naythanN



Contribua com o repositório também!