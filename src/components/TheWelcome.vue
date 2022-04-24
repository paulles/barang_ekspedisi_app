<script setup lang="ts">
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
<img src="../assets/kurir.jpg"/>
<br><br>

<main>
  <div class="row row-cols-2 row-cols-md-5 mb-3 text-center">
    <div class="col">
      <div class="card mb-4 rounded-3 shadow-sm">
        <div class="card-header py-3">
          <h4 class="my-0 fw-normal">Kerjasama secara kekeluargaan</h4>
        </div>
        <div class="card-body">
          <h1 class="card-title pricing-card-title"><small class="text-muted fw-light"></small></h1>
          <ul class="list-unstyled mt-3 mb-4">
            <li>Kami bertanggung jawab mewakili online shop Anda untuk semua masalah pengiriman paket</li>
          </ul>
          <button type="button" class="w-40 btn btn-lg btn-outline-primary">Mulai</button>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card mb-4 rounded-3 shadow-sm">
        <div class="card-header py-3">
          <h4 class="my-0 fw-normal">Jemput Pengiriman</h4>
        </div>
        <div class="card-body">
          <h1 class="card-title pricing-card-title"><small class="text-muted fw-light"></small></h1>
          <ul class="list-unstyled mt-3 mb-4">
            <li>Minimal ambil barang 10 kg kami siap jemput di tempat Anda (FLEKSIBEL & GRATIS)</li>
          </ul>
          <button type="button" class="w-60 btn btn-lg btn-primary">Terima Jemput Kami</button>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card mb-4 rounded-3 shadow-sm border-primary">
        <div class="card-header py-3 text-white bg-primary border-primary">
          <h4 class="my-0 fw-normal">Layanan 24 Jam<br><br></h4>
        </div>

        <div class="card-body">
          <h1 class="card-title pricing-card-title"><small class="text-muted fw-light"></small></h1>
          <ul class="list-unstyled mt-3 mb-4">
            <li><br><br>Siap melayani Anda bersama kami Zelva Bot<br></li>
          </ul>
          <button type="button" class="w-40 btn btn-lg btn-primary">Hubungi Kami</button>
        </div>
      </div>
    </div>
  </div>

</main>

</template>
