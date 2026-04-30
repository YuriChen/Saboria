# Saboria - Descubra Receitas do Mundo Todo

Saboria é um aplicativo mobile multiplataforma desenvolvido em Flutter que conecta os usuários a milhares de receitas culinárias de diferentes países e culturas. Com uma interface rica e intuitiva, o app permite buscar, explorar e salvar receitas, trazendo o mundo da gastronomia para a palma da mão.

✨ Funcionalidades Principais:
🔍 Busca Inteligente:	Pesquise receitas por nome, ingrediente ou categoria diretamente na barra de busca
🎲 Receita Aleatória:	Descubra novos pratos com um toque — ideal para quem quer sair da rotina
🌍 Grade Visual:	Grid de receitas com imagens, nome, categoria e bandeira do país de origem
📋 Detalhes Completos	Cada receita exibe ingredientes com quantidades, instruções passo a passo e vídeo do YouTube
🦸 Animação Hero:	Transição suave da imagem entre a listagem e os detalhes, com efeito parallax
📱 Multiplataforma:	Mesmo código para Android, iOS e Web — desenvolvido com Flutter

🛠️ Tecnologias Utilizadas
Tecnologia	Aplicação
Flutter 3.x	Framework multiplataforma para UI
Dart	Linguagem de programação
Material Design 3	Sistema de design e componentes visuais
API MealDB	Fonte de dados de receitas (gratuita)
Pacote http	Requisições HTTP para consumo da API
Pacote url_launcher	Abertura de links externos (YouTube)
Provider	Gerenciamento de estado (se implementado)
Hero Animation	Transições animadas entre telas
🎯 Diferenciais Técnicos

    Arquitetura limpa: Separação entre modelos, telas e widgets reutilizáveis

    Design responsivo: Adapta-se a diferentes tamanhos de tela (mobile e web)

    Tema personalizado: Paleta de cores quentes (marrom e laranja) que remetem à culinária

    Código gerado com auxílio de IA: GitHub Copilot utilizado para acelerar o desenvolvimento

    Consumo de API REST: Integração com a MealDB para dados reais e atualizados

📂 Links do Projeto

    Código Fonte: GitHub - seu-usuario/saboria

    Demo Online: GitHub Pages - Saboria

    LinkedIn: Seu Perfil

🖼️ Capturas de Tela
Tela Inicial	Tela de Detalhes
https://link-para-screenshot-1	https://link-para-screenshot-2

(Substitua os links pelas imagens reais do seu app rodando)
🚀 Como Executar
bash

# Clone o repositório
git clone https://github.com/seu-usuario/saboria.git

# Entre na pasta
cd saboria

# Instale as dependências
flutter pub get

# Execute no navegador (modo mais rápido para testar)
flutter run -d web-server --web-port=8080

# Ou gere o APK para Android
flutter build apk --debug

📈 Próximos Passos (Roadmap)

    Adicionar sistema de favoritos com armazenamento local (Hive/SQLite)

    Implementar modo escuro

    Adicionar compartilhamento de receitas

    Criar tela de categorias (italiana, japonesa, vegana, etc.)

    Publicar na Google Play Store

