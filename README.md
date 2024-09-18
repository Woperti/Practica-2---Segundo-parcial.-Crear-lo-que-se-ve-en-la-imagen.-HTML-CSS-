# Haz que se vea lo que se ve en la imagen. Es un clone muy basico del landing page de twitter.


![Descripción de la imagen](./practica-2.png)

## Investiga las etiquetas html y los estilos necesarios:
las propiedades css: 

## Utiliza el html:

```html
  <div class="container">
  <header>
    <nav>
      <h1>Twitter Clone</h1>
    </nav>
  </header>
  <div class="main-content">
    <aside class="sidebar">
      <ul>
        <li>Inicio</li>
        <li>Explorar</li>
        <li>Notificaciones</li>
        <li>Mensajes</li>
        <li>Perfil</li>
      </ul>
    </aside>
    <section class="content">
      <h2>Feed</h2>
      <p>Aquí va el contenido del feed</p>
    </section>
    <aside class="extra">
      <h2>Tendencias</h2>
      <p>Aquí van las tendencias</p>
    </aside>
  </div>
  <footer>
    <p>© 2024 Twitter Clone</p>
  </footer>
</div>
```

y el css

```css
/* General Styles */
/* General Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f5f8fa;
  color: #14171a;
}

.container {
/*Escribe abajo de esta linea comentada*/
  
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  flex: 1; 
}

/* Header */
header {
  background-color: #1da1f2;
  padding: 20px;
 /*Escribe abajo de esta linea comentada*/

  color: white;
}

nav h1 {
  font-size: 2rem;
}

/* Main Content Layout */
.main-content {
   /*Escribe abajo de esta linea comentada*/
  
  margin-top: 20px;
}

/* Sidebar */
.sidebar {
  width: 20%;
  background-color: white;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.sidebar ul {
  list-style-type: none;
}

.sidebar ul li {
  padding: 10px 0;
  font-size: 1.1rem;
  cursor: pointer;
}

.sidebar ul li:hover {
  color: #1da1f2;
}
/* Content Section */
.content {
  width: 55%;
  background-color: white;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.content h2 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}

/* Extra Section (Trends) */
.extra {
  width: 20%;
  background-color: white;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.extra h2 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}

/* Footer */
footer {
  margin-top: 30px;
  /*Escribe abajo de esta linea comentada*/
  
  font-size: 0.9rem;
  color: #657786;
}
```
