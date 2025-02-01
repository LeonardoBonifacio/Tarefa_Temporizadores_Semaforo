
# Tarefa5 U4: Simulação de um semáforo digital utilizando 3 leds e a raspberry pico w

### Descrição do Projeto
Este projeto implementa a logica de um sinal de transito em que os leds são acesos com 3 segundos de diferença entre vermelho,amarelo e verde, utilizando um temporizador repetitivo que apaga todos os leds de 3 em 3 segundos e baseado na variavel 'estado' o led correto é acesso. A cada segundo é printado no terminal "sinaleira funcionando", se o led vermelho está acesso é printado "Sinal fechado", se o led amarelo está acesso é printado "Sinal abrindo ou vai freiando" e se o led verde está acesso é printado "sinal aberto"

OBS: O primeiro led(vermelho) so acenderá na primeira vez após 3 segundos e não de imediato logo após rodar o código.


### Instruções de uso

Para rodar este código é necessário:

ter o arquivo .c e ter arquivo do cmakelist em uma pasta para que você os possa transformar em um projeto utilizando a extensão da raspberry pi pico

Você pode rodar ele :

Tanto na sua BitDogLab(mudando os pinos do leds para vermelho == 13, amarelo == 13 e 11(liga os dois leds) e verde == 11)")

Ou através da extensão wokwi pelo vs code, tendo os arquivos diagram.json  e o wokwi.toml preenchidos.

