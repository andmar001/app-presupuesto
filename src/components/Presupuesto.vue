<script setup>

</script>

<template>
   <form
         class="presupuesto"
   >
      <div class="campo">
         <label for="">Definir Presupuesto</label>
         <input 
               id="nuevo-presupuesto"
               class="nuevo-presuuesto"
               placeholder="Añade tu presupuesto"
               type="number"
         />
      </div>

      <input type="submit" value="Definir Presupuesto">

   </form>
</template>

<style scoped>
   .presupuesto{
      width: 100%;
   }
   .campo{
      display: grid;
      gap: 2rem;
   }
   .presupuesto label{
      font-size: 2.4rem;
      font-weight: 500;
      color: var(--azul);
      text-align: center;
   }
   .presupuesto input[type="number"]{
      background-color: var(--gris-claro);
      border-radius: 1rem;
      padding: 1rem;
      border: none;
      font-size: 2.2rem;
      text-align: center;
   }
   .presupuesto input[type="submit"]{
      background-color: var(--azul);
      border: none;
      padding: 1rem;
      text-align: center;
      font-size: 2rem;
      margin-top: 2rem;
      color: var(--blanco);
      font-weight: 900;
      width: 100%;
      transition: background-color 300ms ease;
   }
   .presupuesto input[type="submit"]:hover{
      cursor: pointer;
      background-color: #1048A4;
   }


</style>