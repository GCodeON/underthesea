<template>
<div class="card">
  <div class="background"  v-on:click="onClick()" ref="bg">
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" id="waves" preserveAspectRatio="xMidYMid" viewBox="0 0 1280 665">
      <g transform="translate(640,332.5) scale(1,1) translate(-640,-332.5)"><linearGradient id="lg-0.5275131334473817" x1="0" x2="1" y1="0" y2="0">
        <stop stop-color="#ff00ff" offset="0"></stop>
        <stop stop-color="#00ffff" offset="1"></stop>
      </linearGradient><path  class="path" d="M 1306 333 C 1306 505 956 746 792 799 C 628 852 343 761 242 622 C 141 483 81 139 182 0 C 283 -139 602 -110 766 -57 C 930 -4 1306 161 1306 333" fill="url(#lg-0.5275131334473817)" opacity="0.4">
        <animate attributeName="d" dur="10s" repeatCount="indefinite" keyTimes="0;0.3333333333333333;0.6666666666666666;1" calcmod="spline" keySplines="0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9" begin="-4s" values="M 1306 333 C 1306 505 956 746 792 799 C 628 852 343 761 242 622 C 141 483 81 139 182 0 C 283 -139 602 -110 766 -57 C 930 -4 1306 161 1306 333;M 1159 333 C 1159 491 926 704 776 753 C 626 802 338 747 245 620 C 152 493 133 160 226 32 C 319 -96 617 -106 767 -57 C 917 -8 1159 175 1159 333;M 1226 333 C 1226 499 952 756 794 807 C 636 858 336 759 238 625 C 140 491 94 141 192 7 C 290 -127 625 -158 783 -107 C 941 -56 1226 167 1226 333;M 1306 333 C 1306 505 956 746 792 799 C 628 852 343 761 242 622 C 141 483 81 139 182 0 C 283 -139 602 -110 766 -57 C 930 -4 1306 161 1306 333"></animate>
      </path><path  class="path" d="M 1256 333 C 1256 503 956 753 794 806 C 632 859 331 768 231 630 C 131 492 85 140 185 2 C 285 -136 608 -121 770 -68 C 932 -15 1256 163 1256 333" fill="url(#lg-0.5275131334473817)" opacity="0.4">
        <animate attributeName="d" dur="10s" repeatCount="indefinite" keyTimes="0;0.3333333333333333;0.6666666666666666;1" calcmod="spline" keySplines="0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9" begin="-4s" values="M 1256 333 C 1256 503 956 753 794 806 C 632 859 331 768 231 630 C 131 492 85 140 185 2 C 285 -136 608 -121 770 -68 C 932 -15 1256 163 1256 333;M 1213 333 C 1213 504 964 775 801 828 C 638 881 294 795 193 657 C 92 519 67 127 168 -11 C 269 -149 624 -174 787 -121 C 950 -68 1213 162 1213 333;M 1225 333 C 1225 517 939 658 764 715 C 589 772 227 860 119 711 C 11 562 33 119 141 -30 C 249 -179 605 -156 780 -99 C 955 -42 1225 149 1225 333;M 1256 333 C 1256 503 956 753 794 806 C 632 859 331 768 231 630 C 131 492 85 140 185 2 C 285 -136 608 -121 770 -68 C 932 -15 1256 163 1256 333"></animate>
      </path><path  class="path" d="M 1232 333 C 1232 504 941 704 778 757 C 615 810 234 839 133 701 C 32 563 56 119 156 -19 C 256 -157 638 -217 801 -164 C 964 -111 1232 162 1232 333" fill="url(#lg-0.5275131334473817)" opacity="0.4">
        <animate attributeName="d" dur="10s" repeatCount="indefinite" keyTimes="0;0.3333333333333333;0.6666666666666666;1" calcmod="spline" keySplines="0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9" begin="-4s" values="M 1232 333 C 1232 504 941 704 778 757 C 615 810 234 839 133 701 C 32 563 56 119 156 -19 C 256 -157 638 -217 801 -164 C 964 -111 1232 162 1232 333;M 1245 333 C 1245 496 944 742 789 792 C 634 842 266 805 170 674 C 74 543 144 174 240 42 C 336 -90 608 -96 763 -46 C 918 4 1245 170 1245 333;M 1175 333 C 1175 497 943 735 787 786 C 631 837 285 794 188 661 C 91 528 62 116 159 -17 C 256 -150 636 -186 792 -135 C 948 -84 1175 169 1175 333;M 1232 333 C 1232 504 941 704 778 757 C 615 810 234 839 133 701 C 32 563 56 119 156 -19 C 256 -157 638 -217 801 -164 C 964 -111 1232 162 1232 333"></animate>
      </path><path  class="path" d="M 1213 333 C 1213 486 899 636 754 683 C 609 730 293 774 203 650 C 113 526 154 169 244 45 C 334 -79 613 -78 758 -31 C 903 16 1213 180 1213 333" fill="url(#lg-0.5275131334473817)" opacity="0.4">
        <animate attributeName="d" dur="10s" repeatCount="indefinite" keyTimes="0;0.3333333333333333;0.6666666666666666;1" calcmod="spline" keySplines="0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9" begin="-4s" values="M 1213 333 C 1213 486 899 636 754 683 C 609 730 293 774 203 650 C 113 526 154 169 244 45 C 334 -79 613 -78 758 -31 C 903 16 1213 180 1213 333;M 1255 333 C 1255 493 937 731 785 780 C 633 829 305 773 211 644 C 117 515 126 157 220 28 C 314 -101 605 -76 757 -26 C 909 24 1255 173 1255 333;M 1356 333 C 1356 514 965 746 793 802 C 621 858 226 857 120 710 C 14 563 49 126 155 -20 C 261 -166 616 -179 788 -123 C 960 -67 1356 152 1356 333;M 1213 333 C 1213 486 899 636 754 683 C 609 730 293 774 203 650 C 113 526 154 169 244 45 C 334 -79 613 -78 758 -31 C 903 16 1213 180 1213 333"></animate>
      </path><path  class="path" d="M 1179 333 C 1179 489 907 648 758 696 C 609 744 342 742 250 616 C 158 490 112 141 204 15 C 296 -111 622 -115 770 -67 C 918 -19 1179 177 1179 333" fill="url(#lg-0.5275131334473817)" opacity="0.4">
        <animate attributeName="d" dur="10s" repeatCount="indefinite" keyTimes="0;0.3333333333333333;0.6666666666666666;1" calcmod="spline" keySplines="0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9;0.3 0.1 0.7 0.9" begin="-4s" values="M 1179 333 C 1179 489 907 648 758 696 C 609 744 342 742 250 616 C 158 490 112 141 204 15 C 296 -111 622 -115 770 -67 C 918 -19 1179 177 1179 333;M 1195 333 C 1195 496 937 719 782 769 C 627 819 257 813 161 681 C 65 549 73 122 169 -10 C 265 -142 600 -72 755 -22 C 910 28 1195 170 1195 333;M 1244 333 C 1244 518 974 760 798 817 C 622 874 222 865 113 715 C 4 565 -10 88 99 -61 C 208 -210 601 -145 777 -88 C 953 -31 1244 148 1244 333;M 1179 333 C 1179 489 907 648 758 696 C 609 744 342 742 250 616 C 158 490 112 141 204 15 C 296 -111 622 -115 770 -67 C 918 -19 1179 177 1179 333"></animate>
      </path></g>
    </svg>
    
    <div class="decor">
      <br><br><br>  <br><br><br><br><br><br><br>
      <h1 class="title">
        Join Us
      </h1>
      <Logo />
      <h1 class="title">
        <span class="name">Sienna Soto-Vazquez</span>
        <br>
        is turning one!

      </h1>

      <h1 class="title">04/27/21</h1>
  <br>
      <particle-effect-button
      :visible.sync="btnOps.visible"
      :animating.sync="btnOps.animating"
      :options="btnOps"
      cls="btn-cls"
      >
      Zoom Party! 
      </particle-effect-button>

      <particle-effect-button
      :visible.sync="registryOps.visible"
      :animating.sync="registryOps.animating"
      :options="registryOps"
      cls="btn-cls"
      >
        View Registry!
      </particle-effect-button>

      <!-- <br v-if="btnOps.visible"><br v-if="btnOps.visible"><br v-if="btnOps.visible"> -->
      <br><br><br> 
      <div class="time">
        <flip-countdown deadline="2021-4-27 00:00:00"></flip-countdown>
      </div>

      <br><br><br> 

    </div>
    <div class="music">
      <audio src="/underthesea.mp3" id="my_audio" ref="song" loop="loop"></audio> 
    </div>
  </div>
