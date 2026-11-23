# GEMONIT · Governança do Monitoramento

Sistema da Gerência de Monitoramento (SMA/SCPMA) que substitui a planilha de governança.

- **Telas:** este repositório (GitHub Pages). Não guarda dados.
- **Dados:** Supabase do HUB (projeto *Agenda SCPMA*), tabelas `gemonit_*`, com RLS.
- **Login:** o mesmo do HUB. Só entra quem está em `gemonit_membros` (tela Administração).
- **Anexos:** bucket privado `gemonit-anexos`.
- **IA:** Edge Function `gemonit-ia`, usando o segredo `GEMINI_API_KEY` (o mesmo da ASID).

Nunca coloque neste repositório planilhas, relatórios do SIPLAM ou a chave secreta (service_role) do Supabase.
A chave publicável que está no `index.html` foi feita para ficar no navegador.
