# 🛍️ Lista e Cadastro de Produtos – Flutter

Aplicativo em Flutter para cadastro e gerenciamento de produtos com banco de dados local SQLite.

## ✅ Funcionalidades

- Cadastro, edição e exclusão de produtos
- Exibição de lista com preço, categoria, estoque e desconto
- Banco de dados local (SQLite)
- Compatível com Flutter Web

## 🧠 Modelo de Produto

```dart
class ProdutoModel {
  int? id;
  String nome;
  double precoCompra, precoVenda, desconto;
  int quantidade;
  String descricao, categoria;
  String? imagem;
  bool ativo, emPromocao;
}
```

## 🗂 Estrutura

- `main.dart`: inicialização do app
- `model/produto_model.dart`: modelo de dados
- `database/product_database.dart`: acesso SQLite
- `page/`: telas de cadastro e listagem
- `widgets/`: componentes reutilizáveis

## 🚀 Como rodar

```bash
flutter pub get
flutter build web
serve build/web
# Acesse em http://localhost:3000
```

## 👨‍💻 Desenvolvedor

Danilo Oliveira Vaz
