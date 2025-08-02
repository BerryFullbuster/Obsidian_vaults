A arquitetura de software é o conjunto de estruturas necessárias para raciocinar sobre o sistema, que compreende elementos de software, as relações entre eles e as propriedades de ambos.

Definição
"A arquitetura de software é um conjunto de estruturas de um sistema, composta por elementos de software, as propriedades externamente visíveis desses elementos e os relacionamentos entre eles." (Bass, Clements e Kazman, 2012)

Importância:
- Facilita a manutenção e evolução do sistema; 
- Suporta decisões de desempenho, escalabilidade, segurança e reutilização; 
- Permite a comunicação entre stakeholders (desenvolvedores, arquitetos, analistas, clientes).

Estilos Arquiteturais
1. Arquitetura em Camadas (Layered)
	Divide o sistema em camdas horizontais, como:
	- Apresentação (UI)
	- Lógica de Negócio
	- Acesso a Dados
	Vantagens: separação de responsabilidadesm fácil manutenção.
	Exemplo: sistemas Web MVC (Model-View-Controller)
2. Cliente-Servidor
	Componentes divididos em cliente (requisita serviços) e servidor (responde aos serviços).
	Exemplo: Aplicações web tradicionais.
	Vantagens: centralização do controle, escalabilidade.
3. Microsserviços
	O sistema é divido em cliente (requisita serviços) e servidor (responde aos serviços)
	Exemplo: Netflix, Amazon
	Vantagens: alta escalabilidade, manutenção independente de módulos.
	Desvantagem: complexidade de orquestração.
4. Event-Driven Architecture (EDA)
	Baseia-se em eventos para comunicação entre componentes.
	Exemplo: sistemas de pagamento, sensores IoT
	Vantagens: desacoplamento, reação em tempo real.
5. Arquitetura Monolítica
	Aplicação única onde todas as funcionalidades estão agrupadas.
	Vantagens: simplicidade inicial.
	Desvantagens: dificil manutenção e escalabilidade.

Exemplo
Sistema de e-commerce:
- Camada de apresentação: React (Frontend) 
- Camada de negócio: API em Node.js 
- Camada de persistência: MongoDB 
- Estilo: Arquitetura em camadas e microsserviços (pagamento, estoque, usuários)