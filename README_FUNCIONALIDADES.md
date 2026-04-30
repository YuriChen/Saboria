# 🍳 Receitas Deliciosas - Flutter App

Uma aplicação Flutter elegante e intuitiva para descobrir e compartilhar receitas culinárias do mundo todo.

## ✨ Funcionalidades Implementadas

### 1. **Tela Inicial (Home Screen)**
- GridView de 2 colunas exibindo receitas populares
- Cada card mostra:
  - Imagem da receita com overlay gradiente
  - Nome da receita
  - Categoria culinária
  - Bandeira e país de origem
- Design elegante com cores quentes (laranja #FFA500, marrom #8B4513)

### 2. **Barra de Busca**
- Campo de busca integrado no AppBar
- Pesquisa em tempo real por nome de receita
- Sugestões visuais enquanto digita
- Botão para limpar a busca

### 3. **Botão de Receita Aleatória**
- Localizado no AppBar (ícone de shuffle)
- Carrega uma receita aleatória ao clicar
- Leva direto para a tela de detalhes

### 4. **Tela de Detalhes da Receita**
- **Hero Animation**: Imagem com transição suave
- **Parallax Scrolling**: Efeito visual ao fazer scroll da imagem
- Exibe completo:
  - Nome e informações da receita (categoria, país)
  - **Lista de Ingredientes**: até 20 ingredientes com quantidades formatadas
  - **Modo de Preparo**: Instruções formatadas e bem organizadas
  - **Link para YouTube**: Botão para abrir vídeo da receita (integração com url_launcher)

### 5. **Design Visual**
- **Cores Quentes**: Paleta laranja e marrom para atmosfera culinária
- **Tipografia**: Fontes que remetem a culinária (Georgia para títulos)
- **Gradientes**: Overlays de gradient em imagens
- **Ícones Emojis**: Bandeiras de países e ícones decorativos

## 🛠️ Estrutura do Projeto

```
lib/
├── main.dart                    # App principal com tema
├── models/
│   └── meal.dart               # Models: Meal, MealDetail, Ingredient
├── services/
│   └── api_service.dart        # Serviço de API (TheMealDB)
└── screens/
    ├── home_screen.dart        # Tela inicial com GridView e busca
    └── recipe_detail_screen.dart # Tela de detalhes com hero animation
```

## 📦 Dependências Utilizadas

```yaml
http: ^1.2.0                      # Requisições HTTP para API
url_launcher: ^6.2.0              # Abertura de links (YouTube)
cached_network_image: ^3.3.0      # Cache de imagens da rede
```

## 🔌 API Utilizada

- **TheMealDB API** (https://www.themealdb.com/api/json/v1/1)
- Endpoints:
  - `search.php?s=` - Buscar receitas por nome
  - `random.php` - Receita aleatória
  - `lookup.php?i=` - Detalhes da receita por ID

## 🎨 Tema e Cores

- **Cor Primária**: #8B4513 (Marrom)
- **Cor Secundária**: #FFA500 (Laranja)
- **Fundo**: Branco com acentos
- **Tipografia Principal**: Roboto com Georgia para títulos

## 🚀 Como Executar

1. **Instalar dependências:**
```bash
flutter pub get
```

2. **Executar a aplicação:**
```bash
flutter run
```

3. **Build para release:**
```bash
flutter build apk    # Android
flutter build ios    # iOS
flutter build web    # Web
```

## 📱 Plataformas Suportadas

- Android
- iOS
- Web
- Windows
- macOS
- Linux

## 🔄 Fluxo da Aplicação

1. **Abertura**: Carrega receitas populares via API
2. **Home**: Usuário vê grid de receitas ou usa busca
3. **Busca**: Digite para filtrar receitas em tempo real
4. **Aleatória**: Clique no ícone shuffle para receita aleatória
5. **Detalhes**: Clique em um card para ver:
   - Ingredientes formatados
   - Instruções de preparo
   - Link para vídeo no YouTube

## 💡 Destaques Técnicos

- **Hero Animation**: Transição suave de imagem entre telas
- **Parallax Effect**: Efeito de profundidade ao fazer scroll
- **State Management**: Use of StatefulWidget com setState
- **Tratamento de Erros**: Tratamento completo de erros com exibição de mensagens
- **Cache de Imagens**: CachedNetworkImage para melhor performance
- **Responsive Design**: GridView adapta-se ao tamanho da tela

## 🎯 Próximas Melhorias Sugeridas

- Adicionar favoritos local (SharedPreferences)
- Filtrar por categoria/país
- Modo escuro (Dark Mode)
- Compartilhar receitas
- Avaliar receitas
- Histórico de visualizadas
- Offline mode com cache

## 📝 Notas de Desenvolvimento

- A API TheMealDB é gratuita e não requer autenticação
- Imagens são servidas via HTTP/HTTPS
- O parallax effect funciona melhor em devices com scroll fluido
- Hero animation automática ao navegar para detalhes

---

**Versão**: 1.0.0
**Status**: Completo e pronto para uso
**Data**: Abril 2026
