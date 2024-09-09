<template>
  <div id="app">
    <div class="app-container">
      <main class="app-main">
        <div class="content">
          <h1>Constanza Mendoza</h1>
          <h2>Santiago, Chile</h2>
          <p>
            Soy una diseñadora industrial con una sólida trayectoria de 7 años en dos campos dinámicos y exigentes: la publicidad y la mecánica. Mi experiencia abarca 3 años en el ámbito publicitario, donde he desarrollado proyectos creativos que conectan eficazmente con las audiencias. Posteriormente, durante 4 años, he trabajado en la industria mecánica, donde he aplicado mi conocimiento técnico para optimizar procesos y productos, destacándome por mi capacidad para integrar diseño funcional y estética.
          </p>
          <p>
            Mi adaptabilidad es uno de mis mayores atributos, permitiéndome enfrentar diferentes desafíos y situaciones con eficacia. Disfruto del trabajo en equipo, donde mi habilidad para colaborar y comunicarme ha sido clave en la consecución de objetivos comunes. Además, tengo una fuerte inclinación por la investigación; cuando algo no lo sé, me sumerjo en él hasta dominarlo.
          </p>
          <p>
            Actualmente, estoy ampliando mis horizontes hacia el desarrollo web, una disciplina que considero complementaria a mi formación en diseño. Estoy segura de que mi experiencia en diseño industrial será un gran aporte en el desarrollo de interfaces y experiencias de usuario innovadoras y efectivas.
          </p>
          <p>
            Estoy disponible para nuevas oportunidades y me encantaría conversar más sobre cómo puedo contribuir a su equipo. Pueden contactarme al número +56 9XXXXXX o a través de mi perfil en LinkedIn.
          </p>
        </div>
      </main>
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
</style>

