# Indice del dominio de Diego Ayala

Pagina estatica sencilla para listar las paginas y subdominios principales de `diegoayala.com`.

El diseno parte de `pagina-diaps`: composicion centrada, modo claro/nocturno y enlaces directos.

## Editar enlaces

Abre `index.html` y cambia cada bloque:

```html
<a class="domain-link" href="#" data-pending>
  <span>dominio1</span>
  <i aria-hidden="true"></i>
</a>
```

por el nombre y URL definitivos:

```html
<a class="domain-link" href="https://ejemplo.diegoayala.com">
  <span>Nombre visible</span>
  <i aria-hidden="true"></i>
</a>
```

Quita `data-pending` cuando el enlace ya apunte a una pagina real.
Los enlaces con `data-pending` o `href="#"` quedan ocultos por defecto.

## Abrir

Puedes abrir `index.html` directamente en el navegador. No requiere servidor ni dependencias.
