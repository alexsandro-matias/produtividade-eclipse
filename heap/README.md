# Memória Heap
Esta memória responsável pela alocação de todos os objetos instanciados. Assim, pode ocorrer do IDE usar toda a memória e começar a comprometer o Sistema Operacional. Então, caso tenha uma máquina mais modesta, é possível reduzir essa memória que o sistema responda de forma mais satisfatória. Para mostrarmos em tempo real o valor desta memória, iremos em ``Windows -> Preferences -> General -> Show heap status (deixe marcado o checkbox).`` 
No botão da lixeira ao lado é possível "limpar" essa memória.



# Xms | Xmx
O eclipse por padrão (default) vem configurado para consumir um valor de memória mínimo e outro máximo utilizados pela JVM. Desta forma, estes valores serão utilizados como referência mesmo que a máquina possua um poder computacional melhor do que o necessário. Para configurar esses valores basta ir no arquivo de configuração chamado de ``eclipse.ini`` que fica localizado no mesmo diretório que o Eclipse foi instalado.
Quase no final do arquivo teremos:
- Xms256m
- Xmx2048m 
Ou seja, 256 MB para o mínimo, e 2 GB para o máximo. Para melhor aproveitamento, e para o meu caso, mudarei ambos os valores 4096m = 4 GB. Os valores de Xms e Xmx devem ser valores iguais para evitar problemas de paginação no projeto.