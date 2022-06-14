<template>
  <section id="new-testimonial">
    <div class="container">
      <div class="row">
        <div class="col-lg-8">
          <h1>Compartilhe suas lembranças</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nobis
            totam voluptatum ipsum nisi? Dolor delectus adipisci autem eius ad,
            commodi facilis reprehenderit vel dignissimos deserunt soluta culpa!
            Laboriosam, fugiat pariatur?
          </p>
        </div>
        <div class="col-lg-4">
          <form>
            <div class="form-group">
              <label for="name">Nome</label>
              <input
                type="text"
                class="form-control"
                id="name"
                placeholder="Nome"
              />
            </div>
            <div class="form-group">
              <label for="email">Email</label>
              <input
                type="email"
                class="form-control"
                id="email"
                placeholder="Email"
              />
            </div>
            <div class="form-group">
              <label for="message">Mensagem</label>
              <textarea class="form-control" id="message" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Enviar</button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style></style>
