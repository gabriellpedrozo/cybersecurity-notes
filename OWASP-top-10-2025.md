# OWASP Top 10 — 2025

## A01 — Broken Access Control

**O que é:** Falha no controle de acesso que permite que um usuário acesse recursos ou execute ações que não deveria.

**Exemplo:** Um usuário comum consegue acessar a conta ou os dados de outro usuário alterando um ID na URL.

## A02 — Security Misconfiguration

**O que é:** Configurações inseguras ou incorretas em sistemas, servidores ou aplicações que podem expor recursos ou informações.

**Exemplo:** Um servidor deixa uma página de administração acessível publicamente com credenciais padrão.

## A03 — Software Supply Chain Failures

**O que é:** Falhas de segurança em dependências, bibliotecas, sistemas de build ou outros componentes da cadeia de desenvolvimento e distribuição de software.

**Exemplo:** Uma aplicação utiliza uma biblioteca comprometida que permite executar código malicioso.

## A04 — Cryptographic Failures

**O que é:** Falhas no uso ou implementação de criptografia que podem causar exposição de dados sensíveis.

**Exemplo:** Uma aplicação armazena senhas ou informações pessoais sem proteção adequada.

## A05 — Injection

**O que é:** Falha que permite que dados fornecidos pelo usuário sejam interpretados como comandos ou código pela aplicação.

**Exemplo:** Um campo de login vulnerável a SQL Injection permite alterar a consulta ao banco de dados.

## A06 — Insecure Design

**O que é:** Falhas na arquitetura ou na lógica de segurança de uma aplicação, originadas durante seu projeto.

**Exemplo:** Um sistema permite que um usuário altere o preço de um produto durante uma compra sem validar essa alteração no servidor.

## A07 — Authentication Failures

**O que é:** Falhas nos mecanismos responsáveis por verificar a identidade dos usuários.

**Exemplo:** Um sistema permite tentativas ilimitadas de login, facilitando ataques de força bruta.

## A08 — Software or Data Integrity Failures

**O que é:** Falhas na verificação da integridade de software, código ou dados, permitindo que componentes não confiáveis sejam utilizados.

**Exemplo:** Uma aplicação instala automaticamente uma atualização sem verificar sua origem ou integridade.

## A09 — Security Logging & Alerting Failures

**O que é:** Falhas no registro, monitoramento ou geração de alertas sobre eventos de segurança.

**Exemplo:** Um sistema sofre várias tentativas de login suspeitas, mas não registra ou alerta os responsáveis.

## A10 — Mishandling of Exceptional Conditions

**O que é:** Tratamento inadequado de erros, exceções ou condições inesperadas que pode causar falhas de segurança.

**Exemplo:** Uma aplicação apresenta uma mensagem de erro contendo informações internas do servidor ou permite que uma operação continue mesmo após uma falha de segurança.

**O que eu aprendi:** Aprendi que erros e situações inesperadas também precisam ser tratados de forma segura, evitando a exposição de informações internas ou a continuação de operações que deveriam ser interrompidas.