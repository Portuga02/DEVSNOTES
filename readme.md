DEVSNOTE( SITESMA DE ANOTAÇÕES SIMPLES)

Sistema simples com criação particular de api onde irá fazer um crud de anotações
simples para usuário utilizando requisições de api 
utilizando como base de dados o banco SQL-SERVER para armazenar e manipular 
arquivos de dados

O QUE O PROJETO PRECISA FAZER ?

- listar as anotações
- Pegar informações de  uma anotação
- Inserir uma anotação nova
- Deletar uma anotação

 Qual strutura de dados
- local para armazenar as anotações

-- id
-- title
-- body

Quais os endpoints?

(get) /api/notes
(get) /api/note/123
(post) /api/note(title, body)
(put) /api/note/123 (title, body)
(delete) /api/note/123
