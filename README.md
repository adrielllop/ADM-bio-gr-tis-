# MespreX Control Center

Painel independente para criar, editar, ativar/desativar e remover os botões exibidos na bio.

O painel usa `GET/POST/PUT/DELETE /api/buttons`. Mantenha `window.MESPREX_API_BASE = ''` em `config.js` quando a API estiver no mesmo domínio. Se o painel estiver em outro endereço, informe a URL base do servidor que possui essa API.

A versão do projeto Manus já possui a API e o banco gerenciado integrados. Firebase não é necessário nesta versão.
