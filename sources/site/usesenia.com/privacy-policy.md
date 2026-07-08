# Source: https://usesenia.com/privacy-policy

[Voltar para o início](https://usesenia.com/)

# Política de Privacidade

Última atualização: 08/07/2026

## 1\. Introdução

A Senia, nome fantasia operado pela **AILA TECNOLOGIA DA INFORMACAO LTDA** ("nós", "nosso" ou "nossa"), está comprometida em proteger a privacidade e os dados pessoais de todos os usuários de nossa plataforma de secretária virtual com inteligência artificial para clínicas médicas. Esta Política de Privacidade descreve como coletamos, usamos, armazenamos e protegemos suas informações pessoais e dados de pacientes, em conformidade com a Lei Geral de Proteção de Dados (LGPD) — Lei nº 13.709/2018.

**Identificação do Operador**

Razão social: AILA TECNOLOGIA DA INFORMACAO LTDA

CNPJ: 63.341.848/0001-02

Endereço: R. Pais Leme, 215, Conj 1713, Pinheiros, São Paulo/SP — CEP 05.424-150

Nas relações com clínicas privadas, a Senia atua como **operadora** de dados pessoais — a clínica contratante é a controladora, definindo finalidades e meios essenciais do tratamento. Em contratações com o Poder Público (licitações), o órgão contratante é o controlador e a Senia opera nos termos do Acordo de Tratamento de Dados (DPA) celebrado.

## 2\. Dados Coletados

Para fornecer nossos serviços de secretária virtual automatizada, coletamos as seguintes categorias de dados:

### 2.1. Dados da Clínica

- Nome da clínica, CNPJ, endereço e informações de contato
- Dados de profissionais de saúde (nome, CRM, especialidade, horários)
- Informações de serviços oferecidos e valores
- Dados de integração com sistemas ERP e Google Calendar

### 2.2. Dados dos Pacientes

- Nome completo, CPF, data de nascimento
- Telefone e informações de contato via WhatsApp
- Histórico de consultas e agendamentos
- Informações de convênios médicos
- Conversas com a assistente virtual (logs de atendimento)

### 2.3. Dados Técnicos

- Logs de acesso e uso da plataforma
- Endereço IP, tipo de navegador e dispositivo
- Dados de performance e métricas de uso

## 3\. Finalidade do Tratamento de Dados

Utilizamos os dados coletados para as seguintes finalidades:

- Fornecer serviços de secretária virtual automatizada via WhatsApp
- Gerenciar agendamentos, confirmações e cancelamentos de consultas
- Integrar com sistemas ERP da clínica para sincronização de dados
- Enviar notificações e lembretes aos pacientes
- Processar e responder dúvidas através de nossa IA conversacional
- Melhorar continuamente nossos serviços através de análise de dados agregados
- Cumprir obrigações legais e regulatórias
- Prevenir fraudes e garantir a segurança da plataforma

## 4\. Base Legal para o Tratamento

Os dados de paciente tratados pela Senia são, em regra, **dados pessoais sensíveis de saúde** (Art. 5º, II da LGPD). O tratamento fundamenta-se nas seguintes hipóteses do Art. 11 da LGPD:

- **Tutela da saúde (Art. 11, II, "f"):** tratamento exclusivamente em procedimento realizado por profissionais ou serviços de saúde — base padrão para a operação cotidiana com clínicas contratantes.
- **Cumprimento de obrigação legal/regulatória (Art. 11, II, "a"):** guarda de prontuário (Resolução CFM 1.821/2007 e Lei 13.787/2018) e demais obrigações regulatórias aplicáveis à saúde.
- **Execução de políticas públicas (Art. 11, II, "b"):** quando a contratante é órgão público no âmbito de licitação ou convênio.
- **Consentimento específico e destacado (Art. 11, I):** apenas para finalidades secundárias que não façam parte da prestação central do serviço (ex.: pesquisas, comunicações de marketing).

Para dados não sensíveis (cadastro da clínica, dados de profissionais e usuários administrativos), a base legal aplicável é **execução de contrato** (Art. 7º, V) e, quando cabível, **legítimo interesse** (Art. 7º, IX), notadamente para segurança da plataforma.

## 5\. Compartilhamento de Dados

Os dados coletados podem ser compartilhados apenas nas seguintes situações:

- Com a clínica contratante e seus profissionais autorizados
- Com provedores de serviços essenciais (hospedagem, processamento, comunicação)
- Com APIs de terceiros integradas (WhatsApp Business API, sistemas ERP, Google Calendar)
- Quando exigido por lei, ordem judicial ou autoridade competente

**Importante:** Nunca vendemos ou alugamos dados pessoais para terceiros. Todos os parceiros são cuidadosamente selecionados e vinculados por contratos de confidencialidade.

## 6\. Suboperadores e Transferência Internacional

Para operar a plataforma, contamos com suboperadores selecionados que tratam dados pessoais em nosso nome — principalmente provedores de infraestrutura em nuvem, inteligência artificial e comunicação. A lista completa, atualizada, com a finalidade de cada um e o país de processamento, está disponível em [/lgpd](https://usesenia.com/lgpd).

Parte do tratamento ocorre fora do Brasil (notadamente Estados Unidos, para serviços de IA, hospedagem e WhatsApp Business). Cada transferência internacional ocorre sob salvaguardas contratuais equivalentes aos requisitos do Art. 33 da LGPD.

## 7\. Segurança dos Dados

Implementamos medidas técnicas e administrativas proporcionais ao risco. Adotamos, em produção:

- Comunicação cifrada (TLS) em todas as conexões com a plataforma
- Isolamento por tenant via Row-Level Security no PostgreSQL — cada clínica acessa apenas seus dados
- Segregação de credenciais privilegiadas (chaves de serviço confinadas ao lado servidor)
- Retenção curta automática de mídia (áudios expirados em 30 dias)
- Logs de interação com IA para rastreabilidade das respostas automatizadas
- Backups gerenciados com Point-in-Time Recovery
- Treinamento periódico da equipe em proteção de dados

Em implementação como parte de nosso roadmap de adequação: criptografia de coluna para identificadores diretos do paciente, MFA obrigatório para usuários administrativos, registros ampliados de auditoria de acesso e fluxos self-service de exercício de direitos do titular.

## 8\. Retenção de Dados

Os dados pessoais são mantidos pelo tempo mínimo necessário para cumprir as finalidades para as quais foram coletados, respeitando prazos legais aplicáveis:

- **Prontuário e observações clínicas:** 20 anos a partir do último registro (Resolução CFM 1.821/2007 e Lei 13.787/2018)
- **Registros de agendamento** (data, status, profissional): 5 anos
- **Mensagens texto de WhatsApp:** 6 meses
- **Áudios e imagens de WhatsApp:** 30 dias (eliminação automática)
- **Logs de interação com IA:** 12 meses
- **Logs de auditoria de acesso:** 24 meses
- **Dados de faturamento:** conforme legislação tributária vigente (mínimo 5 anos)
- **Contas administrativas inativas:** anonimização após 24 meses sem login

## 9\. Direitos dos Titulares

Em conformidade com o Art. 18 da LGPD, você tem os seguintes direitos:

- **Confirmação e acesso:** Saber se tratamos seus dados e acessá-los
- **Correção:** Solicitar correção de dados incompletos ou desatualizados
- **Anonimização, bloqueio ou eliminação:** Requisitar a remoção de dados desnecessários
- **Portabilidade:** Receber seus dados em formato estruturado e interoperável
- **Informação sobre compartilhamento:** Saber com quem compartilhamos seus dados
- **Revogação de consentimento:** Retirar consentimento a qualquer momento
- **Oposição:** Opor-se ao tratamento de dados em determinadas situações

Para exercer qualquer um desses direitos, use o canal dedicado em [/lgpd](https://usesenia.com/lgpd) ou escreva para **legal@usesenia.com.br**. Responderemos em até 15 dias.

## 10\. Cookies e Tecnologias Similares

Utilizamos cookies e tecnologias similares para melhorar a experiência do usuário, analisar o uso da plataforma e personalizar conteúdo. Você pode gerenciar suas preferências de cookies através das configurações do seu navegador.

## 11\. Alterações nesta Política

Podemos atualizar esta Política de Privacidade periodicamente. Notificaremos sobre alterações significativas através de e-mail ou aviso na plataforma. Recomendamos que você revise esta política regularmente.

## 12\. Contato

Para questões relacionadas à privacidade e proteção de dados, entre em contato:

**Encarregado de Proteção de Dados (DPO)**

E-mail: legal@usesenia.com.br

Canal do titular: [usesenia.com.br/lgpd](https://usesenia.com/lgpd)

Esta Política de Privacidade está em conformidade com a Lei Geral de Proteção de Dados (LGPD) - Lei nº 13.709/2018 e demais legislações aplicáveis.