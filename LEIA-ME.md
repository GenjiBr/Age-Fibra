# Landing page Age Fibra – Gabriel de Lima

## Abrir no VS Code
1. Extraia o .zip.
2. No VS Code: File > Open Folder... > selecione a pasta `age-fibra-site`.
3. Para ver a página: clique com o botão direito em `index.html` > "Open with Live Server"
   (instale a extensão "Live Server" se não tiver) ou dê dois cliques no arquivo pelo Explorer/Finder.

## Publicar na Vercel pelo VS Code (terminal)
Requer Node.js instalado (nodejs.org).

    npm i -g vercel
    vercel            # primeira vez: faz login e cria o projeto (aceite as opções padrão)
    vercel --prod     # publica a versão final

Para atualizar depois: edite o index.html, salve e rode `vercel --prod` de novo.

## Onde editar
- Textos, planos e preços: procure pelo texto direto no index.html (Ctrl+F).
- WhatsApp: procure por `5561920075118`.
- Cores: no topo do arquivo, em `:root` (--laranja, --azul...).
