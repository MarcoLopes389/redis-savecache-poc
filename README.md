#Criando Pod Redis

Para criar o pod corretamente, execute o apply do configmap primeiro, depois execute o apply do volume e do volumeClaim, repectivamente.
Por fim, execute o apply do redis.
Dê um exec e adicione uma chave com o redis-cli, depois entrando no bash do pod é possível ver os dois arquivos, appendonly e dump.
Apague o Pod do Redis e depois recrie, se entrar é possível ver os arquivos dentro.