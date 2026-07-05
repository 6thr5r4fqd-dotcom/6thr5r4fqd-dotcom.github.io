---
layout: default
title: Revista
permalink: /revista/
---

<style>
.revista-page {
  max-width: 980px;
  margin: 0 auto;
  padding: 3rem 1.25rem;
  color: #1a1a1a;
  background: #ffffff;
  line-height: 1.7;
}

.revista-title {
  font-size: clamp(2rem, 5vw, 3.5rem);
  margin-bottom: 1rem;
  text-align: center;
  color: #111111;
}

.revista-subtitle {
  text-align: center;
  font-size: 1.1rem;
  color: #555555;
  margin-bottom: 2.5rem;
}

.revista-content {
  max-width: 820px;
  margin: 0 auto;
}

.revista-content p {
  margin-bottom: 1.5rem;
  font-size: 1.05rem;
  color: #1a1a1a;
}

.revista-content strong {
  color: #000000;
}

.revista-edicion {
  display: grid;
  grid-template-columns: 280px 1fr;
  gap: 2rem;
  align-items: center;
  margin: 2.5rem auto;
  padding: 2rem;
  background: #f4f4f4;
  border-left: 4px solid #b00020;
}

.revista-cover {
  width: 100%;
  max-width: 280px;
  height: auto;
  display: block;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.18);
}

.revista-edicion h2 {
  margin-top: 0;
  margin-bottom: 0.75rem;
  font-size: 1.8rem;
  color: #111111;
}

.revista-edicion-meta {
  margin-bottom: 1rem;
  font-weight: 600;
  color: #b00020;
}

.revista-button-group {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.25rem;
}

.revista-button {
  display: inline-block;
  padding: 0.75rem 1.3rem;
  border: 1px solid #b00020;
  color: #b00020;
  text-decoration: none;
  border-radius: 999px;
  font-weight: 600;
  transition: all 0.2s ease;
}

.revista-button:hover {
  background: #b00020;
  color: #ffffff;
}

.revista-button.secondary {
  border-color: #111111;
  color: #111111;
}

.revista-button.secondary:hover {
  background: #111111;
  color: #ffffff;
}

@media (max-width: 720px) {
  .revista-edicion {
    grid-template-columns: 1fr;
    text-align: center;
  }

  .revista-cover {
    margin: 0 auto;
  }

  .revista-button-group {
    justify-content: center;
  }
}
</style>

<section class="revista-page">

  <div class="revista-content">
    <h1 class="revista-title">Revista Estrategia</h1>

    <p class="revista-subtitle">
      Revista teórica y proyecto revolucionario
    </p>

    <p>
      <strong>Revista Estrategia</strong> busca poner a disposición de trabajadoras, trabajadores, estudiantes, organizaciones sociales y espacios de discusión política una herramienta para el debate estratégico.
    </p>

    <p>
      En esta sección encontrarás las ediciones disponibles de la revista, sus contenidos y mecanismos de acceso.
    </p>

    <div class="revista-edicion">
      <div>
        <img 
          class="revista-cover" 
          src="/assets/img/revista-estrategia-n1-invierno-2026.jpg" 
          alt="Portada Revista Estrategia Edición N°1 Invierno 2026"
        >
      </div>

      <div>
        <h2>Edición N°1</h2>

        <p class="revista-edicion-meta">
          Invierno, 2026
        </p>

        <p>
          <strong>Debates y reflexiones para el siglo XXI</strong> reúne textos orientados a contribuir al análisis político, la discusión teórica y la elaboración estratégica en el presente.
        </p>

        <div class="revista-button-group">
          <a class="revista-button" href="/assets/pdf/revista-estrategia-n1-invierno-2026.pdf" target="_blank" rel="noopener">
            Leer revista
          </a>

          <a class="revista-button secondary" href="https://www.instagram.com/revista_estrategia/" target="_blank" rel="noopener">
            Contactar por Instagram
          </a>
        </div>
      </div>
    </div>

    <p>
      Para consultas sobre distribución, colaboración o acceso a ejemplares, puedes escribirnos a través de nuestras redes sociales.
    </p>
  </div>

</section>
