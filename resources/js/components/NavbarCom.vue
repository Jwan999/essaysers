<template>
  <nav id="header" class="fixed flex justify-center w-full content-center z-30 top-0">

    <div class="w-11/12 flex flex-wrap items-center justify-between my-5">
      <!--logo-->
      <div>
        <a class="toggleColour no-underline hover:no-underline font-bold text-2xl lg:text-4xl text-white" href="#">
          <div>
            <svg width="180px" viewBox="0 0 332 97" version="1.1" xmlns="http://www.w3.org/2000/svg"
                 xmlns:xlink="http://www.w3.org/1999/xlink">
              <title>Page 1</title>
              <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"
                 font-family="MLingWaiMedium-TC, LingWai TC" font-weight="400" letter-spacing="5">
                <g id="Group-5" transform="translate(-1.000000, -30.000000)" fill="#FFFFFF" stroke="#FFFFFF">
                  <text id="Essays" stroke-width="3" font-size="100">
                    <tspan x="0" y="106">Essays</tspan>
                  </text>
                  <text id="ers." stroke-opacity="0.822880245" stroke-width="3.5" font-size="60"
                        fill-opacity="0.822880245">
                    <tspan x="248" y="106">ers.</tspan>
                  </text>
                </g>
              </g>
            </svg>
          </div>

        </a>
      </div>
      <!--nav content-->
      <div
          class="w-full lg:items-center lg:w-auto hidden lg:block mt-2 lg:mt-0 lg:bg-transparent p-4 lg:p-0 z-20"
          id="nav-content">
        <ul class="list-reset lg:flex justify-end flex-1 items-center">
          <li class="mr-3">
            <a class="inline-block py-2 px-4 text-white font-bold no-underline" href="#">About us</a>
          </li>
          <li class="mr-3">
            <a class="inline-block text-white no-underline hover:text-white hover:text-underline py-2 px-4" href="#">Contact Us</a>
          </li>
          <li class="mr-3">
            <a class="inline-block text-white no-underline hover:text-white hover:text-underline py-2 px-4" href="#">Get help or advice?</a>
          </li>
        </ul>
      </div>
      <!--button-->
      <div>
        <button
            class="font-semibold text-lg text-red-100 rounded-full py-3 px-8 shadow-md bg-red-500 hover:shadow-2xl
hover:text-white">
          Add an essay
        </button>
      </div>
      <!--burgermenu-->
      <div class="block lg:hidden">
        <a id="nav-toggle"
           class="flex items-center cursor-pointer outline-none p-1 text-orange-800 hover:text-gray-900">
          <svg class="fill-current h-6 w-6 text-white outline-none" xmlns="http://www.w3.org/2000/svg"
               viewBox="0 0 24 24">
            <path
                d="M12,7a2,2,0,1,0-2-2A2,2,0,0,0,12,7Zm0,10a2,2,0,1,0,2,2A2,2,0,0,0,12,17Zm0-7a2,2,0,1,0,2,2A2,2,0,0,0,12,10Z"/>
          </svg>
          <!--          <svg class="fill-current h-6 w-6" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">-->
          <!--            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>-->
          <!--          </svg>-->
        </a>
      </div>
    </div>

  </nav>

</template>

<script>
export default {
  mounted() {
    console.log('Component mounted.')
  }
}
</script>
