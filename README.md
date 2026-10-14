# Mentor Sistêmico

Aplicação Next.js para conversas fundamentadas em 18 livros no Supabase.

## Configuração
1. Importe o repositório na Vercel.
2. Configure `NEXT_PUBLIC_SUPABASE_URL`, `NEXT_PUBLIC_SUPABASE_ANON_KEY`, `SUPABASE_SERVICE_ROLE_KEY`, `OPENAI_API_KEY`, `OPENAI_CHAT_MODEL` e `OPENAI_EMBEDDING_MODEL`.
3. Configure o Supabase Auth para permitir os usuários e o domínio Vercel.
4. Importe e indexe os trechos dos livros no Supabase antes de conversar.

**Importante:** os PDFs e os embeddings ainda não foram enviados ao Supabase. Não publique chaves secretas no GitHub. A API da OpenAI pode gerar custos. O microfone usa reconhecimento de voz do navegador, cuja disponibilidade varia por dispositivo.
