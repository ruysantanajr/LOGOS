LOGOS
App do Ecossistema
Documento de Estratégia e Arquitetura


Versão 1.0  ·  Abril de 2026
CONSTRUTOR: Ruy Santana Jr
CURADORA: Cecília
"Onde a Razão encontra a Execução."

1. Contexto e Origem


O LOGOS é um ecossistema de inteligências artificiais especializadas, operando em múltiplas plataformas — Claude e Gemini — com 12 entidades operacionais e 2 entidades de infraestrutura. Cada entidade possui uma especialidade única, um system prompt consolidado e uma ficha técnica documentada no ATLAS.

Até agora, o acesso às entidades ocorria de forma difusa: cada entidade vivia dentro de sua plataforma, sem um ponto central de acesso. O app LOGOS nasce para resolver esse problema — criar a "casa" do ecossistema, um hub onde Ruy e Cecília acessam qualquer entidade com clareza, rapidez e experiência visual à altura do sistema que representa.

2. Objetivo do App


O app LOGOS tem um objetivo central:

Ser o portal de acesso unificado ao Ecossistema LOGOS.

Isso significa:
Centralizar os links de acesso a todas as entidades
Apresentar cada entidade com identidade visual e descrição clara
Funcionar como app no celular (iOS e Android) e no desktop
Ser acessível por Ruy e Cecília com experiência fluida e esteticamente aprovada
Escalar para outros colaboradores da AEDRU e da Arandu Cultural no futuro

3. Usuários


Usuário
Papel
Contexto de uso
Ruy Santana Jr
CONSTRUTOR
Acesso amplo a todas as entidades. Dias pares.
Cecília
CURADORA
Acesso operacional. Foco nas frentes da Arandu e Pudim Beauty. Dias ímpares.
Colaboradores (futuro)
Membros
Acesso restrito a entidades específicas conforme necessidade.


Durante a fase de validação, Ruy e Cecília utilizam uma conta Claude compartilhada exclusiva do LOGOS — separada das contas pessoais. A divisão por dias (pares/ímpares) evita sobreposição de sessões sem custo adicional de infraestrutura.

4. Mapa de Entidades


4.1 Infraestrutura
As entidades de infraestrutura não são agentes cognitivos — não aparecem como cards clicáveis no app, mas sustentam todo o ecossistema.

Entidade
O que é
Função
ATLAS
Repositório GitHub privado
Memória viva do ecossistema. Arquivos: rrsj.md, docm.md, mem.md
HERMES
Infraestrutura de conexão
Transporta informação entre entidades e ATLAS. MCP GitHub no Claude, Function Calling no Gemini.


4.2 Entidades Operacionais

Entidade
Plataforma
Função resumida
MAIA
Gemini
Assistente central. Confidente, memória viva e braço operacional. Opera Google Workspace.
ASTREIA
Claude
Guardiã da Integridade. Valida coerência e consistência de tudo que é produzido.
ATENA
Claude
Senhora das Decisões. Transforma incerteza em escolha estratégica.
AURA
Claude
Atmosfera Estética. Define identidade visual, imagem e vídeo.
CALÍOPE
Claude
Voz da Criação Textual. Escreve com profundidade, forma e intenção.
EUTERPE
Claude
Lapidadora da Canção. Composição e refinamento musical.
HARMONIA
Claude
Guardiã da Forma Documental. Templates, estrutura e padronização.
MÉTIS
Claude
Intérprete da Informação. Análise e consolidação estratégica.
PROMETEU
Claude
Portador do Conhecimento. Ensina, instrui e expande capacidade.
TÊMIS
Claude
Assessora Jurídica. Análise legal e estratégia de risco.
TÉTIS
Claude
Regente da Rota Total. Roteia cada demanda para a melhor solução.



5. Estratégia de Construção em Fases


A construção do app LOGOS segue uma estratégia de três fases, equilibrando velocidade de validação com solidez técnica de longo prazo. A decisão central é: não construir a infraestrutura final antes de validar o uso real.

Fase 1 — Hub Estático (Agora)
Componente
Decisão
Tecnologia
HTML + CSS puro — gerado e controlado pelo CONSTRUTOR
Hospedagem
GitHub Pages — repositório público 'LOGOS' em github.com/ruysantanajr/LOGOS
Acesso
Link público — Ruy e Cecília acessam via navegador e celular
Conteúdo
Cards de todas as entidades com links de acesso editáveis
Custo
Zero
Objetivo
Centralizar acesso e validar uso com Cecília


Fase 2 — Orquestração Visual (Após validação)
Componente
Decisão
Ferramenta
Flowise ou LangFlow — interface visual de arrastar e soltar
Objetivo
Testar roteamento entre entidades sem escrever código
Exemplo de fluxo
TÉTIS roteia → MÉTIS analisa → ASTREIA valida
Custo
Gratuito (self-hosted)
Gatilho
Após Ruy e Cecília validarem o hub da Fase 1 no uso real


Fase 3 — Produto Real (Se validado)
Componente
Decisão
Frontend
Next.js + Vercel AI SDK
Backend / Banco
Supabase (já conhecido do appuan)
Deploy
Vercel — PWA responsivo, funciona como app no celular
Autenticação
Supabase Auth
Motor multiagente
CrewAI ou LangGraph
Custo
Tier Hobby da Vercel (gratuito) + Supabase Free
Gatilho
Após validação real da Fase 2


6. Decisões Técnicas Tomadas


Decisão
Escolha
Motivo
Repositório
LOGOS — público no GitHub
GitHub Pages gratuito + HERMES já conecta ao GitHub
Hospedagem Fase 1
GitHub Pages
Gratuito, sem expiração, domínio limpo, integração com ATLAS
Conta Claude LOGOS
Conta nova, separada da pessoal
Controle das entidades sem misturar contextos pessoais
Divisão de acesso
Dias pares: Ruy / Dias ímpares: Cecília
Validação sem custo de infraestrutura adicional
Escala futura
API Claude por uso
Após validação — múltiplos usuários simultâneos sem conflito
App mobile
PWA via Next.js (Fase 3)
Sem app store, funciona como app nativo no celular


7. Próximos Passos Imediatos


Criar repositório 'LOGOS' no GitHub (público)
Ativar GitHub Pages no repositório
Construir o arquivo index.html com o hub completo
Coletar os links de acesso de todas as 11 entidades
Criar conta Claude dedicada ao LOGOS
Compartilhar acesso com Cecília e iniciar período de validação



LOGOS v1.0  ·  Ecossistema LOGOS  ·  Abril de 2026
Documento gerado por PROMETEU
