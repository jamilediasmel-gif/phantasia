# Phantasia 🏛️

**Ouve a conversa, transcreve e mostra a intenção e o tom por trás das palavras** — ironia, inveja, orgulho, maldade, raiva, manipulação, paz, carinho, tristeza.

> *"Você é apenas uma impressão, e não aquilo que parece ser."* — Epicteto, *Manual*

No estoicismo, **phantasia** é a *impressão*: aquilo que uma fala ou um fato parece ser à primeira vista. Os estoicos ensinavam a examinar cada impressão antes de dar o seu *assentimento* (concordar com ela). Este app faz isso com as conversas: mostra o tom provável, o trecho que gerou a impressão e deixa a decisão final com você.

Criado por **Jamile Dias (nome social Mel)** · JD 110

## Como funciona
1. Toque em **🎙️ Começar a ouvir**. O celular transcreve a conversa em português.
2. Toque em **⏹️ Parar** e depois em **🔍 Analisar intenção**.
3. O app mostra a intenção geral, os tons com barra de intensidade (%), o trecho que gerou cada tom e uma dica.

Também dá para **colar uma conversa do WhatsApp** e analisar.

## Dois modos de análise
| Modo | Como | Precisão |
|---|---|---|
| 📘 Simples (offline) | palavras e expressões-chave | básica, não entende bem ironia |
| ✨ IA (Claude) | coloque sua chave da API em ⚙️ Configurações | entende contexto, indiretas e ironia |

A chave fica salva só no seu aparelho.

## Privacidade
- O **áudio não é gravado** nem enviado. Só o texto transcrito fica no aparelho (histórico local).
- No modo IA, o texto é enviado para a API do Claude para ser analisado.
- Avise as pessoas que você está usando o app.
- O resultado é uma **leitura possível**, não uma prova do que a pessoa sentiu.

## Limitações
- A transcrição usa o reconhecimento de voz do navegador: funciona melhor no **Google Chrome (Android)**.
- Precisa ficar com o **app aberto e a tela ligada** enquanto ouve (o Android e o iPhone bloqueiam escuta em segundo plano).
- A transcrição não separa quem está falando.

## Publicar no GitHub Pages
1. Crie um repositório chamado `phantasia` e envie os arquivos: `index.html`, `manifest.json`, `icon.svg`, `sw.js`, `README.md`.
2. Vá em **Settings (Configurações) → Pages (Páginas)**.
3. Em **Branch (Ramo)** escolha `main` e `/ (root)`, e clique em **Save (Salvar)**.
4. Em 1–2 minutos o app estará em `https://SEU-USUARIO.github.io/phantasia/`.
5. No Chrome do celular, abra o link → menu ⋮ → **Adicionar à tela inicial**.

## Tecnologias
HTML, CSS e JavaScript puro · Web Speech API · API do Claude (Anthropic) · PWA

## Licença
MIT
