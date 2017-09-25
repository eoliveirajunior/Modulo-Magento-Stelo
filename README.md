# Môdulo-Magento-Stelo

# PASSO A PASSO COMO INSTALAR O MÓDULO STELO SUB EM SUA LOJA MAGENTO
Nosso módulo foi desenvolvido seguindo o padrão de boas práticas no desenvolvimento.

Magento e deve funcionar perfeitamente em qualquer loja Magento nas versões 1.7x, 1.8x e
1.9x.
Instruções antes da instalação:

1- Todos módulos devem primeiramente ser instalados em ambiente de homologação, assim
você evitar qualquer problema em sua loja em produção, é sempre muito mais seguro verificar
a compatibilidade do módulo com seu sistema, então, gere um backup da loja, crie um
ambiente de homologação e efetue todos os testes, depois instale o módulo em produção
#segueadica.

2- Antes de subir em produção faça um backup da loja, base e arquivos
COMO INSTALAR O MÓDULO MAGENTO - STELO SUB
Passo 1 - Efetue o Download do módulo
Passo 2 - Descompactar o arquivo.

3 - Entre na pasta descompactada.

4 - Navegue pelas pastas do módulo até onde estão as pastas app, js e skin.

5 - Copie as pastas app, js e skin para a raiz de sua instalação Magento, use um software
de FTP.

6 - Limpe os caches do Magento pela administração da loja em Sistema > Gerenciar
Cache e logo em seguida faça o logout de sua conta e faça o login novamente.

Após realizar esses passos você finalizou o processo de instalação e agora é preciso configurar
o módulo.

# PASSO A PASSO COMO CONFIGURAR O MÓDULO STELO SUB EM SUA LOJA MAGENTO

1 – Acesso a administração do Magento e vá no caminho Sistema > Configuração >
Vendas > Métodos de Pagamento e escolha a aba Stelo Transparente – Configurações da
ATIVAÇÃO.

2 – Preencha os campos solicitados pelo módulo na aba Stelo Transparente –
Configurações da ATIVAÇÃO.

   1- Habilitado = Sim.
   2- Título = Preencha o Título para aparecer na página de checkout.
   3- Ambiente = Em Produção.
   4- Status de pedido novo = Você escolhe qual status o pedido deve retornar após confirmação de pagamento, ex: pendente, processando, etc...
   5- Url Stelo = Copie e Cole este link: https://api.stelo.com.br/security/v1/cards/tokens
   6- ClientID Stelo = É fornecido pela Stelo no ato de seu cadastro.
   7- ClientSecret Stelo = É fornecido pela Stelo no ato de seu cadastro.
   8- Ordem de exibição = É a ordem que o módulo irá aparecer na página de checkout.

3 - Preencha os campos solicitados pelo módulo na aba Stelo Transparente –
Configurações da PAGAMENTO.
   1- Número máx. de parcelas = É o número máximo parcela que é aceito em uma compra.
   2- Valor mínimo de parcela = É o valor mínimo aceito por parcela.
   3- Habilitar Boleto = Escolha SIM ou NÃO para habilitar a opção Boleto como método de pagamento.
   4- Ordem de Exibição do Boleto = É a ordem que a opção de Boleto irá aparecer na tela de checkout.

4 – Salve as configurações realizadas e com isso o módulo Stelo SUB estará habilitado em sua página de checkout.
