# Lab-Monitoramento-Inteligente

1. Azure Monitor (O Coração do Sistema)
É a ferramenta central que coleta dados de tudo o que acontece na sua nuvem.

Métricas: Dados numéricos em tempo real (ex: quanto de memória seu notebook virtual está usando).

Logs: Registros detalhados de eventos (ex: quem tentou logar e falhou).

Insights: Painéis prontos que mostram a "saúde" de serviços específicos (bancos de dados, redes, etc.).

3. Application Insights (Foco no Código)
Ideal para desenvolvedores e QAs monitorarem o comportamento do aplicativo.

Rastreamento de Erros: Avisa exatamente em qual linha do código um erro aconteceu.

Performance: Mostra quais partes do seu app estão lentas para os usuários.

Uso: Identifica quais funcionalidades os usuários mais acessam.

5. Alertas Inteligentes e Ações Automáticas
O sistema não apenas avisa, ele pode agir sozinho.

Alertas de Anomalia: O Azure aprende o que é "normal" no seu sistema e te avisa se algo estranho acontecer (ex: um pico de acessos às 3 da manhã).

Auto-scaling: Se o sistema ficar sobrecarregado, ele pode criar automaticamente mais servidores para aguentar a carga e depois desligá-los para economizar dinheiro.

7. Log Analytics (O Detetive)
Uma ferramenta poderosa para investigar problemas complexos.

Consultas KQL: Você usa uma linguagem simples (Kusto) para pesquisar em milhões de registros em segundos.

Cruzamento de Dados: Permite entender se uma lentidão no site foi causada por um problema no banco de dados ou na rede.

9. Azure Service Health
Focado na infraestrutura global da Microsoft.

Avisos de Manutenção: Avisa quando a Microsoft vai mexer nos servidores onde seus dados estão.

Incidentes Globais: Informa se um problema que você está enfrentando é geral na região do Azure (ex: uma queda de energia no datacenter do Brasil).

11. IA e Machine Learning (A "Inteligência")
Previsão de Gastos: Avisa se, no ritmo atual, você vai estourar seus créditos de estudante antes do fim do mês.

Análise de Causa Raiz: Quando algo quebra, a IA analisa os dados e sugere o motivo provável da falha, economizando horas de investigação.

Dica para seu cenário: Como estudante, o Application Insights é a ferramenta mais legal para você conectar nos seus projetos.

Ele ajuda a entender como seu código se comporta "no mundo real" e é uma habilidade muito valorizada em vagas de QA e DevOps.
