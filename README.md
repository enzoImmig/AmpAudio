# AmpAudio
 Etapa de um aplificador de audio classe D

    Conversao do sinal:
 Leitura do sinal de entrada através do AD
 Interpolação do valor do AD (12bits) para o valor do ARR para PWM (variavel com a frequencia)

    Atuador
 Leitura do Encoder incremental
 Controle de overflow
 Atuação no sinal modulado de saída