
# Cybersecurity-Skills

# Relatório de Auditoria de Segurança de TI: Botium Toys

## 📌 Visão Geral do Projeto
[cite_start]Este projeto consiste em uma auditoria interna de segurança realizada para a **Botium Toys**, uma empresa que busca expandir sua presença online e garantir a conformidade com padrões internacionais[cite: 1, 2]. [cite_start]O objetivo é mitigar riscos operacionais e evitar multas regulatórias[cite: 1, 2].

## 🔍 Resumo dos Achados (Checklist de Controles)

Com base no relatório de auditoria, aqui está o estado atual dos controles internos:

| Controle | Implementado | Observação do Auditor |
| :--- | :---: | :--- |
| **Princípio do Menor Privilégio** | ❌ | [cite_start]Todos os funcionários acessam dados de clientes no momento[cite: 4, 13]. |
| **Plano de Recuperação de Desastres** | ❌ | [cite_start]Inexistente, o que compromete a continuidade do negócio[cite: 4]. |
| **Políticas de Senhas** | ✅ | [cite_start]Existem, mas são mínimas e inadequadas contra ameaças[cite: 4]. |
| **Criptografia** | ❌ | [cite_start]Ausente, deixando dados PII/SPII e financeiros vulneráveis[cite: 5, 9, 11]. |
| **Gestão de Sistemas Legados** | ⚠️ | [cite_start]Sistemas em uso, mas sem cronograma de manutenção claro[cite: 5]. |
| **Segurança Física (CCTV/Fechaduras)** | ✅ | [cite_start]Implementada e funcional na sede e armazém[cite: 5, 6]. |



## 💡 Recomendações e Plano de Ação

[cite_start]Com base nos dados coletados[cite: 4, 5, 6], as seguintes ações são necessárias para fortalecer a segurança e garantir conformidade:

### 1. Controles de Acesso e Gestão de Identidade
* [cite_start]**Restrição de Acesso:** Implementar o Princípio do Menor Privilégio para reduzir o risco de violações[cite: 4, 21].
* [cite_start]**Separação de Funções:** Delegar a gestão da folha de pagamento e operações a pessoas diferentes para evitar fraudes, já que atualmente o CEO acumula ambas[cite: 4].
* [cite_start]**Gerenciamento de Senhas:** Adotar um sistema de gerenciamento de senhas para melhorar a produtividade e a segurança[cite: 5, 9].

### 2. Proteção de Dados e Conformidade (PCI DSS, GDPR, SOC)
* [cite_start]**Criptografia Obrigatória:** Implementar criptografia para proteger dados financeiros e de identificação pessoal (PII)[cite: 5, 9, 13].
* [cite_start]**Classificação de Dados:** Inventariar e classificar ativos para assegurar que cada tipo de dado receba o controle adequado[cite: 11].
* [cite_start]**Continuidade:** Criar um Plano de Recuperação de Desastres e protocolos de backups regulares[cite: 4, 5].

### 3. Monitoramento de Rede
* [cite_start]**Implementação de IDS:** Instalar um Sistema de Detecção de Intrusão para identificar invasores no departamento de TI[cite: 5].
* [cite_start]**Políticas de Privacidade:** Continuar reforçando as políticas já existentes entre os membros da equipe[cite: 11].

---

## ⚖️ Conclusão
[cite_start]Embora a Botium Toys possua segurança física adequada [cite: 6][cite_start], a falta de controles técnicos como criptografia e gestão de acessos cria riscos significativos para a conformidade GDPR e PCI DSS[cite: 9, 11]. A implementação imediata destas recomendações é vital para o crescimento sustentável da empresa.
