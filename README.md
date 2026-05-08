# Indice del dominio de Diego Ayala

Pagina estatica sencilla para listar las paginas y subdominios principales de `diegoayala.com`.

El diseno parte de `pagina-diaps`: composicion centrada, modo claro/nocturno y enlaces directos.

## Editar enlaces

Abre `index.html` y anade una nueva entrada dentro de `.domain-list`:

```html
<li>
  <a
    class="domain-link"
    href="https://ejemplo.diegoayala.com/"
    target="_blank"
    rel="noreferrer"
  >
    <span>Nombre visible</span>
    <i aria-hidden="true"></i>
  </a>
</li>
```

Las entradas con `data-pending` o `href="#"` quedan ocultas por defecto.

## Abrir

Puedes abrir `index.html` directamente en el navegador. No requiere servidor ni dependencias.
