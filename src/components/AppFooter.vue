<template>
  <footer class="mt-16 pb-16 text-sm leading-6">
    <div class="max-w-7xl mx-auto divide-y divide-gray-200 px-4 sm:px-6 md:px-8">
      <div class="flex">
        <div class="flex-none w-1/2 space-y-10 sm:space-y-8 lg:flex lg:space-y-0">
          <div class="lg:flex-none lg:w-1/2">
            <h2 class="font-semibold text-gray-900">組織資訊</h2>
            <ul class="mt-3 space-y-2">
              <li><a class="hover:text-gray-900" href="#">核心成員</a></li>
              <li><a class="hover:text-gray-900" href="#">財務報表</a></li>
              <li><a class="hover:text-gray-900" href="#">關於組織</a></li>
            </ul>
          </div>
          <div class="lg:flex-none lg:w-1/2">
            <h2 class="font-semibold text-gray-900">產品列表</h2>
            <ul class="mt-3 space-y-2">
              <li><a class="hover:text-gray-900" href="#">Swollen</a></li>
              <li><a class="hover:text-gray-900" href="#">Sara 無密碼式身分認證系統</a></li>
              <li><a class="hover:text-gray-900" href="#">meow 微型部落格社交平台</a></li>
              <li><a class="hover:text-gray-900" href="#">更多產品</a></li>
            </ul>
          </div>
        </div>
        <div class="flex-none w-1/2 space-y-10 sm:space-y-8 lg:flex lg:space-y-0">
          <div class="lg:flex-none lg:w-1/2">
            <h2 class="font-semibold text-gray-900">就業資源</h2>
            <ul class="mt-3 space-y-2">
              <li><a class="hover:text-gray-900" href="#">徵才平台</a></li>
              <li><a class="hover:text-gray-900" href="#">求職平台</a></li>
              <li><a class="hover:text-gray-900" href="#">職場討論</a></li>
            </ul>
          </div>
          <div class="lg:flex-none lg:w-1/2">
            <h2 class="font-semibold text-gray-900">學習資源</h2>
            <ul class="mt-3 space-y-2">
              <li><a class="hover:text-gray-900" target="_blank" href="#">為什麼我要更新瀏覽器呢？</a></li>
              <li><a class="hover:text-gray-900" target="_blank" href="#">網際網路基礎觀念</a></li>
              <li><a class="hover:text-gray-900" target="_blank" href="https://ncurl.xyz/s/b0AIBYTnR">JavaScript 基礎教學（MDN）</a></li>
              <li><a class="hover:text-gray-900" target="_blank" href="#">網際網路後端伺服器開發基礎（Express.js）</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="max-w-7xl mx-auto mt-11 divide-y divide-gray-200 px-4 sm:px-6 md:px-8 text-sky-700">
      <a class="mr-3" href="https://github.com/web-tech-tw/web-tech-tw.github.io">網站原始碼</a>
      <router-link class="mr-3" to="/privacy">隱私權政策</router-link>
    </div>
    <div class="max-w-7xl mx-auto mt-5 divide-y divide-gray-200 px-4 sm:px-6 md:px-8">
      &copy; 2022 臺灣網際網路技術推廣組織 Taiwan Web Technology Promotion Organization (Web Tech TW)
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter'
}
</script>
