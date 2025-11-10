
# Roadmap do Salsilauncher

## Fase 1 — Estrutura Inicial (Concluída)
- [x] Criar backend FastAPI básico
- [x] Criar frontend React com Vite
- [x] Criar comunicação frontend → backend
- [x] Estruturar rotas iniciais e layout básico
- [x] Implementar endpoint GET /games com dados estáticos
- [x] Configurar ambiente de desenvolvimento

## Fase 2 — Fundação do Sistema de Jogos (Em andamento)
- [ ] Implementar banco de dados SQLite
- [ ] Criar modelos persistentes de jogos
- [ ] Criar CRUD completo (adicionar, editar, remover jogos)
- [ ] Implementar API para upload de imagens de jogos
- [ ] Criar modal para adicionar jogos manualmente
- [ ] Implementar carregamento e tratamento de erros no frontend

## Fase 3 — Biblioteca e Organização
- [ ] Criar layout completo da biblioteca
- [ ] Criar página individual por jogo
- [ ] Criar sistema de busca
- [ ] Criar filtros (por gênero, categoria, tempo jogado, favoritos)
- [ ] Criar categorias personalizadas
- [ ] Implementar ordenação por mais jogados, recentes etc.

## Fase 4 — Sistema de Execução de Jogos
- [ ] Implementar execução direta de jogos no Windows
- [ ] Implementar contagem de horas jogadas
- [ ] Criar sistema que roda em segundo plano para monitorar jogo aberto
- [ ] Registrar estatísticas no banco de dados

## Fase 5 — Sistema de Download de Jogos (Principal)
- [ ] Criar integração com fonte externa de downloads
- [ ] Mapear jogos do fórum e baixar imagens, descrições e metadados
- [ ] Implementar downloader com barra de progresso
- [ ] Gerenciar múltiplos downloads simultâneos
- [ ] Verificar integridade dos arquivos baixados

## Fase 6 — Recursos Avançados
- [ ] Criar sistema de savestates
- [ ] Criar integração com fórum (comentários, posts, notas)
- [ ] Criar sistema de avaliações dos jogos
- [ ] Criar seção de jogos recomendados

## Fase 7 — UI/UX Completa
- [ ] Criar tema visual definitivo
- [ ] Criar tema claro/escuro
- [ ] Criar animações e transições
- [ ] Criar mecanismo de responsive design
- [ ] Criar ícone, splash screen e identidade visual

## Fase 8 — Transformação do Launcher em Aplicativo Desktop
- [ ] Integrar o Salsilauncher com Electron
- [ ] Criar comunicação backend local → Electron
- [ ] Empacotar versão desktop para Windows
- [ ] Criar sistema de auto-update
- [ ] Criar modos portáteis e instaláveis

## Fase 9 — Infraestrutura e Qualidade
- [ ] Criar testes automáticos (backend e frontend)
- [ ] Criar documentação em /docs
- [ ] Criar pipeline de build
- [ ] Criar sistema de logs
- [ ] Otimizar performance geral

## Fase 10 — Futuro e Expansões
- [ ] Suporte a outras plataformas além de Windows
- [ ] Integração com outros launchers
- [ ] Plugin system para extensões
