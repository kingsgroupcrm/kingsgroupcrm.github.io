# ADR CRM — build estático

Build estático do frontend do ADR CRM (ADR Snow Management + ADR Pro Builders),
publicado via GitHub Pages.

Este repositório **não** contém código-fonte, migrations, credenciais
administrativas nem dados de clientes. A única chave presente é a
**publishable (anon) key** do Supabase, pública por arquitetura: todo o acesso a
dados é controlado por Row Level Security e por permissões de Business Unit no
banco. O sistema exige login e não possui cadastro público.
