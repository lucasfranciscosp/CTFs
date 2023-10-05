# Wave a flag

Neste challenge , como diz em uma na primeira dica "This program will only work in the webshell or another Linux computer", portanto eu recomendo usar a webshell que o próprio site fornece.

Com isso basta fazer seu login na webshell e usar o comando da segunda dica:
##### wget https://mercury.picoctf.net/static/b28b6021d6040b086c2226ebeb913bc2/warm
Com isto feito, agora conseguimos executar o programa com
##### ./warm
Ele irá te responder com uma mensagem que precisa de uma flag -h
Então faremos o que ele quer:
##### ./warm -h
E com isso conseguimos a nossa flag :D
