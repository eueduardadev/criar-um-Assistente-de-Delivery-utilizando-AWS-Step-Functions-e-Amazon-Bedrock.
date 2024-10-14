# criar-um-Assistente-de-Delivery-utilizando-AWS-Step-Functions-e-Amazon-Bedrock.
**Atividade com AWS**

**Passo 1: Estruturação do Fluxo**
1 Recepção do Pedido

  - Início do fluxo: Cliente faz o pedido.

  - Validação do pedido: Verifica disponibilidade e detalhes.

2 Processamento do Pagamento

   - Integração com serviço de pagamento: Processa o pagamento.

   - Confirmação de pagamento: Verifica se o pagamento foi realizado com sucesso.

3 Preparação do Pedido

   - Notificação ao restaurante/cozinha: Prepara o pedido.

   - Atualização de status: Pedido em preparo.

4 Entrega

   - Alocação do entregador: Designa um entregador.

   - Rastreamento: Permite que o cliente rastreie o pedido.

   - Entrega do pedido: Confirmação da entrega.

5 Pós-Entrega

  - Feedback do cliente: Solicita avaliação.

  - Análise de dados: Utiliza Amazon Bedrock para personalizar futuros pedidos.

**Passo 2: Implementação com AWS Step Functions e Amazon Bedrock**

1 Criar Step Functions

   - Definir estados: Como ReceberPedido, ValidarPedido, ProcessarPagamento, ConfirmarPagamento, PrepararPedido, DesignarEntregador, RastrearPedido, ConfirmarEntrega, SolicitarFeedback.

   - Configurar transições e ações em cada estado.

2 Integração com Serviços

   - Serviço de pagamento: Usar AWS Lambda ou API Gateway para integração.

   - Notificação e atualização de status: Integrar com SNS/SQS para comunicação.

3 Utilização do Amazon Bedrock 
  - Personalização: Usar aprendizado de máquina para analisar dados de pedidos e melhorar recomendações.
 
  -  Eficiência: Otimizar processos com base em dados históricos.

 *Esboço produzido com auxilio de IA**

