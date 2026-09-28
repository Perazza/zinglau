ZINGLAU — rastreador de grind do Black Desert (teste para Windows)

O Zinglau lê o log de itens obtidos da tela (OCR), conta o loot e calcula o
silver por hora com os preços do mercado. Ele só olha a imagem da tela: não
lê a memória do jogo nem mexe no processo do BDO.

COMO USAR
1. Descompacte a pasta Zinglau inteira onde quiser (ex.: Documentos).
   Se recebeu o arquivo .7z: abra com o 7-Zip (7-zip.org), senha: zinglau.
   Os arquivos precisam ficar juntos: zinglau.exe, onnxruntime.dll e models.
2. Abra o zinglau.exe.
   O Windows pode avisar "O Windows protegeu o computador" porque o programa
   não é assinado: clique em "Mais informações" e depois em "Executar assim
   mesmo".
3. Deixe o jogo em JANELA SEM BORDAS (Opções > Tela > Modo de janela), no
   monitor principal. Em tela cheia exclusiva o overlay não aparece.
4. No app, página "Log de loot": no jogo, abra ESC > Interface > Modo de
   edição de interface, deixe visíveis as caixas "Log de obtenção de item" e
   "Log de itens raros obtidos" e clique em Detectar.
5. Página "Sessão" > Iniciar sessão, e vá upar.
   Alt+F8 abre os controles no jogo (iniciar, pausar, encerrar, histórico).

SE DER ERRO AO INICIAR A SESSÃO
- Mensagem sobre onnxruntime: instale o Microsoft Visual C++ Redistributable
  (x64): https://aka.ms/vs/17/release/vc_redist.x64.exe
- A captura usa o monitor principal do Windows. Se o jogo estiver em outro
  monitor, mova o jogo ou troque o principal em Configurações > Tela.

ONDE FICAM OS DADOS
- Configuração e sessões: %APPDATA%\zinglau
- Cache de preços e ícones: %LOCALAPPDATA%\zinglau
Para desinstalar, apague a pasta do Zinglau e essas duas pastas.

Envie para quem te passou o programa: prints, o que aconteceu e, se puder,
a pasta %APPDATA%\zinglau\diagnostics (Preferências > Gravar diagnóstico).
