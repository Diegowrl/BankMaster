# BankMaster

Boa tarde, este e o projeto de backEnd do banco master.
Foram utilizados os patterns de Mediator e CQRS no projeto zipado, foi realizado um projeto bem completo para mostrar alguns de meus conhecimentos.
Este projeto poderia ser realizado com apenas um project, mas gostaria de mostrar algo mas robusto e escalavel.
![image](https://github.com/user-attachments/assets/259aad1e-42aa-49b9-a8e5-364cdf9bf355)


Foram criadas 4 rotas de CRUD, e uma rota especifica de BFF aonde e realizada o calculo de melhor rota.

![image](https://github.com/user-attachments/assets/2344022b-cf7d-428e-a338-e43d3cbfac33)

Para realizar o calculo de melhor rota so preencher o body da requisição, não sendo necessario o valor.

![image](https://github.com/user-attachments/assets/c6eb2284-62ed-4a4e-8b0b-8c5c50e27d18)![image](https://github.com/user-attachments/assets/a3247241-d15c-4b6f-92f3-890168296db3)

Foi criado um BD Local dentro do proprio projeto para a realizaçao dos testes.
Ele se encontra na camada de Infrastructure na pasta database.
![image](https://github.com/user-attachments/assets/0706064e-3658-4db9-9e00-3217947e68ea)
![image](https://github.com/user-attachments/assets/dc9b8a2a-be05-4dd2-821b-2274e5babffb)

# Observações

Por motivo de tempo alguns items ficaram faltando da lista.
 - Foram realizados testes somente no command que e realizado o calculo, tenho ciencia que vereria ter realizado em todas e controllers e acrescentado logging em todas as etapas.
 - Validações no update dependendo da regra de negocio, como não foi passada nenhuma deixei em aberto.
 - O projeto de FrontEnd, tenho conhecimento para realizar mas não tive o tempo necessario.

Tenho alguns pontos interessantes sobre esse projeto, sera um bom ponto na nossa conversa na entrevista.
