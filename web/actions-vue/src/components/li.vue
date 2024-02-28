<template>
  <div>
    <ul>
      <li v-for="number in 9" :key="number" @click="showAlert(number)">
        {{ number }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  methods: {
    showAlert(number) {
      alert(`You selected ${number}`);
    }
  }
}
</script>
