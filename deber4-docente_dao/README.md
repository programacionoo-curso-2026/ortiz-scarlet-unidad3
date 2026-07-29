# Deber 4 - DocenteDAO

## Descripción
Implementación del patrón DAO para la entidad `Docente` usando `database/sql`
y el driver `github.com/glebarez/sqlite`, sobre una base de datos SQLite.

## Estructura del proyecto
- `dataaccess/dataaccess.go`: inicialización y conexión a la base de datos.
- `model/docente.go`: struct `Docente`.
- `dao/docente_dao.go`: operaciones CRUD (`CreateTable`, `Insert`, `GetByID`, `GetByEmail`).
- `main.go`: punto de entrada que prueba las operaciones del DAO.

## Cómo ejecutar
\`\`\`bash
go mod tidy
go run main.go
\`\`\`
