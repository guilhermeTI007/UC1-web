# Projeto AMARELO

## Visão Geral
Plataforma para notícias de animes, publicação de histórias e mangás independentes e localização de eventos.

## Objetivos
- Centralizar notícias de animes.
- Apoiar criadores independentes.
- Permitir descoberta de eventos.
- Monetização por assinatura e moedas.

## Perfis de Usuário
- Visitante
- Usuário cadastrado
- Assinante
- Administrador

## Funcionalidades

### Visitante
- Visualizar notícias, histórias, mangás e posts.
- Navegar por categorias.
- Visualizar eventos sem filtros.

### Usuário cadastrado
- Login e cadastro.
- Criar, editar e excluir posts.
- Filtrar posts.
- Publicar histórias e mangás.
- Comprar moedas.
- Desbloquear capítulos com moedas.
- Aguardar X dias para desbloqueio gratuito.

### Assinante
- Perfil personalizado.
- Maior destaque nas publicações.
- Recebimento de moedas periódicas.
- Filtrar eventos por interesse.

### Administrador
- Gerenciar usuários.
- Moderar conteúdos.
- Gerenciar categorias, eventos, notícias e planos.

## Telas
1. Página inicial
2. Login
3. Cadastro
4. Perfil
5. Notícias
6. Histórias e Mangás
7. Leitor de capítulos
8. Eventos
9. Compra de moedas
10. Assinatura
11. Painel administrativo

## Entidades

### Usuário
- id
- nome
- email
- senha
- foto
- tipo
- moedas
- assinaturaAtiva

### Perfil
- bio
- banner
- personalização

### Post
- id
- título
- conteúdo
- categoria
- autor
- data

### Notícia
- id
- título
- conteúdo
- fonte
- data

### História/Mangá
- id
- título
- descrição
- autor
- capa
- status

### Capítulo
- id
- história
- número
- conteúdo
- custoMoedas
- diasEspera

### Evento
- id
- nome
- descrição
- local
- data
- categoria

### Categoria
- id
- nome

### Assinatura
- id
- plano
- valor
- benefícios

### Carteira
- saldo
- histórico

### Compra
- id
- usuário
- tipo
- valor
- data

## Fluxo de Uso
1. Visitante acessa o site.
2. Pode navegar sem login.
3. Realiza cadastro/login.
4. Publica conteúdos e gerencia seus posts.
5. Compra moedas ou assina um plano.
6. Desbloqueia capítulos por moedas ou espera o prazo.
7. Assinantes possuem benefícios adicionais.

## Regras de Negócio
- Visitantes não publicam conteúdo.
- Apenas autores editam/excluem seus posts.
- Capítulos podem ser desbloqueados por moedas ou espera.
- Assinantes recebem destaque e filtros de eventos.
- Eventos são públicos, porém filtros são exclusivos para assinantes.

## Rodapé
- Contato
- Redes sociais
- Política de Privacidade
- Termos de Uso
- Direitos Autorais
