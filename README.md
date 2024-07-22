# Containers

## 01. Nomeando Containers

1.1 Listando os containers, no prompt de comando com o docker aberto em execução, utilizar o comando docker ps

- Lista de containeirs atualmente em execução na maquina.

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/01_Lista_Containers.png">

1.2 Criando um conteiner, a partir de uma imagem (em backgound) com um nome especifico.

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/02_Nomeando_Conteiners.png">

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/03_Container_Criado.png">

## 02. Verificando o log de eventos

2.1 - Verificando as opções para analisar logs de conteiners

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/04_Logs_Containers.png">

2.2 - Utilizando a opção -f

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/05_docker_logs_F.png">

2.3 - Utilizando o timestamp para verificar os logs

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/06_docker_logs_t.png">

## 03. Publicando portas de acesso.

3.1 - Mapeando Portas

- Comando para realizar o mapeamento de portas (Tudo que chegar na porta 80 do pc será redirecionado para a porta 3000 do docker).

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/07_Mapeando_Portas.png">

- Aplicação em execução

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/08_Acessando_Aplicacao.png">

- Conteiner criado com o nome incluido.

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/09_App_Map_Ports.png">

- Verificando as portas do conteiner por comando.

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/10_Docker_ps_MapPorts.png">

## 04. Executando comandos em containers

4.1 - Verificando os arquivos dentro do conteiner, a partir do terminal da máquina.

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/11_Comandos_ls.png">

<b>Observação:</b> Utilizar sempre o docker exec nome_do_conteiner e o comando.

## 05. Iniciando e parando containers

5.1 Parando um conteiner que está em execução.

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/12_Docker_Stop.png">

5.2 Iniciando um conteiner que está parado.

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/13_Docker_Start.png">

## 06. Removendo Containers

<img src="https://github.com/JosiTubaroski/Docker_Containers/blob/main/img/14_Docker_Rm.png">
















