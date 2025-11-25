# AgroTrace
**Introdução:** O projeto busca solucionar o problema da falta de transparência e do alto desperdício na cadeia de suprimentos de alimentos, especialmente em países em desenvolvimento, onde cerca de 40% da produção é perdida antes de chegar ao consumidor. Soluções corporativas existentes são caras e inacessíveis para pequenos e médios produtores — que representam a maior parte da agricultura na América Latina e em outros mercados emergentes —, deixando milhões de consumidores sem informações confiáveis sobre a origem, o uso de água, as emissões de carbono e as condições de produção dos alimentos que consomem.
O AgroTrace surge como uma solução simples, gratuita e democrática: um aplicativo móvel que permite a qualquer produtor registrar seus produtos com dados de sustentabilidade e gerar QR codes únicos, enquanto qualquer pessoa pode escanear esses códigos com o celular e visualizar imediatamente toda a jornada do alimento, da fazenda à prateleira. O objetivo é promover transparência total, reduzir desperdício, incentivar práticas agrícolas responsáveis e contribuir diretamente para o alcance do ODS 12 (Consumo e Produção Responsáveis), oferecendo uma ferramenta acessível.
O AgroTrace será o aplicativo de rastreabilidade agrícola mais simples, acessível e confiável, permitindo que qualquer pessoa — do pequeno produtor rural ao consumidor urbano — acompanhe a jornada real de cada alimento com apenas um escaneamento de QR code.
Nosso produto conecta diretamente quem produz, quem vende e quem consome, eliminando intermediários desnecessários e oferecendo transparência total sobre origem, uso de água, emissões de carbono e práticas sustentáveis. Será 100% gratuito para produtores e consumidores. 
Em um mundo onde o consumidor consciente quer saber exatamente o que está comendo e o pequeno agricultor precisa de ferramentas baratas para comprovar sua qualidade, o AgroTrace será a ponte que transforma informação em confiança, confiança em valor e valor em impacto real — social, ambiental e econômico — para toda a cadeia alimentar.


**Escopo:** O que foi e o que não foi incluído.
**Funcionalidades Principais:** Lista clara das funcionalidades.
**Tecnologias Utilizadas:** Frontend: React Native, Expo (câmera, notificações).
Backend: Firebase (autenticação, banco).
APIs: Firebase Auth, Expo Camera, mock API (rastreabilidade).

**Como Rodar o Projeto:** Instruções detalhadas de setup do ambiente (incluindo a necessidade de HAXM/WHPX), como compilar e rodar em emulador ou dispositivo.
Screenshots e/ou Vídeo Curto do App em Funcionamento (MVP).
Membros da Equipe e Contato (Git committers).
Licença (ex: MIT ou outra, se aplicável).
**Pasta UML/Diagrams:** Incluam todos os diagramas UML gerados nas semanas 1 e 2 (Casos de Uso, Classes, Atividades, Sequência, Componentes). Façam referência a eles no README.md ou em um documento Architecture.md se optarem por criá-lo.
Pasta docs (Opcional, mas altamente recomendado): 
**Architecture.md:** Detalhes sobre a arquitetura escolhida (MVVM, Clean Architecture etc.), justificativas para as escolhas.
**API_Specs.md:** Documentação da API consumida (endpoints, exemplos de requests/responses), se aplicável.
**User_Manual.md:** Guia de Uso do Aplicativo AgroTrace: Transparência e Rastreabilidade

O AgroTrace foi desenvolvido para simplificar a rastreabilidade e promover a transparência, estabelecendo uma ligação direta entre o Produtor Rural e o Consumidor. A sua utilização é segmentada conforme o perfil do utilizador.

Para o Produtor Rural 

O Produtor tem a responsabilidade de introduzir os dados do produto no sistema, garantindo a transparência da sua mercadoria.

O processo inicia-se com o Login e o acesso à funcionalidade "Cadastrar Produto" no menu principal. Neste ecrã, o Produtor preenche o formulário detalhado, que inclui o Nome do Produto, a sua Origem e, de forma crucial, as métricas de Sustentabilidade, como o Uso de Água por quilograma. Estes dados ambientais são a base da confiança para o Consumidor. Por fim, é inserido o ID único do Lote que será associado ao QR Code , o produto fica imediatamente rastreável no Firebase e disponível para verificação.

Para o Consumidor 

O Consumidor utiliza o aplicativo para obter informações detalhadas e partilhar o seu feedback sobre os produtos agrícolas.

O rastreio é iniciado através da função "Escanear QR Code" no Dashboard. Ao apontar a câmara para o código do produto, o sistema exibe de imediato o ecrã "Rastreabilidade do Produto". Aqui, o Consumidor tem acesso completo à Origem, às Certificações e aos dados de Sustentabilidade fornecidos pelo Produtor. No mesmo ecrã de detalhes, o Consumidor pode utilizar o componente de estrelas para dar a sua nota (1 a 5), um feedback direto e valioso (UC03). A qualquer momento, o utilizador pode consultar o "Consultar Histórico" para rever todos os produtos que já rastreou e avaliou (UC10).
Garanta que os commits estejam limpos e o histórico do Git esteja organizado e que cada membro da equipe contribuiu de forma significativa.
