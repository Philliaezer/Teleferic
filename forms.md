https://docs.google.com/forms/d/e/1FAIpQLScc1zG8NAOaa9-18gliFhE8muj9gdz76mXnSN4UHCqgSskhEA/viewform

https://forms.gle/36p6ssU2mhdYEDwKA

https://docs.google.com/forms/d/e/1FAIpQLSexEyUJqr0slkhqeEjxL-9CyEv_Db2FhZpzQ8Xlw9L3oosNrw/viewform?usp=header

# Informaçoes Bradesco
> Importante: Quando possivel, enviar para email teleperformance para devida anotação

- [ ] Central Transacional: registros do Atendimento Fone Fácil ( 40020022) na conta corrente - que, no nosso caso, deveriam ter sido registradas no SAC Cartão de Crédito - como não são especialistas em cartão de crédito por falta de alçada - afinal, é justamente por isso eles registram em SACL, por não terem alçada.
- [ ] Canais são "portas de entrada" por onde uma reclamação no SACL pode ser registrada. Central Transacional é uma, assim como Não me pertube também (sempre que o cliente cadastra o telefone do bradesco no não me pertube, nós é que devemos fazer a tratativa)
- [ ] Canais (portas de entrada) para nós, massificados backoffice: Carta, Agência, Telefones, Imprensa, Não Me Pertube, Defensoria Bradesco
- [ ] Atendimentos
  - Fone Fácil: Consultas e serviços transacionais. 
  - Alô Bradesco (0800 704 8383): Reclamações. 
  - SAC Cartão de crédito (0800 727 9988)
- [ ] Prazo TP (48h) Bradesco (3 dias - 7 dias LEI)

Outras coisas a anotar
- CIP -> CÂMARA INTERBANCÁRIA DE PAGAMENTO

Dicas:
- Coloque esses excels (filas/tarefas, emails, codigos, pdfs/xls da beedoo etc.) no email SISTEMAS BRADESCO e no Microsoft Teams




















Tarefas do Service View

http://tpbradesco.beedoo.io/wiki/466972/controversia

DETALHAMENTO DAS CATEGORIAS DE CONTROVÉRSIA > CANCELAMENTO DE COMPRA ou MERCADORIA NÃO RECEBIDA

RC157 – CONTEST DESPESA NACIONAL – INTERC DE CONTROVERSIA. 

RC159 – CONTEST DE DESPESA INTERN – INTEC DE CONTROVERSIA. 



https://tpbradesco.beedoo.io/wiki/470719/devolucao-saldo-credor

DUPLICIDADE DE PAGAMENTO DEVIDO ERRO SISTÊMICO 

Abrir fila no turbina BM012 - TRANSF SALDO CREDOR - CONTA CORRENTE; 

NÃO CONSTA SALDO CREDOR

Se o cartão não estiver mais credor, devido às transações terem abatido no crédito, e o cliente insistir no reembolso total do valor (do saldo credor), abrir a tarefa para monetário verificar a possibilidade de reembolso.  

Abrir fila BM012 - TRANSF SALDO CREDOR - CONTA CORRENTE;
CLIENTE NÃO CORRENTISTA > Na abertura da fila BM012 na situação de transferência do saldo para outro banco informar no registro da tarefa o código do banco e não apenas o nome, consulte a planilha abaixo para ver os códigos.

BM011 - TRANSFERENCIA DE SALDO CREDOR - ENTRE CARTOES.

RC348 - VERIFICAR CREDITO VOUCHER 

Tarefa: BM547 DEVOLUCAO SALDO CREDOR - CARTÃO ATIVO CANC SRV 



https://tpbradesco.beedoo.io/wiki/467080/fraude

Se constar no histórico o registro das tarefas: EC001 ou IT344 - RESPOSTA DE PARECER DEFINITIVO, significa que não haverá mais exceção para o tratamento da contestação. Porém se no registro do cartão não houver parecer definitivo do time de exceção, devemos abrir fila para reanalise. 

 

 - RC016 – Contestação Despesa Nacional: Despesa Nacional; 

 - RC056 – Contestação Despesa Internacional: Despesa Internacional. 

Se o cliente tiver diversas compras ou se for necessário complementar a abertura da fila, a primeira fila deve ser aberta conforme o tipo de compra e os demais complementos devem ser feitos com a tarefa RC000.



RE015 – ANALISE EXCEÇÃO



Verificar no histórico do Service View, se consta a resposta do time de exceção. A avaliação é registrada no histórico do Service View como “Parecer Definitivo”. E para assegurar este processo, são registradas as tarefas EC001, área de exceção ou IT344 pelo intercâmbio FIS, para que outras áreas tenham facilidade em localizar a informação no histórico. 



RC546 - MANIFESTACOES CANAL DE EXCECAO 

Incluir na tarefa: Cliente não reconhece a despesa no Estabelecimento xx, data xx/xx/xx, no valor de R$xxx. Suspeita do Golpe Cesárea. 

 -BM029 – AJUSTES DE ENCARGOS - CHEQUE ESPECIAL 

