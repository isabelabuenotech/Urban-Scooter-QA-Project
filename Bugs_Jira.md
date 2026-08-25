# 🐛 Estrutura do reporte de Inconsistências e Bugs — Jira


ID JIRA: TPPF-7

CASO DE TESTE: Checagem da obrigatoriedade do sinal de adição (+) no campo "Telefone"

SEVERIDADE: Alta

STATUS: Aberto

ETAPAS DO TESTE:
```
1
Abra o aplicativo Urban Scooter

2	
Clique no botão "Fazer Pedido"

3	
O formulário "Para quem é a Scooter" abrirá na página

4	
Preencha o campo "Nome" com uma string válida

5	
Preencha o campo "Sobrenome" com uma string válida

6	
Preencha o campo "Endereço" com uma string válida

7	
Clique no campo "Estação de metrô"

8	
Selecione uma estação válida na lista "Estação de metrô"

9	
Clique no campo "Telefone: o entregador ligará para este número"

10	
Digite "12345678909"

11	
Remova o foco do campo "Telefone: o entregador ligará para este número" clicando fora dele.
```

AMBIENTES: Chrome 1280x720 e Opera 1280x720

RESULTADO ESPERADO: O campo "Telefone: o entregador ligará para este número" ficará destacado em vermelho e a seguinte mensagem de erro aparecerá abaixo do campo, também em vermelho: "Digite um número válido".

RESULTADO REAL: A string é aceita, o campo "Telefone: o entregador ligará para este número" não fica destacado e a mensagem de erro não aparece.


