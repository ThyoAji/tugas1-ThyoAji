<template>
    <div>
      <div class="kategori kategori-introduction">
        <img src="https://icons.veryicon.com/png/o/miscellaneous/johnny_icon/personnel-introduction.png" alt="Introduction Icon">
        <WelcomeItem>
          <template #icon>
            <DocumentationIcon />
          </template>
          <template #heading>INTRODUCTION</template>
          <p style="text-align: left;">
            Perkenalkan nama saya Thyo Aji Dinata, biasanya dipanggil Thyo atau Teo.
          </p>
        </WelcomeItem>
      </div>
  
      <div class="kategori kategori-pendidikan">
        <img src="https://icons.veryicon.com/png/o/object/material-design-icons/school-9.png" alt="Pendidikan Icon">
        <WelcomeItem>
          <template #icon>
            <ToolingIcon />
          </template>
          <template #heading>PENDIDIKAN</template>
          <p style="text-align: left;">
            SMA: Bina Bangsa<br>
            SMP: SMP IT Annawawi<br>
            SD: SD IT Al Izhar
          </p>
          <code></code>
        </WelcomeItem>
      </div>
  
      <div class="kategori kategori-aboutme">
        <img src="https://icons.veryicon.com/png/o/application/tmall-icon-library/about-me-2.png" alt="About Me Icon">
        <WelcomeItem>
          <template #icon>
            <EcosystemIcon />
          </template>
          <template #heading>ABOUT ME</template>
          <p style="text-align: left;">
            Halo, saya Tyho. Saya hanya seorang manusia seperti manusia pada umumnya. Keseharian saya diisi dengan kegiatan yang saya nikmati, terutama bermain game. Walaupun kadang-kadang saya merasa pusing atau emosi, bermain game memberikan saya kesenangan dan kepuasan tersendiri.
          </p>
        </WelcomeItem>
      </div>
  
      <div class="kategori kategori-hobi">
        <img src="https://icons.veryicon.com/png/o/miscellaneous/other-1/toys-hobby.png" alt="Hobi Icon">
        <WelcomeItem>
          <template #icon>
            <CommunityIcon />
          </template>
          <template #heading>Hobi</template>
          <p style="text-align: left;">
            Selain bermain game, saya juga menyukai olahraga, terutama badminton.
          </p>
        </WelcomeItem>
      </div>
  
      <div class="kategori kategori-media-sosial">
        <img src="https://icons.veryicon.com/png/o/object/material-design-icons-1/instagram-49.png" alt="Media Sosial Icon">
        <WelcomeItem>
          <template #icon>
            <SupportIcon />
          </template>
          <template #heading>MEDIA SOSIAL</template>
          <p style="text-align: left;">
            INSTAGRAM: @Dinata.De_rayzel <br>
            DISCORD: !Kill's
          </p>
        </WelcomeItem>
      </div>
    </div>
  </template>
  
  <style>
    .kategori {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 20px;
    }
  
    .kategori img {
      width: 32px; 
      height: 32px;
    }
  
    .kategori p {
      text-align: left;
    }
  </style>
  