O Time de Backoffice Intercâmbio irá abrir tarefa IT452 - DEV.DE ERRO CARTÃO NÃO FOI CANC.MANIFESTAÇÃO para a situação abaixo: 



Tarefas de Contestação



O APP irá avaliar o tipo da despesa, prazo da bandeira e motivo da contestação para seguir ou não com o crédito e abertura de fila para tratamento conforme abaixo: 

Tarefa 

Descrição 

APP01 

CONTESTACAO PERDA / ROUBO COM SEGURO 

APP02 

NAO RECONHECIMENTO DE COMPRA RECUPERACAO - BO 

APP03 

CONTESTACAO DESPESA COM CHIP / SENHA E SEGURA 

APP04 

RECONHECIMENTO DE COMPRA - FRAUDE/ BACKOFFICE 



https://tpbradesco.beedoo.io/wiki/467355/parcelamento-de-fatura-parcelado-comum-parcelado-facil

RC095 – Estorno de Despesa Segura – Exceção

RC000 – INFORMAÇÕES GERAIS - RECLAMAÇÕES 

Abra tarefa - BM013 - PARCELAMENTO DE FATURA - com todas as informações acordadas durante o contato: (valor de adesão, quantidade e valor das parcelas) e solicitar a formalização do parcelamento. 

Registre Tarefa Informativo: RC525 - Parcelamento de Fatura Fácil - Aceitou 

Registro: (sem complemento) 

arefa Demais cartões: RC223 ANTECIPAÇÃO TOTAL PARCELADO. 

Tarefa Cartões RCP- Platinum: RC055 ANTECIPAÇÃO TOTAL PARCELADO -RCP 

Abra a tarefa BM064 para o BackOffice realizar o ajuste na fatura do cliente. 

​Registro: Cliente não concorda com a diferença no valor da parcela do parcelamento realizado em XX/XX/XX. Simulação efetivada em R$ XX,XX , e na fatura ficou em R$ XX,XX 

Abrir a tarefa BM010 - ESTORNO TAXAS / TARIFAS 

​Registrar: SACL XXXX Favor efetuar o ajuste de juros emissor cobrados em parcelamento de fatura sobre o valor de xxxx referente a despesa contestada/taxas e tarifas cobradas indevidamente do cliente. 

 Registre Tarefa Informativa: RC525 - Parcelamento de Fatura Fácil - Aceitou

Tarefa: BM063 - CANCELAMENTO PARCELADO FACIL - BO 

Registro: Providenciar ajuste dos encargos cobrados nas parcelas já postadas e ajuste do valor mínimo da próxima fatura. 

BM064 - RECLAMACAO PLANO PARCELADO FACIL - BO 

Registro: Cliente solicita um novo parcelamento em XX parcelas. 



https://tpbradesco.beedoo.io/wiki/469378/anuidade-

Caso não consiga fazer a isenção no módulo de renegociação, devido à trava sistêmica, abra a tarefa BM008 - ISENCAO TOTAL/PARCIAL TAXA DE ANUIDADE e solicite o desconto das parcelas restantes. 

O sistema não permitirá a negociação de cartões com menos de 12 meses de utilização. Caso seja o cenário de um cartão cancelado ou substituído, para realizar os estornos, abra a tarefa BM008 - Isenção total/ parcial taxa de anuidade, solicitando o estorno da cobrança para o BackOffice, solicitando a isenção das parcelas 

Se a resposta for que o cliente possui direito, porém não foi solicitado o estorno. Prossiga com a abertura de tarefa: BM025 - Isenção Anuidade - Func Folha de Pagamento para que sejam feitas as consultas e se necessário, os ajustes. O prazo para tratamento é de até 02 dias úteis.
Tarefa: AR271 – CLIE LEGADO ALTER CAMPANHA/ESTORNO ANUIDADE – AMEX. 

TAREFA 

CENÁRIO 

BM008  

ISENCAO TOTAL/PARCIAL TAXA DE ANUIDADE 

BM010  

ESTORNO TAXAS / TARIFAS 

BM025  

ISENCAO DE ANUIDADE - FUNC FOLHA PGTO 

BM059  

AJUSTE DE ANUIDADE CB CANC HSBC - BO



https://tpbradesco.beedoo.io/wiki/476562/seguros-cartao-de-credito

BM015 - SOLICITACAO DE ESTORNO DO SEGURO

BM020- ESTORNO DO BRADESCO DENTAL

Tarefa: RE153 - ENVIO MANUAL SEGURADO

Tarefa: RC129 – RECLAMAÇÃO SEGURO (SINISTRO)

Em caso de inconsistência no cancelamento ou indisponibilidade do sistema, solicitar o cancelamento do Seguro através de tarefa no Service View.

Tarefa: RC122 - RECLAMACAO CANC SEGURO



https://tpbradesco.beedoo.io/wiki/472305/dados-pessoais

 RC170 – ATUALIZACAO DE NOME,

Após alteração do procedimento e esclarecimento da informação para o cliente, registrar as informações no Service View através da tarefa RC000, encerrar o SACL. 

RC006 – SOLICITACAO DE ALTERACAO DE CPF – PESSOA FISICA

