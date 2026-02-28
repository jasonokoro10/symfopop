# SymfoPop - Catàleg de Productes en Symfony 7

Aquesta aplicació web permet als usuaris registrar-se, iniciar sessió i publicar productes de segona mà amb una interfície moderna i SEO optimitzat.

## 🚀 Característiques

- **Seguretat**: Sistema complet d'autenticació (Login/Logout).
- **Productes (CRUD)**: Gestió de productes (Títol, Descripció, Preu, Imatge).
- **SEO**: URLs amigables basades en slugs (ex: `/product/show/pantalla-led`).
- **Buscador**: Cerca productes per qualsevol paraula clau al títol o descripció.
- **Responsivitat**: Disseny totalment adaptat a mòbils amb Bootstrap 5.

## 🛠️ Instal·lació pas a pas

1. **Clona el projecte** (o descarrega'l a htdocs).
2. **Dependències**:
    ```bash
    composer install
    ```
3. **Base de dades**:
   Configura el fitxer `.env` (ex: `DATABASE_URL="mysql://root:@127.0.0.1:3306/symfopop?charset=utf8mb4"`) i executa:
    ```bash
    php bin/console doctrine:database:create
    php bin/console doctrine:migrations:migrate
    php bin/console doctrine:fixtures:load --no-interaction
    ```
4. **Execució**:
   Obre el teu servidor local a: [http://localhost:8000/](http://localhost:8000/)

## 🔑 Credencials per a proves

- **Email**: `admin@symfopop.com`
- **Password**: `admin123`

---

_Projecte finalitzat i comentat en català segons les directrius de l'arquitecte._
