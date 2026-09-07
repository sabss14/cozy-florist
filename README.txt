COZY FLORIST — PUBLICACIÓN GRATIS

1. Abre index.html con un editor de texto.
2. Sustituye:
   SUPABASE_URL = "PEGA_AQUI_TU_PROJECT_URL"
   SUPABASE_KEY = "PEGA_AQUI_TU_PUBLISHABLE_O_ANON_KEY"
   por los datos de Supabase.
3. Guarda el archivo como index.html.
4. Súbelo a tu repositorio público de GitHub llamado cozy-florist.
5. En GitHub: Settings > Pages > Deploy from a branch > main > / (root) > Save.
6. La página pública quedará en https://TUUSUARIO.github.io/cozy-florist/

SEGURIDAD:
- No uses la secret/service_role key en este archivo.
- La publishable/anon key está diseñada para frontend; la seguridad real la ponen las políticas RLS de Supabase.
- Solo el usuario que está en public.admins puede escribir.

NOTA:
- Las 60 flores y 40 jugadoras ya están en Supabase.
- La aplicación permite registrar qué flores tiene cada jugadora (sí/no).
- Las 66 posiciones de misión son independientes.
- El temporizador de 1:30 h se calcula en cada posición.
- La aparición de una nueva misión requiere que la administradora registre la nueva flor; la app no puede leer automáticamente lo que ocurre dentro del juego Cozy Florist.
