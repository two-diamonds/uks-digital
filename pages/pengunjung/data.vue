<template>
  <div class="container-fluid content">
    <div class="row">
      <div class="col-lg-8">
        <h2 class="text-center my-4">DATA ALAT</h2>
        <form>
          <div class="mb-3 row">
              <label for="" class="col-sm-2 col-form-label">NAMA ALAT :</label>
              <div class="col-sm-10">
                <input type="text" class="form-control" id="">
              </div>
        </div>
        <div class="mb-3 row">
              <label for="" class="col-sm-2 col-form-label">KEGUNAAN :</label>
              <div class="col-sm-10">
                <input type="text" class="form-control" id="">
              </div>
          </div>
          <div class="mb-3 row">
              <label for="" class="col-sm-2 col-form-label">JUMLAH ALAT :</label>
              <div class="col-sm-10">
                <input type="text" class="form-control" id="">
              </div>
          </div>
          <div class="text-end">
          </div>
          <div class="justify-content-end d-flex">
            <button type="submit" class="btn btn-white m-2 btn-lg px-5">PAKAI</button>       
            <button type="submit" class="btn btn-white m-2 btn-lg px-5">KEMBALI</button>       
          </div>  
        </form>
      </div>
    </div>
  </div>
</template>

<style scoped>
img {
    height: 100px;
  
}
.content {
  background: #B84F4F;
  height: 100vh;
}
label, h2 {
  color: white;
  font-weight: 700;
}
.btn{
  background: #d9d9d9;
}
</style>