Abrir tarefa referida RC009 – ALTERAÇÃO DE DADOS PESSOAIS informando os dados corretos (estado civil, sexo, nacionalidade, RG ou filiação).

Após esclarecer as informações ao cliente, registrar todo procedimento no Histórico do Service View através da tarefa RC000 - INFORMAÇÕES GERAIS. 



https://tpbradesco.beedoo.io/wiki/469637/estorno-de-encargos-juros-multa-e-iof

Tarefa: BM010 - ESTORNO DE TAXAS\TARIFAS 

A tarefa BM029 deverá ser aberta nas situações em que o cliente mencionar que foi prejudicado na cobrança de encargos na conta corrente devido a utilização do cheque especial ou casos de exceção que o cliente informa que foi debitado e não concorda com a cobrança e irá acionar os órgãos regulamentados. Na tarefa deverá conter as seguintes informações: 



https://tpbradesco.beedoo.io/wiki/488189/fidelidade-bradesco-cartao-disney

ABERTURA DE FILA NO SERVICE VIEW

Após realizar o tratamento do chamado no Portal ADM Disney, registrar a tarefa RC000 no Service View.



https://tpbradesco.beedoo.io/wiki/469182/renegociacao-de-dividas

RC446 - RENEGOCIAÇÃO DE DÍVIDA INFORMATIVA 

► Para ajuste na TC 7119 e na TC 7121, abrir tarefa na fila CM000 e descrevera solicitação + valor da TC. 

O time providenciará a abertura da tarefa BC085, para que o IOF ADICIONAL seja ajustado.
Quando é realizado uma renegociação com entrada, é registrado a informação através das filas BC005/CR050 conforme exemplos abaixo:  



► Operador deveria solicitar ajuste com TC 7119 no valor de R$150,00, porem ao realizar a solicitação,envia a TC 7121. Para a correção o operador deverá solicitar a reversão com TC 8121 no valor de R$150,00 e enviar nova solicitação de ajuste com TC 7119 no valor de R$150,00. Este envio deverá ser feito também através de abertura de fila CM000

















EMAILS BRADESCO
bradesco.com.br 
teleperformance.com.br
pesquisa.interna@bradesco.com.br

sac.cobranca@bradesco.com.br;

 intercambiobradesco@servicosfps.com.br,

Após identificado que se trata de cartão expurgado, seguir conforme abaixo: 

 LUIS FERNANDO DE SOUSA TEIXEIRA <luisfernando.teixeira@bradesco.com.br>; LUCIANO HENRIQUE SILVA <lucianohenrique.silva@bradesco.com.br>; 

E-mails Folha de Pagamento:  

ERICA FERNANDA TRINDADE erica.trindade@bradesco.com.br 

ANDRESSA MEDEIROS DE OLIVEIRA andressa.m.oliveira@bradesco.com.br 

DANIELA BITTENCOURT SANT ANA daniela.bittencourt@bradesco.com.br 

Solicitar ao cliente que os documentos devem ser enviados para o e-mail da Caixa Departamental da TP (Atendimento Cliente Bradesco <atendimentocliente.bradesco@teleperformance.com.br>)

Aprovado: Cliente com acesso ao APP.
Deriva: Acionar o Dener através do e-mail dener.f.rossi@bradesco.com.br com o print do gerenciador e dados do cliente para que seja solicitado agilidade na tratativa. Após o retorno, seguir conforme as orientações passadas.
jefferson.o.lima@bradesco.com.br

Caso o cliente insista que já avaliou tudo, em exceção, poderá ser acionado por e-mail o contato jefferson.o.lima@bradesco.com.br para avaliação.

Em caso de reclamações relacionadas à impossibilidade de cancelamento, a operação deverá encaminhar a solicitação de cancelamento para o e-mail: opcd@bradesco.com.br com os seguintes dados:  
Baixa de dívida da Carteira Cedida 

Cartões ou Venda de carteira de cartões: 

 

apoio_carteiracedida@servicosfps.com.br 

  

Na cópia colocar os e-mails:  

 

jordana.mf@bradesco.com.br 

nirlene.figueira@bradesco.com.br 

adriana.moraes@bradesco.com.br 

sandy.rocha@bradesco.com.br 

jessica.a.rodrigues@bradesco.com.br 

 

Outras carteiras: enviar e-mail para credcedidos e direcionar o SACL para DRC 

Carteira Banco por exemplo carteira comercial carteira (321, 288, 260, 444); 

Losango: tem um canal específico que não é DRC, direcionar SACL para 9080. 

Não é permitido renegociar contas ajuizadas, consulte a caixa cobranca.cartoes@bradesco.com.br.
Caixa de Envio: 4510.acordos@bradesco.com.br
 sac.cobranca@corpr.bradesco.com.br.



E-mail da área: Caixa genérica: scrbacencartoes@bradesco.com.br  

 

Atenção: Em casos de priorização acionar o gestor da área conforme manual de áreas  

o ADALBERTO GUILHERME DOS ANHOS (adalberto.anjos@bradesco.com.br) 

o e-mail com cópia para: cada gestor avaliar para seu portfólio 

 
