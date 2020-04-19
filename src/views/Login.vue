<template>
  <section class="section section-lg pt-lg-0 section-contact-us">
    <div class="container mt-5">
      <b-row class="justify-content-center">
        <div class="mt-5">
          <card
            class="align-content-center"
            style="background-color:#eedada"
            shadow
            body-classes="p-lg-5"
          >
            <h4 class="align-content-center mt-5">Posez nous votre question</h4>
            <base-input
              class="mt-5"
              alternative
              placeholder="Votre nom"
              addon-left-icon="ni ni-user-run"
            ></base-input>
            <base-input alternative placeholder=" Email" addon-left-icon="ni ni-email-83"></base-input>
            <base-input class="mb-5">
              <textarea
                class="form-control form-control-alternative"
                name="name"
                rows="4"
                cols="80"
                placeholder="Votre message..."
              ></textarea>
            </base-input>
            <base-button type="default" round block size="lg">Envoyer</base-button>
          </card>
        </div>
      </b-row>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style>
</style>
