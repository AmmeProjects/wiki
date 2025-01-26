# Recursos

## Acrónimos

### Agentes de Mercado


Enumeramos de seguida alguns agentes de mercado relevantes para efetuar serviços de carregamentos na mobilidade elétrica. Tentamos sempre que possível dar como exemplos empresas que se focam apenas num segmento de mercado (pure-plays) em vez de acumular vários papéis.

* **OPC** \- Operador de Posto de Carregamento. Em Portugal, um OPC aluga o seu equipamento para o carregamento de veículos e partilha os consumos com a **EGME** (**MobiE**) para poderem ser posteriormente faturados pelo **CEME**. Desta forma, a gestão de fluxos energéticos (de forma simplificada, a contagem de energia consumida pelo posto) e financeiros (a faturação dos consumos) é gerida pela **EGME**. O operador não revende energia. Nos restantes países, um **OPC** compra energia a um comercializador como qualquer outro consumidor, gere os fluxos energéticos e financeiros, e fatura a energia consumida diretamente ao cliente.  
  **Exemplo:** PowerDot, Ionity, Tesla, Continente.


* **PAN** \- Ponto de Acesso Nacional. Este agente foi introduzido pelo AFIR e é responsável por centralizar os dados estáticos (informação do posto tal como potência e tipo de tomadas) e dinâmicos (estado atual do posto). Esta informação é disponibilizada então aos utilizadores para saberem o que podem esperar da rede pública de carregamento. Este papel já existe no regulamento português, e é uma das responsabilidades da **EGME**. Nos restantes países, é um espaço ocupado por instituições públicas e/ou entidades privadas tal como a Eco-Movement, dado o valor criado por estes dados.  
  **Exemplo:** MobiE (excluindo a sua plataforma de e-roaming).

	

* **EGME** \- Entidade Gestora da Mobilidade Elétrica. Este agente criado pelo regulamento português inclui vários papéis dos quais se destacam: **PAN**, gestor de fluxos energéticos e financeiros na rede de carregamento, e agente de **e-roaming** entre **OPCs**. Permite que a energia entregue num posto seja contabilizada a diferentes fornecedores de energia (**CEMEs**), dado que transmite os consumos das sessões de carregamento aos **CEMEs** para que possam faturar a energia aos seus clientes. Como agente de **e-roaming**, garante uma solução para que um único cartão seja válido em qualquer posto na rede. Em Portugal, este papel cabe exclusivamente à empresa pública **MobiE**. Nos restantes países, os papéis da **EGME** são divididos entre **PAN**, **OPCs** e agentes de **e-Roaming**.  
  **Exemplo:** MobiE.

* **CEME** \- Comercializador de Energia para a Mobilidade Elétrica. Este agente criado pelo regulamento português tem o papel de compra de energia de um comercializador do setor elétrico (**CSE**) tal como qualquer outro consumidor, e revenda para os utilizadores da rede de carregamento. É responsável também por faturar as sessões de carregamento ao utilizador final a partir dos dados de consumos fornecidos pela **EGME**. É responsável também por disponibilizar um meio de pagamento ao utilizador, tipicamente um cartão RFID ou aplicação. Este agente com este papel apenas existe em Portugal.  
  **Exemplo:** ViaVerde Electric, Prio.

* **eMSP** \- Fornecedor de Serviços de Mobilidade Elétrica. Este agente surgiu naturalmente da necessidade de agregar várias redes **OPC** através de único método de pagamento (**e-roaming**), e proliferam-se pela UE. Estabelecem contratos com vários **OPCs** para revender os seus serviços de carregamento, cobrando uma taxa ao utilizador final pelo serviço de conveniência. Em Portugal, o serviço de agregação de redes é prestado em exclusivo pela **EGME**, sendo que a faturação é feita pelo **CEME**. No entanto, os **CEMEs** são revendedores de energia, pelo que não são **eMSP** puros em Portugal, tal como existem nos restantes mercados. Para um **eMSP** puro operar em Portugal tal como o faz nos restantes países europeus tem de contratar os serviços de um **CEME**, mas regra geral apenas traz valor acrescentado para os seus utilizadores estrangeiros.  
  **Exemplo:** ChargeMap, Electromaps, Electroverse.

* **CSE** \- Comercializador do Setor Elétrico. Toda a rede de mobilidade elétrica em assenta no mercado elétrico tradicional, seja em Portugal ou na Europa. O **CSE** compra eletricidade aos produtores no mercado grossista (exemplo, OMIE na península ibérica) e revende-a ao consumidor, seja um cliente doméstico, empresarial ou um **CEME**. Em Portugal, os **OPCs** não compram energia a um **CSE**, o **CEME** é responsável pela revenda de energia de um **CSE** ao utilizador; por sua vez, o **OPC** aluga ao utilizador o carregador usado lhe entregar a energia. Nos restantes mercados, os **OPCs** compram energia a um **CSE** local e revendem diretamente ao cliente, numa operação verticalmente integrada.  
  **Exemplo:** Luzboa, GoldEnergy.
