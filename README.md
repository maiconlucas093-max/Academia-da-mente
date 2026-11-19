# Academia da Mente — pacote de arquitetura e interface

## O que está incluído

Este ZIP reúne a estrutura HTML da Etapa 1 e a identidade visual CSS da Etapa 2.

- Painel principal em `index.html`.
- Páginas institucionais em `pages/`.
- Sistema visual global em `style.css`.
- Componentes reutilizáveis em `css/components.css`.
- Estilos do painel em `css/dashboard.css`.
- Responsividade em `css/responsive.css`.
- Módulos JavaScript separados em `js/`, ainda reservados para as próximas etapas.
- Pastas `assets/images/`, `assets/icons/` e `aulas/` criadas e vazias.

## Como abrir

1. Extraia a pasta `academia-da-mente`.
2. Abra `index.html` no navegador.
3. Navegue pelos links do menu e pelas páginas internas.

Também pode usar um servidor estático local para desenvolvimento.

## Publicação no GitHub Pages

1. Envie o conteúdo da pasta para a raiz do repositório GitHub.
2. Em Settings → Pages, selecione a branch e a pasta de publicação.
3. Aguarde a publicação e abra o endereço informado pelo GitHub.

Os caminhos dos arquivos são relativos, para permitir publicação em subdiretório de repositório.

## Escopo e limites desta versão

- A interface HTML/CSS está implementada.
- Não há cursos, módulos, aulas, textos didáticos ou áudios cadastrados.
- Não há botões de funcionalidades futuras simulados como se estivessem ativos.
- JavaScript funcional, player, progresso, autenticação e administração serão desenvolvidos nas próximas etapas.
- A tipografia usa fontes do Google Fonts com fontes locais de fallback; se estiver sem internet, o navegador utilizará as alternativas instaladas.

## Próximas etapas

3. Navegação e funcionalidades JavaScript.
4. Departamentos e estrutura acadêmica.
5. Cursos, módulos e aulas.
6. Player de áudio.
7. Ferramentas de aprendizagem.
8. Painel administrativo.
9. Integração com Supabase.
10. Testes, correções e publicação.

## Segurança futura

Nunca exponha `service_role`, senhas ou credenciais administrativas no JavaScript público. A autorização deverá ser aplicada no backend, com políticas de Row Level Security no Supabase.
