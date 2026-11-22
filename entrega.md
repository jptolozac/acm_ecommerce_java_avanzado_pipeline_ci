Entrega – Pipeline de CI

- Repositorio: https://github.com/jptolozac/acm_ecommerce_java_avanzado_pipeline_ci
- Pull Request: https://github.com/jptolozac/acm_ecommerce_java_avanzado_pipeline_ci/pull/4

**Aclaración:** El job de seguridad con Trivy puede fallar debido a vulnerabilidades (CVE) sin resolver en el repo o sus dependencias. Este comportamiento es intencional, ya que el pipeline está configurado para detectar y bloquear la publicación de imágenes con vulnerabilidades HIGH o CRITICAL que cumplan los criterios definidos.
En la última action ejecutada para el evento push se puede ver que hay un exit (1) por vulnerabilidades encontradas: https://github.com/jptolozac/acm_ecommerce_java_avanzado_pipeline_ci/actions/runs/39759563326/job/119761058575