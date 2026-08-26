# Cibersegurança para Pequenas e Médias Empresas: Utilizando o NotebookLM para Análise de Riscos e Boas Práticas

# Contexto
Pequenas e médias empresas estão cada vez mais dependentes de recursos tecnológicos para executar suas atividades. Sistemas em nuvem, redes corporativas, dispositivos móveis, aplicações web, serviços de terceiros e ferramentas de comunicação ampliam a produtividade, mas também aumentam a superfície de ataque. Ao contrário de grandes organizações, muitas pequenas e médias empresas possuem recursos financeiros e equipes de TI limitados, tornando a implementação de uma estratégia de segurança um desafio. Entre os riscos estão: Phishing, Ransomware, Malware, Roubo de credenciais, Vazamento de informações, Engenharia socia e Falta de treinamento dos colaboradores.

# Objetivo geral
Analisar os principais riscos de Cibersegurança enfrentados por pequenas e médias empresas e identificar boas práticas e controles que possam reduzir esses riscos.

# Objetivos específicos
 <ul>
  <li>Identificar as principais ameaças cibernéticas enfrentadas pelas PMEs;</li>
  <li>Compreender os principais controles de segurança recomendados;</li>
  <li>Investigar a importância de políticas de segurança;</li>
  <li>Avaliar a importância da conscientização dos usuários;</li>
  <li>Estudar mecanismos como MFA, backup, firewall e segmentação de rede;</li>
  <li>Compreender como o gerenciamento de riscos pode auxiliar na proteção da organização;</li>
  <li>Utilizar o NotebookLM para analisar e relacionar diferentes fontes;</li>
  <li>Desenvolver um miniguia de Cibersegurança aplicável a pequenas e médias empresas.</li>
</ul>

# Curadoria de Fontes
Durante o projeto foram selecionadas fontes de pesquisa em conformidade com os objetivos apresentados. Dentre fontes como vídeos, arquivos em PDF. Dessa forma, seguem as fontes pesquisadas com os seus respectivos links de acesso. 
<ul>
  <li>Identificar as principais ameaças cibernéticas enfrentadas pelas PMEs - https://www.youtube.com/watch?v=-t7l3GRK_L0;</li>
  <li>Cibersegurança é desafio para pequenas e médias empresas - https://proximonivel.claro.com.br/ciberseguranca-pme/;</li>
  <li>18 dicas de Cibersegurança para pequenas empresas - https://www.pipedrive.com/pt/blog/dicas-de-ciberseguranca;</li>
  <li>O Impacto da Cibersegurança nas Pequenas e Médias Empresas Brasileiras - https://horizontes.sbc.org.br/index.php/2025/03/o-impacto-da-ciberseguranca-nas-pequenas-e-medias-empresas-brasileiras/</li>
</ul>

# Engenharia de Prompts e "Cicatrizes": 
<b>Experimento 1 — Prompt inicial</b>

<b>Prompt:</b> Quais são os principais riscos de Cibersegurança para pequenas empresas?

<b>Problema:</b> A resposta pode ser muito genérica. O prompt pode listar riscos como phishing, ransomware,  malware, senhas fracas e vazamento de dados. Porém não necessariamente explica prioridade, impacto ou mitigação. 

<b>Aprendizado:</b> Percebe-se que perguntas muito amplas geravam respostas pouco específicas.

<b>Experimento 2 — Prompt contextualizado</b>

<b>Prompt:</b> Com base exclusivamente nas fontes deste notebook, identifique os principais riscos de Cibersegurança enfrentados por pequenas e médias empresas. Para cada risco, apresente: descrição, causa, impacto potencial, nível de criticidade e medidas de mitigação. Cite a fonte utilizada para cada afirmação.

Esta configuração de prompt é muito melhor porque define: Fonte + contexto + tarefa + formato + critério de evidência.

<b>Experimento 3 — Cenário realista</b>

<b>Prompt:</b> Considere uma pequena empresa com 50 funcionários, uma rede Wi-Fi corporativa, acesso à Internet, Microsoft 365, computadores Windows, sistema ERP em nuvem e ausência de uma equipe dedicada de segurança. Com base exclusivamente nas fontes disponíveis, identifique os principais riscos dessa organização e proponha um plano de segurança priorizado.

<b>Aprendizado:</b> com prompts baseados em cenários, percebe-se que o NotebookLM está sendo utilizado para resolução de problemas, e não simplesmente para responder perguntas.

# Miniguia de Estudos

<b>Fundamentos de Cibersegurança</b>

Confidencialidade: Garantir que informações sejam acessadas somente por pessoas autorizadas.

Integridade: Garantir que os dados não sejam alterados indevidamente.

Disponibilidade: Garantir que sistemas e informações estejam disponíveis quando necessários.

<b>Principais ameaças às PMEs</b>

<b>1- Phishing</b>

Tentativas de enganar usuários para obter credenciais ou informações.

Principal vetor: fator humano.

Prevenção:

<ul>
 <li>Treinamento;</li>
 <li>MFA;</li> 
 <li>Filtros de e-mail;</li>
 <li>Autenticação;</li>
 <li>Conscientização.</li>
 </ul>
 
<b>2- Ransomware</b>

Malware utilizado para impedir o acesso aos dados ou sistemas, frequentemente associado à extorsão.

Medidas importantes:
<ul>
 <li>Backups; </li>
 <li>Segmentação; </li>
 <li>Atualizações; </li>
 <li>Antimalware; </li>
 <li>MFA;</li>
 <li>Treinamento.</li>
</ul>

<b>3- Roubo de credenciais</b>

O atacante obtém usuário e senha por phishing, vazamentos, reutilização de senhas ou outras técnicas.

Controles:

<ul>
 <li>MFA;</li>
 <li>senhas fortes;</li> 
 <li>gerenciadores de senhas; </li>
 <li>princípio do menor privilégio. </li>
</ul>

<br>Controles essenciais para uma PME</br>
<ul>
 <li>MFA; <li> 
 <li>Políticas de senhas;  <li>
 <li>Backup;  <li>
 <li>Atualizações e patches; <li> 
 <li>Firewall;  <li>
 <li>Segmentação de rede; <li> 
 <li>Proteção contra malware;  <li>
 <li>Treinamento dos colaboradores;  <li>
 <li>Política de Segurança da Informação; <li> 
 <li>Plano de resposta a incidentes. <li> 
________________________________________
#Glossário
Termo	Definição
MFA: Autenticação utilizando múltiplos fatores
Firewall: Controle do tráfego de rede
Phishing: Fraude para induzir usuários a fornecer informações
Ransomware: 	Malware utilizado para bloquear/criptografar dados e exigir resgate
Malware:	Software desenvolvido para realizar ações maliciosas
VPN:	Tecnologia para estabelecer comunicação protegida através de uma rede
IAM:	Gerenciamento de identidades e acessos
Zero Trust:	Modelo baseado na premissa de não confiar implicitamente
Backup:	Cópia de segurança dos dados



