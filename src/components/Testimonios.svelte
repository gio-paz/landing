<section class="testimonios" id="testimonios">
  <h2>Clientes y Casos de Éxito</h2>
  <div class="testimonials">
    <div class="testimonial">
      <div class="quote-mark">“</div>
      <p>Gracias a Fixlat hemos reducido el consumo de agua en un 30% y detectado fugas a tiempo.</p>
      <div class="author">Empresa ABC, Colombia</div>
    </div>
    <div class="testimonial">
        color: #1e90ff;
      <p>La integración de sensores de aforo nos permitió optimizar procesos y ahorrar costos.</p>
      <div class="author">Planta XYZ, Perú</div>
    </div>
    <div class="testimonial">
        color: #1e90ff;
      <p>La plataforma es intuitiva y el soporte técnico excelente.</p>
      <div class="author">Comunidad Residencial, México</div>
    </div>
  </div>
</section>

<style>
.testimonios {
  background: #fff;
  padding: 60px 20px 40px 20px;
  max-width: 1200px;
  margin: 0 auto 48px auto;
}
.testimonios h2 {
  text-align: center;
  font-size: 2.1rem;
  font-weight: 800;
  color: #0a2540;
  margin-bottom: 40px;
}
.testimonials {
  display: flex;
  flex-wrap: wrap;
  gap: 32px;
  justify-content: center;
}
.testimonial {
  background: #f7f9fb;
  border-radius: 18px;
  box-shadow: 0 4px 24px rgba(44,62,80,0.08);
  padding: 38px 28px 32px 28px;
  flex: 1 1 260px;
  min-width: 240px;
  max-width: 320px;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  transition: transform 0.18s, box-shadow 0.18s;
}
.testimonial:hover {
  transform: translateY(-6px) scale(1.03);
  box-shadow: 0 8px 32px rgba(44,62,80,0.13);
}
.quote-mark {
  font-size: 3.5rem;
  color: #ff6f3c;
  font-family: serif;
  position: absolute;
  top: 18px;
  left: 22px;
  opacity: 0.18;
  pointer-events: none;
}
.testimonial p {
  color: #23395d;
  font-size: 1.08rem;
  text-align: center;
  margin: 0 0 18px 0;
  font-style: italic;
}
.testimonial .author {
  margin-top: 10px;
  font-weight: bold;
  color: #ff6f3c;
  font-size: 1.05rem;
  text-align: center;
}
@media (max-width: 900px) {
  .testimonials {
    flex-direction: column;
    gap: 24px;
    align-items: center;
  }
}
</style>
