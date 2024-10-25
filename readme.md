
# Registro de Pontos

Este projeto é um script Bash simples para fins de estudos que permite registrar entradas e saídas de ponto de trabalho em um arquivo de texto. O script usa a ferramenta `dialog` para criar uma interface interativa para o usuário.


## Funcionalidades

- **Registrar Entrada**: Registra o horário de entrada com base no horário atual.
- **Registrar Saída**: Registra o horário de saida com base no horário atual.
- **Gerar Relatório**: Exibe um relatório com as entradas e saídas de um dia específico ou de todos os registros, caso nenhuma data seja informada.


## Pré-requisitos

Para executar este script, você precisa:

- **Sistema Operacional**: Linux ou outro sistema compatível com Bash.
- **Dialog**: Este script usa a ferramenta `dialog` para criar a interface gráfica no terminal. Instale com o comando:
  ```bash
  sudo apt-get install dialog

## Como executar

Clone o repositorio para sua maquina local
```
git clone https://github.com/ViniciusWessner/Registro-de-Pontos.git
cd Registro-de-Pontos
```

De permissão ao script
```
chmod +x registro_ponto.sh
```
Execuite o script
```
./registro_ponto.sh
```

## Estrutura do Arquivo de logs
Todos os registros são salvos no arquivo bd.txt no seguinte formato:

```
YYYY-MM-DD:Tipo:HH:MM
```
Exemplo:

```
2024-10-24:Entrada:08:30
2024-10-24:Saída:17:45
```


Histórico de Versões
 - v1.0 - Criação do script com registro de entrada e saída.
 - v1.1 - Adição de interface com dialog.
 - v1.2 - Adição da função de relatório.

# Capturas de Tela

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <img src="https://github.com/ViniciusWessner/Registro-de-Pontos/blob/main/assets/menu.png?raw=true" alt="Menu" width="300">
    <img src="https://github.com/ViniciusWessner/Registro-de-Pontos/blob/main/assets/entrada.png?raw=true" alt="Entrada" width="300">
    <img src="https://github.com/ViniciusWessner/Registro-de-Pontos/blob/main/assets/saida.png?raw=true" alt="Saida" width="300">
    <img src="https://github.com/ViniciusWessner/Registro-de-Pontos/blob/main/assets/relatorio1.png?raw=true" alt="Filtro de Data" width="300">
    <img src="https://github.com/ViniciusWessner/Registro-de-Pontos/blob/main/assets/relatorio2.png?raw=true" alt="Relatório" width="300">
</div>

