# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO


AZURE

Aula 1: Domínio do objetivo

O que é computação em nuvem?
A computação em nuvem é o fornecimento de serviços de computação pela internet. Habilitando inovações rápidas, recursos flexíveis e economias de escala. 

Nuvem privada:
- As organizações criam um ambiente em nuvem em seu datacenter.
- As organizações são responsáveis por operar os serviços que fornecem.
- Não fornece acesso aos usuários fora da organização.
Principais diferenças:
- As organizações têm controle total sobre recursos e a segurança.
- As organizações são responsáveis pela manutenção e pelas atualizações de hardware software.

Nuvem pública:
- Pertencente a serviços de nuvem ou provedor de hosting. Ex. Azure, AWS.
- Fornecer recursos e serviços a várias organizações e usuários.
- Acessada via conexão de rede segura (geralmente pela internet).
Principais diferenças: 
- Nenhuma despesa de capital para escalar verticalmente.
- Os aplicativos podem ser provisionados e de provisionados rapidamente.
- As organizações pagam apenas pelo que utilizam.

Nuvem hibrida:
- Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.
Principais diferenças: 
- As organizações determinam onde executar seus aplicativos.
- As organizações controlam a segurança, a conformidade e os requisitos legais.
- Fornece a maior flexibilidade.

Despesas de Capital (CapEx):
O CAPEX é um investimento de longo prazo, que se refere a gastos com bens de capital, como aquisição de maquinário, imóveis ou hardwares. O CAPEX é pago no ato da compra e é deduzido ao longo dos anos por meio da depreciação. 
- O gasto inicial de dinheiro em infraestrutura física.
- As despesas do CapEx têm um valor que se reduz com o tempo.
Despesas Operacionais (OpEx):
O OPEX é um investimento de curto prazo, que se refere a custos operacionais, como aluguel, água, luz, folha de pagamento, marketing, suprimentos e outros gastos necessários para manter a empresa funcionando. O OPEX é uma despesa recorrente, que é deduzida no mesmo período em que é realizada.
- Gastar com produtos e serviços conforme necessários. Pagamento conforme o uso.
- Seja cobrança recorrente.

Cap 2 – Localizando serviços por categoria
Mód 2 – Benefícios da Nuvem Azure

Aula 1: Benefícios de Nuvem

Alta Disponibilidade: Um sistema que está sempre funcionando, recursos disponíveis sempre que necessários, assim, tendo o melhor ambiente para seus clientes. Também associada ao SLA, ou seja, caso de problema a Microsoft se vira. Qual porcentagem de SLA caracteriza mais tempo, qual caracteriza menos tempo, essa porcentagem já é prevista em contrato e caso o tempo da porcentagem não foi entregue ele será convertido em créditos ao cliente. 
99% -> 1,68h -> 7,2h -> 3,65 dias
99,9% -> 10,1 min -> 43,2 min -> 8,76h
99,95% -> 5 min -> 21,6 min -> 4,38h
99,99% -> 1,01 min -> 4,32 min -> 52,56 min
99,999% -> 6 seg -> 25,9 seg -> 5,26 min
Escalabilidade: Ajustar a capacidade de armazenamento/processamento/RAM conforme a demanda, se alguma máquina usar demais, poderá aumentar, se usar menos, poderá diminuir. (Crescimento Vertical).
Elasticidade: Se acontecer um grande aumento de demanda inesperada, seus recursos implantados podem ser expandidos (automaticamente ou manualmente). (Crescimento Horizontal)
Confiabilidade: Devido ao design descentralizado. A nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente e também permite que tenha recursos implantados em várias partes do mundo.
Previsibilidade: Permite que avance com a confiança, seja no desempenho ou custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework
Segurança: É oferecida ferramentas de segurança que atende a necessidade do cliente, porém importante lembrar que a implementação delas devem ser realizadas pelo cliente.
Governança: Auditoria (log) baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de resolução de problemas.
Gerenciabilidade: Diz respeito de gerenciar os recursos presentes na nuvem. Ex. Escalar automaticamente a implantação de recursos com base na necessidade.
Implantação de recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual e também podendo gerenciar o seu ambiente de nuvem por meio do Portal ou linha de comando remete.
