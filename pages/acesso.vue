<template>
  <div>
    <Acesso />
    <Footer />
  </div>
</template>

<script>

async function oi(){
  try {
    await this.$strapi.find('Users');
  } catch (error) {
    console.error(error);
  }
}
export default oi()

</script>