# João Inácio Imóveis — Site público

Vitrine pública da João Inácio Imóveis, desenvolvida/operada pela INFLINT.

## Escopo
- página pública responsiva;
- Cobertura e Área Privativa;
- fotos e vídeo;
- contato via WhatsApp e redes sociais;
- captação de leads, chat e eventos quando o Supabase estiver configurado.

## Supabase
Copie `config.example.js` para `config.js` e informe apenas a Project URL e a **publishable key** do projeto autorizado. Nunca use `service_role` no navegador.

O site continua com fallback estático enquanto o Supabase não estiver configurado.

## Publicação
Projeto estático compatível com Vercel. O arquivo `vercel.json` já inclui headers básicos de segurança.
