# p1-ej-12

## Consigna

Hacer un programa para tomar datos poblacionales. Hay tres botones: "Cargar nueva familia", "Ordenar por salario" y "Filtrar por localidad".

1- Al apretar "Cargar nueva familia" se deben pedir datos de las personas que viven en ese hogar, entre ellos:

  - Direccion del hogar.
  - Localidad.
  - Integrantes. Donde de cada uno se debe pedir:
    
    - Nombre y apellido.
    - Edad.
    - Genero.
    - Ocupacion.
    - Salario (si aplica).

2- Al apretar "Ordenar por salario" deben mostrarse las familias por orden de ingreso per capita de forma decreciente.

3- Al apretar "Filtrar por localidad" debe pedirse una localidad y mostrar todas las familias que pertenezcan a ella.

4- Formato para mostrar cada familia:

```javascript
- ${direccion}, ${localidad}
- Integrantes:
  - ${APELLIDO}, ${nombre} [${edad}, ${genero}]
  - ${APELLIDO}, ${nombre} [${edad}, ${genero}]
  - ${APELLIDO}, ${nombre} [${edad}, ${genero}]
  ...
```

## Entrega

- Clonar este repositorio localmente
- Crear un repositorio personal con el nombre `dw-p1-12`
- Modificar este `README.md` con este contenido:

```markdown
### Alumno: ...

#### Comision: ...
```

- Subir los archivos `index.html`, `index.js` y `README.md`.
