<template>
 <div class="font-sans bg-gray-200 border-t-8 border-yellow-600 mt-12">
    <div class="back bg-fixed">
      <div>
        <div class="max-w-full">
          <div class="py-10 px-40">
            <img src="@/assets/img/ssc.png" width="400px"/>
          </div>
        </div>
    </div>
  </div>

  <div class="container bg-green-200">
      <div class="py-3 px-10">
        <div>
          <div class="flex mb-4 px-5" data-aos="fade-up" data-aos-offset="500">
            <div class="w-1/2"><div class="font-bold sm:text-sm md:text-base lg:text-lg xl:text-xl mb-2 mr-10">The Highest Student Governing Body of Davao del Norte State College ( A.Y. 2019 -2020 )</div>
            <p class="text-gray-700 text-base my-6 text-justify mr-10">The Supreme Student Council (SSC), as the highest governing student organization in this institution, will once again spearhead the annual week-long intramurals dubbed as ‘Kalibulung 2019’ with the theme “Rise of the Institutes, Triumph of DNSC” on November 4-8. This event will showcase the different talents and skills of the students in Literary and Sports Competitions. It also promotes camaraderie and healthy competitions among all institutes.</p></div>
            <div class="w-1/2"><img src="@/assets/img/sscc.JPG" class="img-responsive" alt="SSC" ></div>
          </div>
        </div>
    </div>
  </div>

  <div class="back bg-fixed">
      <div class="py-10 px-8">
        <div class="flex mb-4">
          <div class="w-1/3">
            <div class="max-w-sm rounded shadow-lg bg-gray-200" data-aos="fade-up" data-aos-offset="400">
              <img class="w-full" src="@/assets/img/joy.JPG" alt="College President - Dr. Joy M. Sorrosa">
              <div class="px-4 py-4">
                <div class="font-bold text-xl mb-2">"Leaders" - Dr. Joy M. Sorrosa</div>
                  <p class="text-gray-700 text-base text-justify">The Supreme Student Council (SSC), as the highest governing student organization in this institution, will once again spearhead the annual week-long intramurals dubbed as ‘Kalibulung 2019’ with the theme “Rise of the Institutes, Triumph of DNSC” on November 4-8. This event will showcase the different talents and skills of the students in Literary and Sports Competitions. It also promotes camaraderie and healthy competitions among all institutes.</p>
              </div>
            </div>
          </div>
          <div class="w-1/3">
            <div class="max-w-sm rounded shadow-lg bg-gray-200" data-aos="fade-up" data-aos-offset="400">
              <img class="w-full" src="@/assets/img/leila.JPG" alt="Guest Speaker - Mam Leila P. Saligumba">
              <div class="px-4 py-4">
                <div class="font-bold text-xl mb-2">"Leadership" - Mam Leila</div>
                  <p class="text-gray-700 text-base text-justify">The Supreme Student Council (SSC), as the highest governing student organization in this institution, will once again spearhead the annual week-long intramurals dubbed as ‘Kalibulung 2019’ with the theme “Rise of the Institutes, Triumph of DNSC” on November 4-8. This event will showcase the different talents and skills of the students in Literary and Sports Competitions. It also promotes camaraderie and healthy competitions among all institutes.</p>
              </div>
            </div>
          </div>
          <div class="w-1/3">
            <div class="max-w-sm rounded shadow-lg bg-gray-200" data-aos="fade-up" data-aos-offset="400">
              <img class="w-full" src="@/assets/img/ian.JPG" alt="SSC Adviser - Ian S. Somosot">
              <div class="px-4 py-4">
                <div class="font-bold text-xl mb-2">"Together" - Ian S. Somosot</div>
                  <p class="text-gray-700 text-base text-justify">The Supreme Student Council (SSC), as the highest governing student organization in this institution, will once again spearhead the annual week-long intramurals dubbed as ‘Kalibulung 2019’ with the theme “Rise of the Institutes, Triumph of DNSC” on November 4-8. This event will showcase the different talents and skills of the students in Literary and Sports Competitions. It also promotes camaraderie and healthy competitions among all institutes.</p>
              </div>
            </div>
          </div>
      </div>
    </div>
  </div>
    <div class="container bg-green-200">
      <div class="py-3 px-10">
        <div>
          <div class="flex mb-4 px-5" data-aos="fade-up" data-aos-offset="500">
            <div class="w-1/2"><div class="font-bold text-xl mb-2 mr-10">Teaser Video of the DNSC Kalibulung 2019 - SSC 2019-2020</div>
            <p class="text-gray-700 text-base my-6 text-justify mr-10" >The Supreme Student Council (SSC), as the highest governing student organization in this institution, will once again spearhead the annual week-long intramurals dubbed as ‘Kalibulung 2019’ with the theme “Rise of the Institutes, Triumph of DNSC” on November 4-8. This event will showcase the different talents and skills of the students in Literary and Sports Competitions. It also promotes camaraderie and healthy competitions among all institutes.</p></div>
            <div class="w-1/2"><iframe src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2FDNSCSSC%2Fvideos%2F795970890856067%2F&show_text=1&width=560" width="560" height="407" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allow="encrypted-media" allowFullScreen="true"></iframe></div>
          </div>
        </div>
    </div>
  </div>
     
  </div>


</template>

<script>
export default {
  head() {
    return {
      title: 'JhayRhic' + ' | SSC'
    }
  },
  data() {
    return {
      dateFormat: 'D MMM',
      dateOne: '',
      dateTwo: ''
    }
  },
  methods: {
    formatDates(dateOne, dateTwo) {
      let formattedDates = ''
      if (dateOne) {
        formattedDates = format(dateOne, this.dateFormat)
      }
      if (dateTwo) {
        formattedDates += ' - ' + format(dateTwo, this.dateFormat)
      }
      return formattedDates
    }
  }
}
</script>

<style>
.back{
  background-image: url('~assets/img/fir.jpg');
}
.contain{
  background-color: white;
}
.center {
  margin: auto;
  width: 50%;
  padding: 10px;
}
.right {
  margin: auto;
  width: 50%;
  padding: 10px;
}
.text{
  color: white;
}
page-enter-active, .page-leave-active {
      transition: all .30s ease-out;
    }
    .page-enter, .page-leave-active {
      opacity: 0;
      transform-origin: 50% 50%;
    }
</style>