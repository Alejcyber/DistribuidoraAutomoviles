### Cuadro de Requerimientos (Table of requirements)


| ID | REQUERIMIENTOS  (Requirement / Feature) |
|----|---------------------|
| ---- | **Funcionales** |
| RF01 | Registrar Sucursales |
| RF02 | Gestionar Grupos o Roles |
| RF03 | Registrar Automóviles |
| RF04 | Registrar Usuarios |
| RF05 | Registrar Clientes |
| RF06 | Procesar ventas |
| RF07 | Editar encuestas |
| ---- | **No Funcionales** |
| RNF01 | Respaldo de BD |
| RNF02 | Usabilidad |
| RNF03 | Rapidez y eficiencia |
| RNF03 | Seguridad y proteccion de datos |
| ---- | **Almacenamiento  (Storage)** |
| DB01 | Marca (nombre) |
| DB02 | Modelo (nombre, precio, idmarca) |
| DB03 | Proveedor (nombre) |
| DB04 | Trabajo (titulo, salarioMinimo, salarioMaximo, idtarea) |
| DB05 | Tarea (titulo, descripcion) |
| DB06 | HistorialDeTrabajo (fechaInicio, fechaFin, idtrabajo, iddepartamento) |
| DB07 | Venta (idautomovil, idempleado, idpersona, idsede) |
| DB08 | Departamento (nombre, idempleado, idlocalidad) |
| DB09 | Localidad (nombre, idparroquia) |
| DB10 | Municipio (nombre, idestado) |
| DB11 | Estado (nombre, idpais) |
| DB12 | Pais (nombre) |
| DB13 | Automovil (nombre,placa,lugarFabricacion, fechaFabricacion, numeroCilindros, numeroPuertas, color, peso, capacidad, opciones, kilometraje) |
| DB14 | Sede (nombre,ubicacion) |
| DB15 | TipoPersona (nombre) |
| DB16 | Persona (cedula,nombres,apellidos, correo, telefono) |
| DB17 | Empleado (cedula,nombres,apellidos, correo, telefono, fechaContratacion,salario) |
| ---- | **Reportes** |
| RP01 | Vehiculos en periodo de prueba(marca, modelo, proveedor) |
| RP02 | Ventas realizadas(vendedor, cliente, marca, modelo, fecha, sucursal) |
| RP03 | Desempeño semestral(semestre, marca, modelo, desempeño) |
| RP04 | Factura(información del cliente, nombre del vendedor, numero de serie del vehículo, kilometraje actual, personalización adicional, financiamiento, información de garantía, información de licencia y seguro, precio, otros detalles ) |