# Auditoria_de_Acessibilidade_HTML5_e_CSS3
📰 Portal Notícias PB — Auditoria de Acessibilidade
Este projeto é um portal de notícias regional desenvolvido com foco total em acessibilidade web (WCAG), semântica HTML5, estilização CSS3 e validações rigorosas de dados. O sistema foi projetado para ser totalmente navegável por tecnologias assistivas, como leitores de tela.

📂 Estrutura do Projeto
A organização dos arquivos segue o padrão de separação de responsabilidades para facilitar a manutenção:

. HTML.html: Ponto de entrada (Home) do portal.

. cadastro/conta.html: Interface de formulário para criação de conta.

. css/style.css: Folha de estilo global (Layout da Home).

. cadastro/css/conta.css: Estilização específica e centralizada para o cadastro.

🛠️ Descrição Técnica
1. Página Principal (HTML.html)
Desenvolvida para consumo de conteúdo acessível.

Semântica Avançada: Uso de header, nav, main, article, section e footer.

Mídia Inclusiva: Implementação da tag <video> com múltiplos formatos (.webm, .mp4), atributo poster e suporte a legendas via tag <track>.

Âncoras de Navegação: Links internos que permitem saltar diretamente para as seções de interesse.


2. Página de Cadastro (cadastro/conta.html)
Focada na interação do usuário e integridade dos dados.

. Acessibilidade de Formulários: Associação explícita entre <label> e <input> via atributos for e id.

. Validações Nativas:

. required: Impede o envio de campos vazios.

. pattern: Regex para validar o formato de telefone brasileiro (XX) XXXXX-XXXX.

. minlength: Garantia de segurança mínima para senhas.

. Feedback Dinâmico: JavaScript integrado para exibir alertas de confirmação e gerenciar redirecionamentos pós-cadastro.

📋 Critérios de Auditoria Atendidos

Item  Critério Técnico        Implementação                                         Status
1     Semântica HTML5         Semântica HTML5                                      ✅ Concluído
2     Navegação por Teclado   Pseudo-classe :focus visível em todos os elementos   ✅ Concluído
3     Associação de Campos    Relação label + input funcional                      ✅ Concluído
4     Validação de Dados      Atributos required e pattern ativos                  ✅ Concluído
5     Mídia Acessível         Vídeos com legendas e caminhos relativos corretos    ✅ Concluído



🚀 Como Executar o Projeto
1. Clone o repositório:

Bash
git clone https://github.com/VictorSillvaa/Auditoria_de_Acessibilidade_HTML5_e_CSS3.git


2. Navegue até a pasta:

Bash
cd Auditoria_de_Acessibilidade_HTML5_e_CSS3

3. Abra o navegador:
Basta clicar duas vezes no arquivo HTML.html ou utilizar a extensão Live Server do VS Code.


👤 Desenvolvedor
José Victor da Silva Nascimento 📅 Ano: 2026

🏗️ Projeto: Auditoria de Acessibilidade Web