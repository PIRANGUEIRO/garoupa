# Repository Audit — Garoupa

Gerado em 2026-09-17.

## Inventário
- Tipo: Workflow n8n (sem código Python/JS standalone)
- Nodes: 22 (Manual Trigger, Schedule, Settings, GS Read, Loops, HTTP Request, If, Process, Save, Status, Backoff)
- APIs: Google Maps Places (mock), Google Sheets (mock)
- Dados: Google Sheets (3 abas)
- Infra: n8n self-hosted v1.89.2 (Docker localhost:5678), workflow Id GlL8pHZGLU0FRn19
- Testes: integração manual n8n→Sheets, n8n→Maps (OK na doc)
- Docs: 8 mds no Vault (Requisitos, Planejamento, Prototipo, etc.)
- Código: não há repo de código — workflow apenas

## Classificação
B — Portfolio Secundário (problema real B2B, 1.247 leads coletados demo, mas sem código próprio)

## Segurança
- Credenciais OAuth 2.0 via n8n credentials (não versionadas)
- URLs reais trocadas por api.exemplo.com mock

## Score
Complexity 3, Architecture 3, Code Quality 2 (workflow visual), Docs 4, Testing 1, Reproducibility 3, Real-world 4, Relevance 3 → médio 2.9
