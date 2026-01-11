# PRD Prompt para Sistemas Profissionais

Prompt otimizado para geração de Product Requirements Documents (PRD) para sistemas técnicos complexos, B2B/Enterprise, IoT/Industrial e contextos regulados.

## 🎯 Contexto

Este prompt foi desenvolvido a partir da necessidade de criar PRDs executáveis para sistemas industriais complexos, onde a versão original (focada em MVPs consumer) foi aprimorado complementando áreas como:

- Arquitetura e integrações
- Requisitos não-funcionais detalhados (SLA/SLO, observabilidade)
- Infraestrutura e deployment
- Viabilidade técnica e TCO
- Compliance e regulação

## 🚀 Diferenciais

- **26 seções estruturadas** cobrindo desde visão de produto até disaster recovery
- **Foco em viabilidade**: não só "o que fazer", mas "como fazer" e "quanto custa"
- **Contexto-aware**: adapta perguntas para B2B, Industrial, IoT ou contextos regulados
- **Operação incluída**: runbooks, observabilidade, CI/CD desde o início

## 📋 Como usar

1. Copie o conteúdo de [`PROMPT.md`](./PROMPT.md)
2. Cole no ChatGPT, Claude ou Gemini
3. Substitua `[COLE AQUI A SUA IDEIA DESESTRUTURADA]` pelo seu brain dump
4. Responda às perguntas estruturadas
5. Digite `/GERAR` quando estiver pronto

## 🎓 Quando usar este prompt vs. o original

**Use este prompt se seu projeto envolve:**
- ✅ Sistemas B2B/Enterprise
- ✅ Integração com infraestrutura existente
- ✅ IoT, edge computing ou hardware
- ✅ Contextos regulados (LGPD, HIPAA, ISO, etc.)
- ✅ Requisitos de SLA/uptime críticos
- ✅ Necessidade de TCO e análise de viabilidade

**Use o prompt original se:**
- ✅ MVP consumer simples
- ✅ Projeto exploratório/validação de ideia
- ✅ Não há integrações complexas
- ✅ Escopo bem definido e pequeno

## 📚 Exemplos

Veja PRDs de exemplo na pasta [`examples/`](./examples/):
- Sistema de rastreabilidade industrial ([exemplo](./examples/prd-exemplo-sistema-industrial.md))
- Plataforma B2B enterprise ([exemplo](./examples/prd-exemplo-b2b-enterprise.md))
- Solução IoT ([exemplo](./examples/prd-exemplo-iot.md))

## 🛠️ Estrutura do PRD gerado

O prompt gera PRDs com 8 partes principais:

1. **Visão de Produto** (4 seções)
2. **Requisitos Funcionais** (2 seções)
3. **Requisitos Não-Funcionais** (5 seções)
4. **Arquitetura e Infraestrutura** (3 seções)
5. **Operação e Deployment** (3 seções)
6. **Viabilidade e Riscos** (4 seções)
7. **Métricas e Custos** (2 seções)
8. **Apêndices** (3 seções)

Total: **26 seções** cobrindo aspectos técnicos, operacionais e de negócio.

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você:
- Identificou gaps em contextos específicos
- Tem sugestões de melhoria
- Criou adaptações para outros domínios

Abra uma issue ou PR.

## 📝 Changelog

Veja [CHANGELOG.md](./CHANGELOG.md) para histórico de versões.

## 📄 Licença

MIT License - use livremente, comercialmente ou não.

## 👤 Autor

**Anderson M Neves**  
Tech Leader @ Viposa S.A.  


- LinkedIn: [https://linkedin.com/in/andersonmnevs](https://www.linkedin.com/in/andersonneves-cloudaws-dev/)
- GitHub: [@andersonmnevs](https://github.com/andersonmnevs)

## 🙏 Créditos

Este prompt é uma evolução do [prompt original](link-do-post-do-cicero) criado por Cícero da Comunidade Lendária, adaptado para contextos técnicos complexos.

---

**⭐ Se este projeto foi útil, considere dar uma estrela!**
