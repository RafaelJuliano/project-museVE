<template>
  <q-page padding>
    <div class="w-full flex justify-end">
      <h6 class="text-primary font-bold q-my-none">Cadastrar Livro</h6>
    </div>
    <q-separator color="primary" spaced="sm"></q-separator>
    <BookForm>
      <q-btn label="Salvar" type="submit" color="primary"></q-btn>
      <q-btn
        label="Limpar"
        type="reset"
        color="primary"
        flat
        class="q-ml-sm"
      ></q-btn>
    </BookForm>
  </q-page>
</template>

<script>
import BookForm from "src/components/BookForm.vue";

export default {
  name: "BooksCreate",

  components: {
    BookForm,
  },
};
</script>
