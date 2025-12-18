<script>
  let nombre = '';
  let email = '';
  let mensaje = '';
  let enviado = false;
  function handleSubmit(e) {
    e.preventDefault();
    enviado = true;
  }
</script>

<section class="contact-section" id="contacto">
  <h2>Contáctanos</h2>
  {#if !enviado}
    <form class="contact-form" on:submit|preventDefault={handleSubmit}>
      <input type="text" placeholder="Nombre" bind:value={nombre} required />
      <input type="email" placeholder="Correo electrónico" bind:value={email} required />
      <textarea rows="4" placeholder="Mensaje" bind:value={mensaje} required></textarea>
      <button type="submit" class="cta-btn">Enviar Mensaje</button>
    </form>
  {:else}
    <div class="enviado">¡Gracias por contactarnos! Te responderemos pronto.</div>
  {/if}
</section>

<style>
  .contact-section {
    background: #fff;
    padding: 48px 24px 40px 24px;
    text-align: center;
    max-width: 440px;
    margin: 0 auto 48px auto;
    border-radius: 18px;
    box-shadow: 0 4px 24px rgba(44,62,80,0.08);
  }
  .contact-section h2 {
    color: #0a2540;
    font-size: 2rem;
    font-weight: 800;
    margin-bottom: 28px;
  }
  .contact-form input, .contact-form textarea {
    width: 100%;
    box-sizing: border-box;
    padding: 14px;
    margin: 12px 0;
    border: 1.5px solid #eaf1f8;
    border-radius: 8px;
    font-size: 1.08rem;
    background: #f7f9fb;
    color: #23395d;
    transition: border 0.18s;
    max-width: 100%;
    display: block;
  }
  .contact-form input:focus, .contact-form textarea:focus {
    border: 1.5px solid #ff6f3c;
    outline: none;
  }
  .cta-btn {
    width: 100%;
    background: linear-gradient(90deg, #ff6f3c 0%, #ffa53c 100%);
    color: #fff;
        border: 1.5px solid #1e90ff;
    border: none;
    border-radius: 8px;
    font-size: 1.12rem;
        background: linear-gradient(90deg, #1e90ff 0%, #0072c6 100%);
    cursor: pointer;
    margin-top: 18px;
    box-shadow: 0 2px 8px rgba(255,111,60,0.08);
    transition: background 0.2s, transform 0.2s;
  }
  .cta-btn:hover {
    background: linear-gradient(90deg, #ffa53c 0%, #ff6f3c 100%);
    transform: translateY(-2px) scale(1.04);
  }
  .enviado {
    color: #ff6f3c;
    font-weight: bold;
        background: linear-gradient(90deg, #0072c6 0%, #1e90ff 100%);
    margin-top: 30px;
  }
</style>
        color: #1e90ff;
