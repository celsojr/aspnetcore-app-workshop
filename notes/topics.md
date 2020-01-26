## Backend
 - APIs conversando com o EF
 - Retornando DTOs
 - Aceitando DTOs para evitar o excesso de vínculos
 - CRUD
 - AsNoTracking
 - Include
 - EF com Muitos para Muitos
  - OnModelCreating e mapeamento de entidade
 - Migrations
 - async Action methods
 - Swashbuckle e Swagger
 - Configurando a URL
 - Seeding data
 - Buscando
 
 ## ConferenceDTO
 - .NET Standard 2.0 library
 - APIs estão devolta no .NET Standard 2.0
 - Model Metadata
 
 ## FrontEnd
 - User Secrets
 - Razor Pages
 - Tag Helpers Customizados
 - Filter Customizados
 - Validação em formulários
 - Logging
 - Chamadas Outgoing HttpClient com JSON
 - Configuração em DI
 - Authenticação (sistema novo no 2.0)
   - Cookies
   - Adicionando suporte ao Twitter e ao Google
- Status Code pages
- Error page
 
 ## Cross cutting
 - Unit testing Controllers
 - Unit testing Pages
 
 
 ## Creditos Extra

- Adicione contas de usuário local usando o ASP.NET Core Identity
- Adicione um log de terceiros (serilog) e desative o log do console embutido
- Adicionar upload de imagem à entidade Speaker
- Adicione cache ao front-end (cache de memória e cache distribuído)
- Faça o site funcionar para várias conferências
  - Adicionar data da conferência
  - Faça com que a página inicial mostre as próximas conferências (em vez da agenda) e mova a agenda para a página separada
- Crie slugs dos nomes em vez de usar ids para navegar pelas entidades
- Adicione o suporte do `ILogger` à implementação do ApiClient
- Permitir Markdown para o Abstract usando um tag helper personalizado para markdown
- Adicione a filtro por datas ao back-end (em vez de fazer isso no front-end)
- Adicionar paginação ao backend
- Use postgres em vez de SQL server ou SQLite
- Adicione páginas de administrador para gerenciar:
  - Palestras
  - Participantes
  - Conferências
  - Sessões

