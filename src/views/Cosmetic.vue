<template>
  <article>
    <h1>Kosmetika SynCare</h1>
    <div class="services">
      <h2>Co znamená SynCare?</h2>
      <div class="right">
        <silent-box :image="article_images[0]" />
      </div>

      <p>
        SynCare je spojení latinské předpony SYN - pro a anglického slova CARE – péče. Vyjadřuje přesvědčení, že
        kosmetika SynCare by měla být významným celoživotním pomocníkem v péči o pleť ženy i muže. Správnou péčí o pleť
        a pokožku ovlivňujeme zdravotní stav a svou vnitřní rovnováhu. Abychom docílili zdravého, jasného a mladistvého
        vzhledu, je nutné dodávat pleti a pokožce potřebné látky pro jejich výživu.
      </p>

      <h2>Certifikovaná biokosmetika</h2>
      <p>
        SynCare je bez syntetických konzervačních látek, barviv, živočišných surovin, minerálních olejů, etoxylovaných
        emulgátorů a bez parfémů. Vysokou úroveň přípravků potvrzují tisíce spolupracujících lékařů, lékáren a
        kosmetických salónů nejen v ČR a SR, ale i v Německu, Rakousku, Velké Británii a Řecku.
      </p>

      <div class="left">
        <silent-box :image="article_images[1]" />
      </div>

      <p>
        Značka SynCare přináší na trh profesionální dermo a bio přípravky na hranici lékařské a estetické péče. Je
        určena pro ošetření všech druhů pleti. Zvláště se zaměřuje na suchou citlivou pleť, dále na pleť s akné, zralou
        pleť a pleť s vrozenými defekty (ekzémy, periorální dermatitida, rosacea, poškození slunečním zářením.)
      </p>

      <p>
        <strong>
          Ke kosmetickému ošetření máte možnost dopřát si parafínový zábal na ruce za zvýhodněnou cenu 70,-
        </strong>
      </p>
    </div>
  </article>
</template>

<script>
export default {
  name: "Cleanset",
  data() {
    return {
      article_images: [
        {
          src: require("@/assets/images/cosmetic/kosmetika1.jpg"),
          description: "Krásný salon | Kosmetika SynCare",
          alt: "Krásný salon | Kosmetika SynCare",
        },
        {
          src: require("@/assets/images/cosmetic/kosmetika2.jpg"),
          description: "Krásný salon | Kosmetika SynCare",
          alt: "Krásný salon | Kosmetika SynCare",
        },
      ],
    }
  },
}
</script>
