# IMVU Extractor

**IMVU Extractor** é uma aplicação desktop premium para extração e gerenciamento de produtos IMVU. Desenvolvida com React, Electron e Python, oferece uma experiência completa e profissional para download de avatares, produtos e texturas do IMVU.

> ⚠️ **Projeto Comercial**: Este é um software premium que requer licença ativa. O GitHub é usado apenas para atualizações automáticas e documentação.

## 🎯 Sobre o Projeto

O IMVU Extractor é uma solução comercial completa que combina:

- **🖥️ Aplicação Desktop**: Interface moderna construída com React e Electron
- **🌐 Plataforma Web**: Sistema de autenticação e gerenciamento de licenças
- **🐍 Backend Python**: API robusta para comunicação com servidores IMVU
- **💳 Sistema de Pagamentos**: Integração com Stripe para planos de assinatura

## ✨ Funcionalidades Principais

### 🎮 Extração de Produtos
- **Download de Avatares Completos**: Extração de avatares com todos os acessórios
- **Produtos Individuais**: Download de roupas, acessórios e móveis
- **Texturas e Meshes**: Extração de arquivos 3D e texturas
- **Processamento em Lote**: Download múltiplo simultâneo

### 📱 Interface Moderna
- **Design Responsivo**: Interface adaptável e intuitiva
- **Multi-idioma**: Suporte completo em Português e Inglês
- **Tema Escuro**: Interface otimizada para uso prolongado
- **Progresso em Tempo Real**: Acompanhamento detalhado de downloads

### 🔒 Sistema de Licenças
- **Autenticação Segura**: Login via Discord integrado
- **Planos Flexíveis**: Mensal, Anual e Vitalício
- **Verificação Online**: Validação automática de licenças ativas
- **Sincronização**: Dados sincronizados entre web e desktop

##  Arquitetura do Sistema

### Componentes Principais

1. **Aplicação Desktop** (`Projeto`)
   - Interface React com Tailwind CSS
   - Integração Electron para funcionalidades nativas
   - Sistema de store com Zustand

2. **Plataforma Web** (`Site`)
   - Next.js 14 com autenticação NextAuth
   - Dashboard de usuário e gerenciamento
   - Sistema de pagamentos Stripe

3. **Sistema de Configuração**
   - Configurações criptografadas
   - Gerenciamento seguro de credenciais
   - Templates de configuração

## 🚀 Como Funciona

### Integração Site + Extrator

O IMVU Extractor funciona através de uma arquitetura integrada que combina:

#### 🌐 **Plataforma Web (Site)**
- **Autenticação Discord**: Login seguro via Discord
- **Gerenciamento de Assinaturas**: Planos Gratuito, Mensal, Anual e Vitalício
- **Processamento de Pagamentos**: Integração completa com Stripe
- **Dashboard do Usuário**: Controle de licenças e configurações
- **Sistema de Verificação**: Validação em tempo real de status de assinatura

#### 🖥️ **Aplicação Desktop (Extrator)**
- **Verificação de Licença**: Comunicação automática com o Site para validar permissões
- **Sincronização de Dados**: Configurações e preferências sincronizadas
- **Download Seguro**: Acesso aos recursos baseado no plano ativo
- **Interface Responsiva**: Experiência otimizada para cada tipo de usuário

### Fluxo de Funcionamento

#### 1. **Registro e Autenticação**
```
Usuário → Discord → Site → Criação de Conta → Dashboard
```

#### 2. **Aquisição de Licença**
```
Dashboard → Escolha do Plano → Stripe Payment → Ativação Automática
```

#### 3. **Uso do Extrator**
```
Download do App → Login Automático → Verificação Online → Acesso Liberado
```

#### 4. **Verificação Contínua**
```
Extrator
```

### Para Usuários

1. **Acesso à Plataforma**: Visite o site oficial e crie sua conta
2. **Escolha do Plano**: Selecione entre os planos disponíveis
3. **Download da Aplicação**: Baixe o executável após a compra
4. **Configuração**: Configure suas credenciais IMVU
5. **Uso**: Comece a extrair produtos imediatamente

### Hierarquia de Recursos por Plano

#### 🆓 **Plano Gratuito**
- ✅ Extração básica limitada (5 produtos/dia)
- ✅ Interface completa
- ❌ Download em lote
- ❌ Suporte prioritário

#### 💙 **Plano Mensal**
- ✅ Extração ilimitada
- ✅ Download em lote
- ✅ Todas as funcionalidades
- ✅ Suporte padrão

#### ❤️ **Plano Anual**
- ✅ Todos os recursos do Mensal
- ✅ Desconto significativo
- ✅ Suporte prioritário
- ✅ Acesso antecipado a novos recursos

#### ⭐ **Plano Vitalício**
- ✅ Acesso permanente
- ✅ Todos os recursos futuros
- ✅ Suporte VIP
- ✅ Participação em beta testing

### Planos Disponíveis

- **🆓 Gratuito**: Funcionalidades básicas limitadas
- **💙 Mensal**: Acesso completo por 30 dias
- **❤️ Anual**: Acesso completo por 12 meses (desconto)
- **⭐ Vitalício**: Acesso permanente (melhor valor)

## 🔄 Sistema de Atualizações

### Distribuição via GitHub

