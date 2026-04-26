<div align="center">

<img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Sprint%20Atual-1%20%E2%80%94%20Onda%201-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Issues-24-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/Plataforma-Mobile-purple?style=for-the-badge" />

# Na Hora!
### Marketplace de serviços por demanda

*Conectamos pessoas que precisam de um serviço a profissionais autônomos qualificados disponíveis na sua região — na hora em que você precisa.*

</div>

---

## 📌 Sobre o projeto

O **Na Hora!** é um aplicativo móvel que funciona como um marketplace de serviços por demanda. O cliente publica um pedido descrevendo o que precisa, profissionais próximos recebem a notificação e enviam propostas, e o cliente escolhe a melhor oferta levando em conta preço, avaliação, distância e portfólio.

### Problema que resolve
- ❌ Contratar um eletricista, encanador ou diarista hoje depende de indicação, grupos de bairro ou empresas com preços inflados
- ❌ O profissional autônomo depende de boca-a-boca e não consegue comprovar sua reputação fora do círculo de clientes que já atendeu
- ✅ O Na Hora! resolve os dois lados ao mesmo tempo

---

## 🏗️ Arquitetura do produto

```
Cliente                          Profissional
   │                                  │
   ├── Publica pedido                 ├── Recebe notificação
   ├── Recebe propostas               ├── Envia proposta
   ├── Conversa via chat              ├── Conversa via chat
   ├── Aceita proposta                ├── Executa serviço
   ├── Confirma conclusão             ├── Marca como concluído
   └── Avalia profissional            └── Avalia cliente
```

---

## 📋 Cronograma — 7 Sprints (Ondas)

| Sprint | Onda | Tema | UHs | Status |
|--------|------|------|-----|--------|
| Sprint 1 | Onda 1 | Fundação | UH-04, UH-05, UH-12 | ⏳ Aguardando |
| Sprint 2 | Onda 2 | MVP Core — Pedidos e Perfil | UH-01, UH-13, UH-11, UH-21 | ⏳ Aguardando |
| Sprint 3 | Onda 3 | MVP Core — Chat e Atribuição | UH-03, UH-27, UH-19 | ⏳ Aguardando |
| Sprint 4 | Onda 4 | Busca, Finalização e Feedback | UH-07, UH-09, UH-31, UH-15 | ⏳ Aguardando |
| Sprint 5 | Onda 5 | Gestão de Pedidos e Busca | UH-06, UH-02, UH-10 | ⏳ Aguardando |
| Sprint 6 | Onda 6 | Interação Direta | UH-08, UH-25, UH-28, UH-18 | ⏳ Aguardando |
| Sprint 7 | Onda 7 | Perfil e Históricos | UH-14, UH-17, UH-30 | ⏳ Aguardando |

> **MVP 1** concluído na Onda 6 · **MVP 2** concluído na Onda 7

---

## 📚 Documentação

| Documento | Descrição | Link |
|---|---|---|
| 📄 Sistema Completo v4 | Visão geral, fluxos, regras de negócio e telas | [Ver documento](https://docs.google.com/SEU-LINK-AQUI) |
| 📋 Casos de Uso | UC-01 a UC-38 detalhados | [Ver documento](https://docs.google.com/SEU-LINK-AQUI) |
| 📝 Histórias de Usuário | UH-01 a UH-38 com critérios de aceitação | [Ver documento](https://docs.google.com/SEU-LINK-AQUI) |
| 📊 Mapeamento UC × UH | Planilha de rastreabilidade | [Ver planilha](https://docs.google.com/SEU-LINK-AQUI) |
| 🗂️ Ondas de Funcionalidades | Priorização e esforço por onda | [Ver documento](https://docs.google.com/SEU-LINK-AQUI) |

---

## 🗂️ Organização do repositório

| Recurso | Link |
|---|---|
| 📌 Board — Sprint Planning | [Ver no GitHub Projects](https://github.com/orgs/Projeto-NaHora/projects/1) |
| 🐛 Issues | [Ver todas as issues](https://github.com/Projeto-NaHora/nahora-app/issues) |
| 🎯 Milestones | [Ver milestones](https://github.com/Projeto-NaHora/nahora-app/milestones) |
| 🏷️ Labels | [Ver labels](https://github.com/Projeto-NaHora/nahora-app/labels) |

---

## 👥 Time

| Membro | Papel | GitHub |
|---|---|---|
| — | — | — |
| — | — | — |
| — | — | — |
| — | — | — |
| — | — | — |

---

## 🛠️ Stack tecnológica

> *A definir pelo time*

---

## 🚀 Como contribuir

1. Escolha uma issue no board com status `Todo`
2. Crie uma branch seguindo o padrão:
```bash
git checkout -b feat/UH-04-cadastro-cliente
```
3. Desenvolva e faça commit:
```bash
git commit -m "feat(auth): cadastro de cliente — UH-04"
```
4. Abra um Pull Request referenciando a issue:
```
Closes #1
```
5. Aguarde revisão do time (`In Review`) e merge (`Done`)

---

## 📏 Convenção de branches

| Prefixo | Uso |
|---|---|
| `feat/` | Nova funcionalidade |
| `fix/` | Correção de bug |
| `docs/` | Documentação |
| `refactor/` | Refatoração |
| `test/` | Testes |

---

## 🏷️ Labels do projeto

| Grupo | Labels |
|---|---|
| Tipo | `user-story` `bug` `documentation` `refactor` `test` |
| Sprint | `sprint-1` `sprint-2` `sprint-3` `sprint-4` `sprint-5` `sprint-6` `sprint-7` |
| Módulo | `auth` `pedidos` `chat` `pagamento` `perfil` `notificações` `geo` |
| Prioridade | `prioridade-alta` `prioridade-media` `prioridade-baixa` |

---

<div align="center">

**Na Hora!** · Projeto acadêmico · Abril/2026

</div>
