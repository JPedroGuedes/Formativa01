# Formativa01 - Criação de uma API com C#

O projeto é para uma criação de uma API com C# onde eu preciso criar um crud de uma api contendo as seguintes entidade e atributos: 
Usuários: Id, Nome, Email, DataNascimento(date) 
Pedidos: Id, usuarioId, EnderecoEntrega 
Categorias: Id, Nome, Status(Ativo, Inativo) 
Produtos: Id, Nome, Descrição, Preço 
PedidosProdutos: produtoId, categoriaId, quantidade


## 🚀 Começando

Para o projeto funcionar alem do codigo precisa da criação do banco de dados, para isso na Microsoft SQL Server Management Studio crie uma consulta e execute os dois codigos a seguir:
```
create database dbApiCompras
use database dbApiCompras
```
apos isso no codigo dentro do Visual Studio vc precisa entrar na aba Ferramentas > Gerenciador de Pacotes do Nuget > Console do Gerenciador de Pacotes, apos abrir a aba você digitara o codigo: 
```
Update-DataBase -Context SistemasComprasDBContext
```

## 📌 Versão

Eu usei [.Net](https://dotnet.microsoft.com/pt-br/download/dotnet/8.0) para controle de versão.

obrigado ate mais 😊
