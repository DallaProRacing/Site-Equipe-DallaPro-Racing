# 🏍️ Equipe DallaPro Racing - Site Oficial

Site oficial da Equipe DallaPro Racing, especializada em competições de Enduro FIM. O projeto apresenta informações sobre a equipe, piloto, competições e patrocinadores.

## 🌐 Demo

**Site ao vivo:** [https://dallaproracing.github.io/Site-Equipe-DallaPro-Racing/]
## 📋 Funcionalidades

### 🏠 Página Principal
- **Hero Section** com apresentação da equipe
- **Competições** - Cards informativos sobre as principais competições
- **Próximas Etapas** - Calendário de eventos futuros
- **Patrocinadores** - Showcase dos apoiadores da equipe
- **Perfil do Piloto** - Informações sobre Ruan Dalla Rosa
- **Formulário de Contato** - Sistema de envio de emails via EmailJS

### 👤 Página de Perfil do Piloto
- **Informações Pessoais** - Biografia e dados do piloto
- **Estatísticas** - Números de provas, pódios e campeonatos
- **Resultados por Competição** - Sistema de abas com resultados detalhados
- **Galeria de Fotos** - Imagens das competições
- **Equipamentos** - Detalhes da moto e equipamentos utilizados
- **Redes Sociais** - Links para Instagram e outras plataformas

### 🏆 Páginas de Competições
- **Gaúcho de Enduro FIM** - Resultados e classificações
- **Sul Brasileiro de Enduro FIM** - Histórico de participações
- **Copa Meio Oeste** - Detalhes das etapas
- **Galeria de Fotos** - Sistema de upload e visualização
- **Classificação Geral** - Tabelas de pontuação

### 📧 Sistema de Contato
- **Validação de Formulário** - Verificação de campos obrigatórios
- **Envio via EmailJS** - Sistema sem backend para envio de emails
- **Feedback Visual** - Notificações de sucesso/erro
- **Responsividade** - Funciona em todos os dispositivos

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização avançada com:
  - CSS Grid e Flexbox
  - Variáveis CSS (Custom Properties)
  - Animações e transições
  - Design responsivo
- **JavaScript ES6+** - Interatividade e funcionalidades:
  - Manipulação do DOM
  - Validação de formulários
  - Sistema de abas
  - Integração com EmailJS

### Serviços Externos
- **EmailJS** - Envio de emails sem backend
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia

### Ferramentas de Desenvolvimento
- **Git** - Controle de versão
- **GitHub Pages** - Hospedagem gratuita
- **VS Code** - Editor de código
- 
## 🚀 Como Executar o Projeto

### Pré-requisitos
- Navegador web moderno
- Conexão com a internet (para fontes e EmailJS)

### Instalação Local
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/uri-erechim/trabalho-individual-t1-DallaProRacing.git
   cd equipe-dallapro-racing
   ```

2. **Abra o projeto:**
   - Abra o arquivo `src/index.html` em seu navegador
   - Ou use um servidor local como Live Server (VS Code)

### Configuração do EmailJS
Para que o formulário de contato funcione, você precisa configurar o EmailJS:

1. **Crie uma conta em [EmailJS](https://www.emailjs.com/)**

2. **Configure um serviço de email (Gmail recomendado)**

3. **Crie um template de email com as variáveis:**
   - `{{from_name}}` - Nome do remetente
   - `{{from_email}}` - Email do remetente
   - `{{message}}` - Mensagem
   - `{{to_email}}` - Email de destino

4. **Obtenha suas credenciais:**
   - Public Key (Account → General)
   - Service ID (Email Services)
   - Template ID (Email Templates)

5. **Atualize o arquivo `src/assets/js/contact-form.js`:**
   \
