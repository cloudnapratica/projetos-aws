## Detector de ações em uma conta da AWS

### Descrição

Como parte de um time de profissionais AWS, você recebeu a tarefa de desenvolver uma solução que detecta ações na sua conta da AWS e manda notificações via e-mail para o seu time.

O primeiro tipo de ação que deve ser monitorada é a criação de usuários IAM. Toda vez que alguém criar um usuário IAM, um e-mail deve ser enviado para o seu time com o seguinte formato:

```
Titulo do e-mail: Novo usuário IAM detectado na conta [ID_DA_CONTA]

Conteúdo do e-mail:
Um novo usuário IAM foi detectado na conta [ID_DA_CONTA].

Detalhes:
Nome: [NOME_DO_USUARIO_IAM]
Criado por: [NOME_DE_QUEM_CRIOU_O_USUARIO]

```

A solução deve ser desenvolvida de forma que o time possa fazer o _deploy_ em múltiplas contas da AWS de forma automatizada.
