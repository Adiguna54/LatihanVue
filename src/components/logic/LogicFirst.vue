<script>
export default {
  data() {
    return {
      num1: 0,
      num2: 0,
      operand: "",
    };
  },

  computed: {
    result() {
      switch (this.operand) {
        case "+":
          return this.num1 + this.num2;
        case "-":
          return this.num1 - this.num2;
        case "*":
          return this.num1 * this.num2;
        case "/":
          return this.num1 / this.num2;
      }
    },
  },
};
</script>

<template>
  <div class="px-10">
    <h1>Equal to: {{ result }}</h1>
    <div class="flex flex-row gap-5">
      <input class="border-2 text-center" type="number" v-model.number="num1" />
      <select name="" id="" v-model="operand">
        <option value="+">+</option>
        <option value="-">-</option>
        <option value="*">*</option>
        <option value="/">/</option>
      </select>
      <input class="border-2 text-center" type="number" v-model.number="num2" />
    </div>
  </div>
</template>

<style></style>
