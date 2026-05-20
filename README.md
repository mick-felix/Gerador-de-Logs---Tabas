📋 Gerador de Log de Turno — Tabas
Este projeto é uma ferramenta de front-end (Single Page Application) desenvolvida para otimizar, padronizar e agilizar o processo de passagem de bastão entre os turnos da equipe. A aplicação permite consolidar todas as ocorrências, pendências e status de infraestrutura do condomínio em um relatório limpo, dinâmico e totalmente formatado para envio direto no Slack.

✨ Principais Funcionalidades
Identificação Dinâmica & Escala: Seleção rápida do período de transição com gerenciamento de presença da equipe que está assumindo o posto.

Gestão de Ocorrências com Autocomplete: Busca inteligente de unidades através de mapeamento interno de códigos VB e apartamentos.

Gerador Mágico de Descrições: Criação automatizada de textos padrões com base no tipo de ocorrência selecionada (Realocação 🔄, Empréstimo 📦, Manutenção 🛠️, etc.), minimizando erros de digitação.

Monitoramento de Infraestrutura: Painel visual para reportar o status operacional de elevadores e detalhamento de falhas em tempo real.

Persistência Local (Autosave): Integração com localStorage para garantir que nenhum dado seja perdido caso a aba do navegador seja fechada acidentalmente.

Exportação Otimizada: Formatação nativa com markdown do Slack (emojis, blocos divisores e menções a usuários), pronta para copiar e colar.

🚀 Como Utilizar
Por ser uma ferramenta construída puramente com HTML5, CSS3 e JavaScript (Vanilla), não há necessidade de instalar dependências ou rodar servidores localmente:

Faça o clone ou o download deste repositório.

Abra o arquivo Gerador de Logs.html diretamente em qualquer navegador de sua preferência.

Preencha as informações do turno e clique em Gerar log para o Slack.

Essa estrutura deixa claro o propósito do projeto para qualquer colega da empresa que acessar o repositório, além de destacar a facilidade de uso (por não precisar de setup ou backend).
