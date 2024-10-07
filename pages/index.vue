<template>
  <div class="container-fluid">
    <div class="row ">
      <div class="col-1 p-5">
        <NuxtLink class="btn btn-light">KEMBALI</NuxtLink>
      </div>

      <div class="row my-2 justify-content-center">
        <div class="col-5">
          <div class="bg-light rounded-5">
            <h1 class="text-center">OBAT-OBATAN DAN ALAT</h1>
          </div>
        </div>
      </div>

      <div class="row my-5 bg-pink justify-content-center">
        <div class="col">
          <div class="row justify-content-center">
            <div class="col my-4">
              <NuxtLink to="/obat" class="btn btn-light">OBAT</NuxtLink>
            </div>
          </div>
          <div class="row">
            <div class="col my-4">
              <NuxtLink to="/paracetamol" class="btn btn-light">paracetamol</NuxtLink>
            </div>
            <div class="col my-4">
              <NuxtLink class=" btn btn-light">betadin</NuxtLink>
            </div>
          </div>
          <div class="row">
            <div class="col my-4">
              <NuxtLink class=" btn btn-light">alkohol</NuxtLink>
            </div>
            <div class="col my-4">
              <NuxtLink class="btn btn-light">opistan</NuxtLink>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="row">
            <div class="col my-4">
              <NuxtLink class="btn btn-light">ALAT</NuxtLink>
            </div>
          </div>
          <kapas class="row">
            <div class="col my-4">
              <NuxtLink class="btn btn-light">hasanplas</NuxtLink>
            </div>
            <div class="col my-4">
              <NuxtLink class="btn btn-light">kapas</NuxtLink>
            </div>
          </kapas>
          <div class="row">
            <div class="col my-4">
              <NuxtLink class="btn btn-light">tensi</NuxtLink>
            </div>
            <div class="col my-4">
              <NuxtLink class="btn btn-light">oksigen</NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// const supabase = useSupabaseClient()
// const keyword = ref('')
// const visitors = ref([])

// const getPengunjung = async () => {
//   const { data, error } = await supabase.from('pengunjung').select(`*, keanggotaan(*), keperluan(*)`)
//   .ilike('nama', `%${keyword.value}%`)
//   if(data) visitors.value = data
//   visitors.value = data
// }

// const visitorFiltered = computed(() => {
//   return visitors.value.filter((b) => {
//       return (
//           b.nama?.toLowerCase().includes(keyword.value?.toLowerCase())
//       )
//   })
// })

// onMounted(() =>{
//   getPengunjung()
// })
</script>


<style scoped>
.container-fluid {
  background-color: #F28787;
  height: 100vh;
}

.bg-pink {
  background-color: #F9A6A6;
}
.bg-light {
  background-color: #d9d9d9 !important;
}

.contect{
  background: #F9A6A6;
}
@import url('https://fonts.googleapis.com/css2?family=Irish+Grover&display=swap');
.container-fluid {
  /* background: url("~/assets/img/OBAT-OBATAN 1.png"); */
  background-size: cover;
  width: 100%;
}
td {
  color: white;
  border: 1px solid #fff;
  background-color: rgba(255, 255, 255, 0);
}

h2{
  color: white;
  font-family: "Irish Grover", system-ui;
}

.bi-caret-left-fill {
  margin-left: 20px;
}
</style> 

          
      
