### Cuadro de Requerimientos (Table of requirements)


| ID | REQUERIMIENTOS  (Requirement / Feature) |
|----|---------------------|
| ---- | **Funcionales** |
| RF01 | Registrar Sucursales |
| RF02 | Gestionar Grupos o Roles |
| RF03 | Gestionar Automóviles |
| RF04 | Registrar Usuarios |
| RF05 | Registrar Clientes |
| RF06 | Procesar Ventas |
| RF07 | Editar Encuentas |
| RF08 | Registrar Resultados de Encuentas |
| ---- | **No Funcionales** |
| RNF01 | Ejemplo |
| ---- | **Almacenamiento  (Storage)** |
| DB01 | Branch (code, name, state, address) |
| DB02 | User (id, username, password, groups, permissions) |
| DB03 | Person (id, first_name, last_name, date_of_birth, gender, phone, email, address) |
| DB04 | Group (id, name, descripcion) |
| DB05 | Permission (code, description) |
| DB06 | Automobile (number_of_serie, price, mark, model, date_of_manufacture, number_of_cylinders, number_of_doors, weight, capacity, options, color, others_specifications) |
| DB08 | Mark (id, name)
| DB08 | Model (id, name)
| DB07 | Survey (id, description, questions, date_of_creation)
| DB08 | Country (id, name)
| DB09 | State (id, name)
| DB10 | City (id, name)
| DB11 | Location (id, name)
| DB12 | Sale (id, date_of_sale, Person)
| DB13 | LineOfSale (id, quantity, Automobile)
| ---- | **Reportes** |
| RP01 | Ejemplo (field1, field2, fieldn) |