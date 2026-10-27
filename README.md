# MangaLibraryDXD
MangaLibraryDXD — v0.53x Beta
Leitor de mangás Android em Kotlin + Jetpack Compose (Material 3).
•
Programador do APK: MinatoDXD0IA (Developer By MinatoDXD I.A)
•
Data de Criação: 23/10/2026
•
Versão: 0.53x Beta (versionCode = 53)
Novidades da versão 0.53x Beta
1.
Remoção da Extensão ComicK:
◦
Retirada a extensão ComicK e seu acesso em todas as telas do aplicativo.
2.
Retirada de SakuraMangas, Taiyō e MangaLivreLT do Catálogo:
◦
SakuraMangas, Taiyō e MangaLivreLT não aparecem mais na aba Catálogo (supportsCatalog = false), mas permanecem disponíveis em Ajustes → Extensões e em Abrir Site de Mangá.
3.
Correção do Bloqueio "Conflito entre códigos" no SakuraMangas (sakuramangas.org):
◦
Desativada a injeção de scripts externos (ANTI_POPUP_JS e evalJs periódico), desativada a interceptação de recursos da página e adotado User-Agent Chrome 131 Mobile limpo (sem marcador ; wv e sem X-Requested-With), permitindo abrir o site normalmente sem o aviso de conflito.
4.
Aba de Notícias Desabilitada e Remoção da Notificação de Notícias:
◦
A opção Notícias na barra inferior da tela inicial foi desabilitada (enabled = false).
◦
Removida a opção Receber Notificações sobre as Notícias sobre Animes e Mangás dentro de Ajustes → Sistema → Notificações.
5.
Remoção da Introdução do APK:
◦
Removida a tela de introdução/splash e o áudio inicial (startup_ost.wav), abrindo o APK diretamente na tela inicial como era antes.
6.
Opção "Linguagem" Desabilitada em Ajustes → Extensões:
◦
A opção Linguagem dentro do tópico Extensões foi desabilitada nesta versão.
