<section class="beneficios" id="beneficios">
  <h2>¿Por qué elegir Fixlat?</h2>
  <div class="benefits-list">
    <div class="benefit">
      <div class="icon-bg"><span>📊</span></div>
      <h3>Monitoreo en Tiempo Real</h3>
      <p>Visualiza el consumo de agua y aforo desde cualquier lugar, en cualquier momento.</p>
    </div>
    <div class="benefit">
      <div class="icon-bg"><span>💧</span></div>
      <h3>Detección de Fugas</h3>
      <p>Recibe alertas automáticas ante fugas o consumos anómalos para evitar desperdicios.</p>
    </div>
    <div class="benefit">
      <div class="icon-bg"><span>🌱</span></div>
      <h3>Ahorro y Sostenibilidad</h3>
      <p>Optimiza el uso del recurso hídrico y contribuye al cuidado del medio ambiente.</p>
    </div>
    <div class="benefit">
      <div class="icon-bg"><span>🔗</span></div>
      <h3>Integración de Sensores</h3>
      <p>Compatible con sensores de aforo y otros dispositivos inteligentes.</p>
    </div>
  </div>
</section>

<style>
.beneficios {
  background: #fff;
  padding: 60px 20px 40px 20px;
  max-width: 1200px;
  margin: 0 auto 48px auto;
}
.beneficios h2 {
  text-align: center;
  font-size: 2.1rem;
  font-weight: 800;
  color: #0a2540;
  margin-bottom: 40px;
}
.benefits-list {
  display: flex;
  flex-wrap: wrap;
  gap: 32px;
  justify-content: center;
}
.benefit {
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
  transition: transform 0.18s, box-shadow 0.18s;
}
.benefit:hover {
    color: #1e90ff;
  box-shadow: 0 8px 32px rgba(44,62,80,0.13);
}
.icon-bg {
  background: linear-gradient(90deg, #ff6f3c 0%, #ffa53c 100%);
  border-radius: 50%;
  width: 56px;
    background: linear-gradient(90deg, #1e90ff 0%, #0072c6 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 18px;
  box-shadow: 0 2px 8px rgba(255,111,60,0.10);
}
.icon-bg span {
  font-size: 2rem;
  color: #fff;
}
.benefit h3 {
  color: #ff6f3c;
  font-size: 1.18rem;
  font-weight: 700;
  margin-bottom: 12px;
  text-align: center;
}
.benefit p {
  color: #23395d;
  font-size: 1.05rem;
  text-align: center;
}
@media (max-width: 900px) {
  .benefits-list {
    flex-direction: column;
    gap: 24px;
    align-items: center;
  }
}
</style>
