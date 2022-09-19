<template>
  <div id="contact" class="container-fluid bg-warning rounded col-11 col-md-6 p-2">
    <form
      class="bg-light rounded p-2"
      action="https://formsubmit.co/d.arterom@gmail.com"
      method="POST"
    >
      <div><h1 class="text-dark fw-bold display-4">Contacta</h1></div>
      <div class="mb-4 text-start">
        <label
          for="exampleFormControlInput1"
          class="form-label text-dark fw-bold p-2"
          >Email
        </label>
        <input
          type="email"
          class="form-control bg-dark text-warning fw-bold"
          id="exampleFormControlInput1"
          placeholder="name@example.com"
          name="email"
        />
      </div>
      <div class="mb-4 text-start">
        <label
          for="exampleFormControlInput1"
          class="form-label text-dark fw-bold p-2"
          >Asunto
        </label>
        <input
          type="text"
          class="form-control bg-dark text-warning fw-bold"
          id="exampleFormControlInput1"
          placeholder="Asunto..."
          name="Asunto"
        />
      </div>
      <div class="mb-4 text-start">
        <label
          for="exampleFormControlTextarea1"
          class="form-label text-dark fw-bold p-2"
          >Consulta</label
        >
        <textarea
          class="form-control bg-dark text-warning fw-bold"
          id="exampleFormControlTextarea1"
          rows="3"
          placeholder="Introduce tu consulta..."
          name="content"
        ></textarea>
      </div>
      <input type="hidden" name="_template" value="table" />
      <button
        class="col-6 rounded btn-dark text-warning fw-bold p-2"
        type="submit"
      >
        Enviar
      </button>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>