</div>
</template>

<script>
import FlipCountdown from 'vue2-flip-countdown';
import ParticleEffectButton from "vue-particle-effect-buttons";

export default {
  props: [],
  components: {
    FlipCountdown, ParticleEffectButton
  },
  data() {
    return {
      musicPlaying: false,
      btnOps: {
        style: "stroke",
        direction: "bottom",
        duration: 1000,
        easing: "easeOutSine",
        speed: 0.7,
        oscillationCoefficient: 75,
        label: "Register",
        onComplete: () => {
          console.log("complete");

          window.open('https://calendar.google.com/event?action=TEMPLATE&tmeid=Y2p0Z3JpMGd2cDBqMjRkcjlqM2ZxYzk2dWcgZ2VyYXJkb3NvdG85M0Bt&tmsrc=gerardosoto93%40gmail.com');

        },
        onBegin: () => {
          console.log("begin");
        },
        visible: true,
        animating: false
      },
      registryOps: {
        style: "stroke",
        direction: "bottom",
        duration: 1000,
        easing: "easeOutSine",
        speed: 0.7,
        oscillationCoefficient: 75,
        label: "Register",
        onComplete: () => {
          console.log("complete");

          window.open('https://www.myregistry.com/wishlist/sienna-aurora-soto-vazquez-escondido-ca/2790830')

        },
        onBegin: () => {
          console.log("begin");
        },
        visible: true,
        animating: false
      },
    }
  },
  mounted() {
   
  },
  computed: {

  },
  methods: {
    playMusic() {
      if(!this.musicPlaying) {
        this.musicPlaying = true;
        this.$refs.song.play();
      }

    },
    onClick() {
      console.log("on click play song");
      this.playMusic();
    },   
  }
};


