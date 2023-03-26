    <script setup>
    import { ref } from 'vue';
    
    const display = ref('');
    
    function append(character) {
      display.value += character;
    }
    
    function calculate() {
      display.value = eval(display.value);
    }
    </script>
<template>
  <div>
    <input type="text" v-model="display" />
    <div>
      <button @click="append('1')">1</button>
      <button @click="append('2')">2</button>
      <button @click="append('3')">3</button>
      <button @click="append('+')">+</button>
    </div>
    <div>
      <button @click="append('4')">4</button>
      <button @click="append('5')">5</button>
      <button @click="append('6')">6</button>
      <button @click="append('-')">-</button>
    </div>
    <div>
      <button @click="append('7')">7</button>
      <button @click="append('8')">8</button>
      <button @click="append('9')">9</button>
      <button @click="append('*')">*</button>
    </div>
    <div>
      <button @click="append('0')">0</button>
      <button @click="append('.')">.</button>
      <button @click="calculate()">=</button>
      <button @click="append('/')">/</button>
    </div>
  </div>
</template>

