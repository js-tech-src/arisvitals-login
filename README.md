# arisvitals-login

Pagina estatica de login usada pela ponte OAuth do Aris (ver `js-tech-src/arisvitals`, ADR-004).
Publica de proposito: nao contem nenhum segredo, so o formulario. A troca de credenciais
acontece via fetch() JSON contra a Edge Function do Supabase.
