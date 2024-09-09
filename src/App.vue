<template>
  <div id="app">
    <div class="app-container">
      <main class="app-main">
        <div class="content">
          <h1>Constanza Mendoza</h1>
          <h2>Santiago, Chile</h2>
          <h3>¿Quien soy?</h3>
          <p>
            Soy una diseñadora industrial con una sólida trayectoria de 7 años en dos campos dinámicos y exigentes: la publicidad y la mecánica. Mi experiencia abarca 3 años en el ámbito publicitario, donde he desarrollado proyectos creativos que conectan eficazmente con las audiencias. Posteriormente, durante 4 años, he trabajado en la industria mecánica, donde he aplicado mi conocimiento técnico para optimizar procesos y productos, destacándome por mi capacidad para integrar diseño funcional y estética.
          </p>
          <h3>Mis fortalezas</h3>
          <p>
            Mi adaptabilidad es uno de mis mayores atributos, permitiéndome enfrentar diferentes desafíos y situaciones con eficacia. Disfruto del trabajo en equipo, donde mi habilidad para colaborar y comunicarme ha sido clave en la consecución de objetivos comunes. Además, tengo una fuerte inclinación por la investigación; cuando algo no lo sé, me sumerjo en él hasta dominarlo.
          </p>
          <h3>Me dedico a...</h3>
          <p>
            Actualmente, estoy ampliando mis horizontes hacia el desarrollo web, una disciplina que considero complementaria a mi formación en diseño. Estoy segura de que mi experiencia en diseño industrial será un gran aporte en el desarrollo de interfaces y experiencias de usuario innovadoras y efectivas.
          </p>
          <h3>¿Cómo puedes contactarme?</h3>
          <p>
            Estoy disponible para nuevas oportunidades y me encantaría conversar más sobre cómo puedo contribuir a su equipo. Pueden contactarme al número +56 9XXXXXX o a través de mi perfil en LinkedIn.
          </p>


          <section class="projects-section">
            <h2>Trabajos Realizados</h2>
            <div class="project-card">

              <h3>Suomi Verb Learning</h3>
              <p>
                Una página de aprendizaje sobre los idiomas finlandés, inglés y español, con ejercicios dinámicos diseñados para mejorar tus habilidades lingüísticas de manera interactiva y efectiva.
              </p>
              <a href="https://suomi-74768.web.app/verb" target="_blank" rel="noopener noreferrer" class="project-link">
                <i class="fas fa-external-link-alt"></i> Visitar Sitio
              </a>
            </div>
            <div class="project-card">
         

              <h3>Proyecto Behance</h3>
              <p>
                Behance presenta todos los proyectos realizados como diseñadora industrial en los diferentes campos, desde publicidad hasta la produccion de productos.
              </p>
              <a href="https://www.behance.net/constanmendoza1" target="_blank" rel="noopener noreferrer" class="project-link">
                <i class="fas fa-external-link-alt"></i> Visitar Sitio
              </a>
            </div>
            <div class="project-card">
         

              <h3>Proyecto Github</h3>
              <p>
                GitHub presenta todos los proyectos realizados como diseñadora Web.
              </p>
              <a href="https://github.com/conzaa" target="_blank" rel="noopener noreferrer" class="project-link">
                <i class="fas fa-external-link-alt"></i> Visitar Sitio
              </a>
            </div>
          </section>
        </div>
      </main>

 
      <footer class="footer">
        <div class="social-icons">
          <a href="https://www.instagram.com" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-instagram"></i>
          </a>
          <a href="https://www.linkedin.com" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-linkedin"></i>
          </a>
          <a href="https://www.twitter.com" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-twitter"></i>
          </a>
          <a href="https://github.com" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-github"></i>
          </a>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  font-family: 'Century Gothic', sans-serif;
}

body {
  background: linear-gradient(90deg, rgba(125, 187, 68, 1) 26%, rgba(0, 212, 255, 1) 100%);
  height: 100%;
  margin: 0;
}

.app-container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.app-main {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}

.content {
  max-width: 800px;
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h1, h2 {
  color: #333;
}

p {
  color: #555;
  line-height: 1.6;
}


.projects-section {
  margin-top: 40px;
}

.projects-section h2 {
  text-align: center;
  color: #333;
  margin-bottom: 20px;
}

.project-card {
  background-color: #f9f9f9;
  padding: 15px 20px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  margin-bottom: 20px;
}

.project-card h3 {
  color: #333;
  margin-bottom: 10px;
}

.project-card p {
  color: #555;
  line-height: 1.5;
}

.project-link {
  display: inline-flex;
  align-items: center;
  color: #1da1f2;
  text-decoration: none;
  font-weight: bold;
  margin-top: 10px;
}

.project-link i {
  margin-left: 5px;
}

.project-link:hover {
  color: #0d8ecf;
}

/* Footer estilos */
.footer {
  background-color: #333;
  padding: 10px 0;
  text-align: center;
}

.social-icons a {
  color: white;
  margin: 0 10px;
  font-size: 24px;
  transition: color 0.3s ease;
}

.social-icons a:hover {
  color: #1da1f2; /* Cambia de color al pasar sobre el ícono */
}
</style>
