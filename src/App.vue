<template>
  <div class="page-wrapper">
    <header class="flex" style="border: 1px solid blue">
      <div>
        <div class="flex align-items-center">
          <img src="./assets/place_black_24dp.svg" alt="" />
          <p class="bold">Smörgatan 28, Kallebäck</p>
        </div>

        <h1><span>1</span> rok bytes</h1>
      </div>

      <img class="img" src="./assets/house.png" alt="lägenhet" />
    </header>

    <h2>Finnes</h2>
    <p>
      - 37kvm <br />
      - 4185kr/mån <br />

      - Smörgatan 28 <br />

      - Våning 3 <br />
      - Hyresvärd Kjellberg och Möller AB <br />
    </p>
    <p>
      En underbar ljus och luftig etta med vacker utsikt över Göteborg!
      <br /><br />
      Lägenheten är omgiven av vackra naturområden, roliga aktiviteter och bra
      kollektivtrafik precis utanför dörren. Det är nära till en Coop mataffär,
      Nordic wellness gym och andra affärer. På 5 minuter är man i skogen med
      flera motionsslingor och till badet går man på 15 minuter. Förutom bada
      vid Delsjön kan man också besöka mysiga caféer, paddla kanot, spela
      padel(raketsport), motionera m.m.
      <br />
      Hyresvärden är Kjellberg och Möller AB som är en väldigt hjälpsam och
      ansvarsfull hyresvärd. Jag stortrivs i min lägenhet och med mina grannar.
      Jag har bott här i över 9 år, men vill få ett miljöombyte och väldigt
      gärna en större lägenhet så jag kan flytta ihop med min partner.
      <br />
      Lägenheten har en välplanerad planlösning och vacker glasvägg mellan kök
      och vardagsrum som öppnar upp hela lägenheten. Fiskbens parkett i
      vardagsrummet och hallen. Det finns väldigt bra förvaringsmöjligheter i
      köket samt flera inbyggda garderober i hallen. Detta är ett stort plus då
      man kan förvara mycket i lägenheten utan att den blir svår att städa.<br /><br />
      Övrigt:<br />
      - Tillgång till att hyra parkeringplats utanför huset för 300kr/mån.<br />
      - Källarförråd (lägenhetens privata).<br />
      - Fräsch tvättstuga i källaren, lätt att få en tvättid. Två tvättmaskiner,
      mangel och stort torkrum.<br />
    </p>

    <h2>Önskas</h2>
    <p></p>
    <p>
      - 37kvm <br />
      - 4180kr/mån <br />

      - Smörgatan 28 <br />

      - Våning 3 <br />
      - Hyresvärd Kjellberg och Möller AB <br />
    </p>

    <!--  <img alt="Vue logo" src="./assets/kitchen.jpg" /> -->
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
  text-size-adjust: none;

  color: #131520;
  background-color: none;
}

.page-wrapper {
  background-color: #fff3ed;
  border: 1px solid red;
}
.bold {
  font-weight: 700;
}
.flex {
  display: flex;
  &.column {
    flex-direction: column;
  }
  &.align-items-center {
    align-items: center;
  }
}
p {
  font-size: 16px;
  font-weight: 300;
  letter-spacing: 0.1px;
}
h1 {
  font-family: "Playfair Display", serif;
  font-size: 112px;
  font-weight: 600;
  line-height: 80px;
  span {
    font-family: "Playfair Display", serif;
    font-size: 192px;
    font-weight: 400;
    line-height: 80px;
  }
}

header {
  .img {
    object-fit: cover;
    width: 25vw;
    height: 25vw;

    border-radius: 50%;
  }
}
</style>