O IMVU Extractor utiliza o GitHub como plataforma de distribuição segura para atualizações:

#### 📦 **GitHub Releases**
- **Distribuição Oficial**: Todas as versões são publicadas via GitHub Releases
- **Assinatura Digital**: Executáveis assinados digitalmente para garantir autenticidade
- **Versionamento Semântico**: Seguimos o padrão SemVer (Major.Minor.Patch)
- **Changelog Detalhado**: Registro completo de mudanças em cada versão

#### 🔄 **Atualizações Automáticas**
- **Verificação ao Iniciar**: O aplicativo verifica automaticamente por novas versões
- **Download Seguro**: Atualizações baixadas diretamente do GitHub
- **Instalação Silenciosa**: Processo de atualização sem interrupção do usuário
- **Rollback Automático**: Reversão automática em caso de falha na atualização

### Processo de Atualização

#### 1. **Detecção de Nova Versão**
```
App Startup → GitHub API Check → Compare Versions → Notify User
```

#### 2. **Download da Atualização**
```
User Consent → GitHub Release Download → Verify Signature → Prepare Install
```

#### 3. **Instalação**
```
Backup Current → Install Update → Verify Installation → Restart App
```

#### 4. **Verificação Pós-Atualização**
```
App Restart → License Check → Feature Validation → Update Complete
```

### Controle de Versão

#### 🏷️ **Tipos de Release**
- **🚀 Major (X.0.0)**: Grandes mudanças, novas funcionalidades principais
- **✨ Minor (X.Y.0)**: Novas funcionalidades, melhorias significativas
- **🐛 Patch (X.Y.Z)**: Correções de bugs, melhorias menores
- **🔥 Hotfix**: Correções críticas de segurança (liberação imediata)

#### 📋 **Canais de Atualização**
- **🟢 Stable**: Versão estável para todos os usuários
- **🟡 Beta**: Versão de teste para usuários Premium/Vitalício
- **🔴 Alpha**: Versão de desenvolvimento (apenas desenvolvedores)

### Configurações de Atualização

#### ⚙️ **Opções do Usuário**
- **Automática**: Baixa e instala automaticamente (padrão)
- **Notificar**: Apenas notifica sobre novas versões
- **Manual**: Usuário controla completamente o processo
- **Beta Channel**: Acesso antecipado a versões beta (Premium+)

#### 🔧 **Configurações Avançadas**
- **Horário de Verificação**: Personalizar quando verificar atualizações
- **Bandwidth Limit**: Limitar velocidade de download
- **Proxy Support**: Suporte para conexões via proxy
- **Offline Mode**: Funcionalidade limitada sem conexão

### Compatibilidade e Rollback

#### 🔄 **Compatibilidade de Versões**
- **Forward Compatibility**: Versões antigas funcionam com dados novos
- **Backward Compatibility**: Versões novas suportam dados antigos
- **Migration Scripts**: Scripts automáticos para migração de dados
- **Configuration Sync**: Sincronização de configurações entre versões

## 📋 Requisitos do Sistema

### Mínimos
- **SO**: Windows 10 (64-bit)
- **RAM**: 4GB
- **Armazenamento**: 500MB livres
- **Internet**: Conexão estável para verificação de licença

### Recomendados
- **SO**: Windows 11 (64-bit)
- **RAM**: 8GB ou superior
- **Armazenamento**: 2GB livres
- **Internet**: Banda larga para downloads rápidos

## 🛡️ Segurança e Privacidade

### Proteção de Dados
- **Criptografia**: Configurações e dados sensíveis criptografados
- **Autenticação Segura**: OAuth2 via Discord
- **Verificação de Licença**: Validação online sem exposição de dados
- **Logs Locais**: Processamento local sem envio de dados pessoais

### Conformidade
- **LGPD**: Conformidade com Lei Geral de Proteção de Dados
- **Stripe**: Pagamentos processados com segurança PCI DSS
- **Discord**: Autenticação via OAuth2 oficial

### Recursos Disponíveis
- **Base de Conhecimento**: Artigos e soluções
- **FAQ**: Perguntas frequentes
- **Tutoriais**: Guias passo-a-passo
- **Comunidade**: Fórum de usuários

## 📄 Informações Legais

### Licenciamento
- **Software Proprietário**: Código-fonte protegido por direitos autorais
- **Licença de Uso**: Termos específicos por plano de assinatura
- **Distribuição**: Proibida redistribuição não autorizada

### Termos de Uso
- **Uso Pessoal**: Licença para uso individual
- **Responsabilidade**: Usuário responsável pelo uso adequado
- **Conformidade**: Respeito aos termos de serviço do IMVU

## 🔗 Links Importantes

- **🌐 Site Oficial**: https://sterlaxvu.com/
- **💬 Discord**: https://discord.gg/WwREnjeHGZ
- **🎥 YouTube**: [Canal Oficial]
- **📧 Suporte**: [Email de Contato]


<div align="center">
  <strong>🎮 Desenvolvido com ❤️ para a comunidade IMVU</strong><br>
  <em>Transformando a experiência de extração de produtos IMVU</em>
</div>

---

> **Nota**: Este repositório contém apenas arquivos de configuração e documentação. O código-fonte completo é proprietário e não está disponível publicamente. Para adquirir uma licença, visite nosso site oficial.
