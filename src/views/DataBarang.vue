<template>
  <div class="data_barang">
    <h2 align="center">Data Input Pengiriman</h2>
  <form>
  <div class="form-group">
    <label for="exampleInputEmail1">Nama Pengirim</label>
    <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Masukkan nama pengirim">
    <small id="emailHelp" class="form-text text-muted"></small>
  </div>
    <div class="form-group">
      <label for="exampleInputEmail1">Jenis Barang</label>
      <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Masukkan jenis barang">
      <small id="emailHelp" class="form-text text-muted"></small>
    </div>
    <div class="form-group">
      <label for="exampleInputPassword1">Nama Barang</label>
      <input type="text" class="form-control" id="exampleInputPassword1" placeholder="Masukkan nama barang">
    </div>
    <div class="form-group">
      <label for="exampleInputPassword1">Berat</label>
      <input type="text" class="form-control" id="exampleInputPassword1" placeholder="Masukkan nilai berat">
    </div>
    <div class="form-group">
      <label for="exampleInputPassword1">Tanggal</label>
      <input type="text" class="form-control" id="exampleInputPassword1" placeholder="Ketikkan tanggal">
    </div>
    <h6>Lunas
      <input type="checkbox" class="form-check-input" id="exampleCheck1">
      <label class="form-check-label" for="exampleCheck1">Ya</label>
      </h6>
    <br>
    <div>
    <button type="submit" class="btn btn-primary">Submit</button>
    </div>
</form>
</div>

</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
