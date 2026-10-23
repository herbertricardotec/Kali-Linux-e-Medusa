# Projeto de Auditoria de Segurança com Kali Linux e Medusa

## Sobre o Projeto
Descrição breve do que foi feito, objetivos de aprendizado e o que este repositório documenta.

**Ambiente controlado:** VirtualBox com rede host-only (isolada).  
**Máquinas:** Kali Linux (atacante) + Metasploitable 2 / DVWA (alvo).  
**Ferramenta principal:** Medusa (e outras que você tenha utilizado).

⚠️ **Aviso importante:** Todo o trabalho foi realizado exclusivamente em ambiente de laboratório isolado, com autorização, para fins educacionais. Não utilize estas técnicas em sistemas reais sem permissão explícita.

## Objetivos
- Compreender ataques de força bruta em diferentes serviços
- Utilizar Kali Linux e Medusa em ambiente controlado
- Documentar processos técnicos de forma clara
- Identificar vulnerabilidades e propor mitigações
- Criar portfólio técnico no GitHub

## Configuração do Ambiente
Descreva (sem comandos de ataque):
- Versões das VMs utilizadas
- Tipo de rede configurada no VirtualBox (host-only)
- IPs das máquinas (exemplo genérico)
- Serviços que estavam ativos no alvo

## Cenários Realizados
### 1. Força bruta em serviço FTP
- Objetivo
- Wordlist utilizada (descreva ou linke o arquivo)
- Resultado observado
- Validação de acesso (se houve)

### 2. Tentativas automatizadas em formulário web (DVWA)
- Nível de segurança do DVWA utilizado
- Abordagem geral
- Resultado

### 3. Password spraying / enumeração em SMB
- Enumeração de usuários (método geral)
- Abordagem de spraying
- Resultado

## Wordlists Utilizadas
- Liste os arquivos
- Explique como foram criadas ou adaptadas
- Tamanho e conteúdo (sem expor senhas reais sensíveis)

## Resultados e Evidências
- Resumo do que funcionou / não funcionou
- Capturas de tela (coloque na pasta `/images` e referencie aqui)
- Lições aprendidas

## Recomendações de Mitigação
- Contas e senhas: política de senhas fortes, MFA, lockout após tentativas
- Serviços de rede: desabilitar serviços desnecessários, restringir acesso por IP/firewall
- FTP: preferir SFTP/FTPS, desabilitar autenticação anônima
- Web (DVWA/formulários): rate limiting, CAPTCHA, WAF, validação server-side
- SMB: desabilitar SMBv1, usar autenticação forte, restringir acesso, monitoramento
- Geral: atualizações, segmentação de rede, logging e SIEM, princípio do menor privilégio

## Lições Aprendidas e Reflexões
O que você aprendeu sobre força bruta, importância de ambientes isolados, ética em segurança ofensiva, etc.

## Como Reproduzir (alto nível)
Apenas orientação genérica de setup de VMs e rede isolada. Não inclua os passos de ataque.

## Referências
- Documentação oficial das ferramentas
- Aulas da DIO
- Materiais de estudo que você consultou

## Autor
Seu nome  
Link do perfil LinkedIn / GitHub  
Data
