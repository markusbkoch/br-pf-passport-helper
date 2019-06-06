# Preenchimento automático do formulário de reagendamento de passaporte
Para fazer um passaporte brasileiro, é preciso agendar um horário para comparecimento a um posto da Polícia Federal (PF). Pode passar despercebido para a maioria das pessoas, mas é possível reagendar esse horário. E não é difícil conseguir **antecipá-lo**, pois ao longo do dia, novas vagas vão sendo abertas pela PF. Mas é preciso entrar periodicamente no site e preencher um [formulário](https://servicos.dpf.gov.br/sinpa/realizarReagendamento.do?dispatcher=exibirSolicitacaoReagendamento&validate=false) com CPF, número do protocolo e data de nascimento, para só então ter acesso aos novos horários disponíveis.  

Um incoveniente desse processo é que a PF desabilitou a função de autocomplete do formulário. Para não ter que preencher manualmente os dados, ou ficar alternando entre janelas para copiar e colá-los, criei um bookmarklet que faz o preenchimento automático.

No futuro se poderia pensar em evoluir esse código para também:
 * preencher o captcha (que o site passa a solicitar se a frequência de tentativas de reagendamento exceder um limite); e
 * selecionar automaticamente o posto de preferência
