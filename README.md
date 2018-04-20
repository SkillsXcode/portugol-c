# Portugol-c

O projeto consiste na criação de um software em __linguagem C__ capaz de converter um algoritmo codificado em __Portugol-C__ (portugol adaptado de acordo com as características da linguagem c) para a linguagem C. Após a conversão o código é compilado e executado pelo próprio software.

## Pré-requisitos
O presente projeto é um programa em linguagem C que deve ser baixado e compilado na própria máquina. Além disso, o código resultante da tradução do portugol-c também resulta em um fonte em linguagem C. Por isto o pré-requisito inicial é que o sistema operacional possua o GCC instalado e configurado para sua utilizaço no terminal.

Este projeto foi concebido para ser utilizado em computadores com o __GNU-Linux__, preferencialmente com o editor __gedit__ instalado (onde conta inclusive com o código de cores, muito utilizado no desenvolvimento de software).

## Instalação

- Abra o terminal do linux (geralmente ctrl+alt+t).
- Instale o GCC (provavelmente já estará instalado) usando o comando: sudo apt-get install gcc
- Em seguida digite (ou copie e cole no terminal): wget https://raw.githubusercontent.com/flavio7co/portugol-c/master/instala-ptgc isto fará download do script de instalação.
- Depois execute o script da seguinte forma: . instala-ptgc (transcrição: ponto espaço instala-ptgc. O ponto garante que o script o levará para o diretório do ptgc onde estará o arquivo algoritmo.alg e elimina a necessidade de dar permissão de execução ao script).

Agora basta editar o arquivo algoritmo.alg, salvar e executar utilizando ./compila (pelo terminal, dentro do diretório do programa).