</script>

<style lang="scss">

.vue-particle-effect-button .particles-button {
  cursor:  url('/mermaid.svg') 25 50, auto;
  position      : relative;
  border-radius : 15px;
    background : rgb(124, 12, 134);
  color       : white;
  border      : 4px solid white;
  margin      : 0;
  will-change : transform;
  font-family : 'Sofia';
  transition  : background-color 0.5s ease;
      font-size   : 22px;

  &:hover {
    background : rgb(124, 12, 134);
    color      : #fff;
    border     : 4px solid #f8c5c3;
    transition : color 0.5s ease;
    transition : background-color 0.5s ease;

  }
  @include breakpoint(medium) {
    font-size   : 27px;
  }
}

.card {
  cursor:  url('/mermaid.svg') 25 50, auto;
}

@import url('https://fonts.googleapis.com/css2?family=Berkshire+Swash&family=Sofia&display=swap');


@keyframes scale {
  0%   {transform: scale(1.2)}
  100%  {transform: scale(1)}
}

@keyframes oscillate {
  0%   {transform: scale(1)}
  25%  {transform: scale(1.04)}
  50%  {transform: scale(0.9)}
  75%  {transform: scale(1.03)}
  50%  {transform: scale(1)}
}
#waves {
  width      : 100%;
  height     : 160%;
  position   : absolute;
  z-index    : -1;
  background : #526488;
}
.decor {
  margin              : 0 auto;
  height              : 100%;
  width               : 100%;
  text-align          : center;
  background          : url('/underthesea.svg');
  background-size     : cover;
  transition          : all 3s;
  background-position : center;
  animation           : oscillate 8s linear infinite;

  @include breakpoint(medium) {
    background-repeat : no-repeat;
    background-size   : cover;
    width             : 75%;
    
  }
    @include breakpoint(large) {
    background-repeat : no-repeat;
    background-size   : cover;
    width             : 85%;
    
  }

}

.title {
  font-family    : 'Sofia', cursive;
  display        : block;
  font-weight    : 300;
  font-size      : 25px;
  color          : white;
  letter-spacing : 1px;
  @include breakpoint(medium) {
    font-size : 35px;
  }

  .name {
    font-size: 1.3em;
  }

}
.logo {
  max-width  : 50%;
  margin     : 0 auto;
  transition : all 2s;
  &:hover {
      transform: scale(1.2);
  }
  //  animation: oscillate 5s linear 2s infinite forwards;
  @include breakpoint(small) {
    max-width : 30%;
  }
}

.subtitle {
  font-weight    : 300;
  font-size      : 42px;
  color          : #526488;
  word-spacing   : 5px;
  padding-bottom : 15px;
}

.links {
  padding-top : 15px;
}

.flip-card {
  color : white;
}
.flip-card__bottom, .flip-card__back-bottom, .flip-card__back::before, .flip-card__back::after {
  color      : pink !important;
  background : rgb(124, 12, 134)!important;
}

.flip-card__top, .flip-card__back::before, .flip-card__back::after  {
  color      : pink !important;
  background : rgb(72, 7, 78) !important;
}
 .flip-clock__slot {
    font-family : Sofia !important;
    background  : #f5c1b69e !important;
    color       : black !important;
 }

</style>
