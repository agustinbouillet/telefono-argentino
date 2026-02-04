# Changelog

## [2.0.3] - 2026-02-04

### Corregido

- Se solucionó un error que provocaba una excepción al consultar si un número
  de teléfono es válido cuando la instancia fue creada sin proporcionar un
  valor como argumento. Ahora, en lugar de interrumpir la ejecución con un
  error no controlado, la validación retorna `false` de forma segura,
  permitiendo que el flujo del programa continúe sin inconvenientes.
