📦 diotdd
diotdd é um projeto de exemplo que demonstra a aplicação de princípios de Inversão de Dependência (IoC) e Desenvolvimento Orientado a Testes (TDD) utilizando .NET Core. Ele serve como referência para desenvolvedores que desejam entender e implementar essas práticas em seus próprios projetos.

🚀 Tecnologias Utilizadas
.NET Core

xUnit

Moq

Inversão de Controle (IoC)

Test-Driven Development (TDD)

📁 Estrutura do Projeto
O projeto está organizado da seguinte maneira:

bash
Copiar
Editar
diotdd/
├── diotdd/                 # Projeto principal
│   ├── Controllers/        # Controladores da aplicação
│   ├── Models/             # Modelos de dados
│   ├── Services/           # Serviços e lógica de negócio
│   └── Program.cs          # Ponto de entrada da aplicação
├── diotdd.Tests/           # Projeto de testes
│   ├── Services/           # Testes dos serviços
│   └── diotdd.Tests.csproj # Arquivo de projeto de testes
└── diotdd.sln              # Solução do Visual Studio
🧪 Executando os Testes
Para executar os testes do projeto, utilize o seguinte comando no terminal:

bash
Copiar
Editar
dotnet test
Certifique-se de que o SDK do .NET Core esteja instalado em sua máquina.

📌 Como Contribuir
Contribuições são bem-vindas! Se você deseja melhorar este projeto, siga os passos abaixo:

Fork este repositório.

Crie uma branch para sua feature: git checkout -b minha-feature.

Faça suas alterações e commit: git commit -m 'Minha nova feature'.

Envie para sua branch: git push origin minha-feature.

Abra um Pull Request.

📄 Licença
Este projeto está licenciado sob a MIT License.
