<script>
    import "../app.css";
  </script>


<nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-900">
	<div class="container flex flex-wrap items-center justify-between mx-auto">
	  <a href="/" class="flex items-center">
		  <img src="/images/dht32b.svg" class="h-6 mr-3 sm:h-9" alt="Downhole Testing Logo" />
		  <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white">Downhole Testing</span>
	  </a>
	  <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-default" aria-expanded="false">
		<span class="sr-only">Open main menu</span>
		<svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
	  </button>
	  <div class="hidden w-full md:block md:w-auto" id="navbar-default">
		<ul class="flex flex-col p-4 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
		  <li>
			<a href="/" class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white" aria-current="page">Home</a>
		  </li>
		  <li>
			<a href="/tech" class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Our Technology</a>
		  </li>
		  <li>
			<a href="/contact" class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Contact</a>
		  </li>
		  <li>

		</ul>
	  </div>
	</div>
  </nav>
  

<!-- <nav class="flex items-center justify-between flex-wrap p-6">
	<div class="flex items-center flex-shrink-0 text-gray-800 mr-6">
		<a
        class="mt-2 mr-2 flex items-center text-neutral-900 hover:text-neutral-900 focus:text-neutral-900 dark:text-neutral-200 dark:hover:text-neutral-400 dark:focus:text-neutral-400 lg:mt-0"
        href="/">
        <img
          src="/images/dht32b.svg"
          style="height: 35px"
          alt=""
          loading="lazy" />
      </a>
	  <span class="font-semibold text-xl tracking-tight">Downhole Testing</span>
	</div>
	<div class="block lg:hidden">
	  <button class="flex items-center px-3 py-2 border rounded text-gray-800 border-gray-400 hover:text-white hover:border-white">
		<svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
	  </button>
	</div>
	<div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
	  <div class="text-lg font-medium lg:flex-grow content-center">
		<a href="/" class="block mt-4 lg:inline-block lg:mt-0 text-blue-600 hover:text-white mr-4">
		  Home
		</a>
		<a href="/tech" class="block mt-4 lg:inline-block lg:mt-0 text-blue-600 hover:text-white mr-4">
		  Our Technology
		</a>

	  </div>
	  <div>
		
	  </div>
	</div>
  </nav> -->

<!-- <header>
	<div class="mx-auto flex max-w-7xl items-center justify-between p-4 bg-neutral-300">
		<a href="/"><svg class="h-6" viewBox="0 0 111 21"><path class="fill-rose-600" d="M9.45569.11334C9.33771.0392836 9.20123.0 9.06194.0c-.1393.0-.27577.0392836-.39375.11334-.94292.60914-1.81132 1.32652-2.5875 2.1375-1.725 1.79062-2.64375 3.74062-2.64375 5.625.0 1.49184.59263 2.92256 1.64752 3.97746s3.97748 1.6475 3.97748 1.6475 2.92256-.5926 3.97746-1.6475 1.6475-2.48562 1.6475-3.97746c0-4.49063-5.01559-7.63125-5.23121-7.7625zM9.06194 12.0008c-.29582.0013-.58896-.0561-.86251-.1687-.27354-.1126-.52207-.2783-.73125-.4875-.20918-.2092-.37486-.4577-.4875-.7313-.11263-.2735-.16998-.5666-.16874-.86246.0-2.25 2.25-3.75 2.25-3.75s2.24996 1.5 2.24996 3.75c.0013.29586-.0561.58896-.1687.86246-.1126.2736-.2783.5221-.4875.7313-.2092.2092-.4577.3749-.73126.4875-.27354.1126-.56668.17-.8625.1687zm8.96246 6.975c-.0477.1518-.1424.2845-.2705.3788-.1281.0944-.2829.1456-.442.1462-.0766.0014-.1529-.0113-.225-.0375l-8.02496-2.55-8.025 2.55c-.072085.0262-.148343.0389-.225003.0375-.159092-6e-4-.313864-.0518-.441943-.1462-.128079-.0943-.22283-.227-.2705568-.3788-.0304549-.0935-.0419719-.1922-.0338781-.2902.0080939-.098.0356359-.1935.0810189-.2807.045383-.0873.107697-.1647.183304-.2276s.162993-.1102.257055-.139l6.000003-1.9125-6.000003-1.9125c-.101479-.0226-.197151-.066-.280941-.1276-.08379-.0615-.153868-.1398-.205786-.2299-.0519183-.0901-.0845418-.19-.09579985-.2933-.01125803-.1034-90453e-8-.2079.03040305-.3071.0313075-.0991.0828848-.1907.1514588-.2688.068574-.0781.152646-.1412.246879-.1851s.196569-.0678.30051-.07c.103942-.0023.20722.0171.303279.0568l8.025 2.55 8.02496-2.55c.0961-.0397.1994-.0591.3033-.0568.104.0022.2063.0261.3005.07.0943.0439.1783.107.2469.1851.0686.0781.1202.1697.1515.2688.0313.0992.0416.2037.0304.3071-.0113.1033-.0439.2032-.0958.2933-.052.0901-.122.1684-.2058.2299-.0838.0616-.1795.105-.281.1276l-6 1.9125 6 1.9125c.0941.0288.1815.0761.2571.139s.1379.1403.1833.2276c.0454.0872.0729.1827.081.2807s-.0034.1967-.0339.2902z"></path><path class="fill-gray-900" d="M30.3039 17.24c-.9467.0-1.8-.1467-2.56-.44-.76-.3067-1.4067-.7533-1.94-1.34-.5334-.6-.9467-1.34-1.24-2.22-.2934-.8933-.44-1.9333-.44-3.12.0-1.17334.1466-2.21334.44-3.12.2933-.92.7066-1.68667 1.24-2.3.5333-.62667 1.18-1.1 1.94-1.42s1.6133-.48 2.56-.48c1.2933.0 2.36.26666 3.2.8.84.52 1.5133 1.34666 2.02 2.48l-2.62 1.36c-.1867-.58667-.48-1.05334-.88-1.4-.3867-.36-.96-.54-1.72-.54-.8934.0-1.6134.29333-2.16.88-.5334.57333-.8 1.41333-.8 2.52v2.24c0 1.1067.2666 1.9533.8 2.54.5466.5733 1.2666.86 2.16.86.7466.0 1.34-.2 1.78-.6.4533-.4133.7866-.9067 1-1.48l2.48 1.44c-.52 1.0667-1.2067 1.8933-2.06 2.48-.84.5733-1.9067.86-3.2.86zm13.0673-2c-.08.28-.3067.5467-.48.8-.1733.24-.3867.4533-.64.64-.24.1733-.52.3067-.84.4-.3067.1067-.6267.16-.96.16-1.3333.0-2.34-.4667-3.02-1.4-.68-.9467-1.02-2.3133-1.02-4.1.0-1.78667.34-3.14667 1.02-4.08.68-.93334 1.6867-1.4 3.02-1.4.68.0 1.28.18666 1.8.56.5333.37333.9733.85333 1.12 1.44V6.5h2.96V17h-2.96v-1.76zm-1.94-.4c.56.0 1.02-.1333 1.38-.4.3733-.28.56-.66.56-1.14v-3.1c0-.48-.1867-.85334-.56-1.12-.36-.28-.82-.42-1.38-.42s-1.0267.2-1.4.6c-.36.38666-.54.9133-.54 1.58v1.82c0 .6667.18 1.2.54 1.6.3733.3867.84.58 1.4.58zM48.4992 17V6.5h2.96v1.78c.1866-.56.6266-1.03334 1.08-1.42.4533-.4 1.0733-.6 1.86-.6.72.0 1.3333.18 1.84.54.5066.36.8733.88666 1.1 1.58.0933-.29334.2933-.56667.48-.82.2-.26667.44-.49334.72-.68.28-.18667.5933-.33334.94-.44.3467-.12.72-.18 1.12-.18 1.0133.0 1.7866.36 2.32 1.08.5466.72.82 1.74666.82 3.08V17h-2.96v-6.34c0-1.33334-.48-2-1.44-2-.44.0-.84.12666-1.2.38-.36.25333-.54.64-.54 1.16V17h-2.96v-6.34c0-1.33334-.48-2-1.44-2-.2134.0-.4267.03333-.64.1-.2.05333-.3867.14666-.56.28-.16.13333-.2934.3-.4.5-.0934.18666-.14.40666-.14.66V17h-2.96zM65.7703 6.5h2.96v1.76c.1466-.58667.58-1.06667 1.1-1.44.5333-.37334 1.14-.56 1.82-.56 1.3333.0 2.34.46666 3.02 1.4.68.93333 1.02 2.29333 1.02 4.08.0 1.7867-.34 3.1533-1.02 4.1-.68.9333-1.6867 1.4-3.02 1.4-.3467.0-.6734-.0533-.98-.16-.3067-.0933-.5867-.2267-.84-.4-.24-.1867-.4467-.4-.62-.64-.1734-.2533-.4-.52-.48-.8V21h-2.96V6.5zm4.9 8.34c.56.0 1.02-.1933 1.38-.58.3733-.4.56-.9333.56-1.6v-1.82c0-.6667-.1867-1.19334-.56-1.58-.36-.4-.82-.6-1.38-.6s-1.0267.14-1.4.42c-.36.26666-.54.64-.54 1.12v3.1c0 .48.18.86.54 1.14.3733.2667.84.4 1.4.4zM77.4982 17V3.04h9.26v2.7h-6.22V8.6h5.3v2.68h-5.3V17h-3.04zM89.9175 5.38c-.6.0-1.04-.13334-1.32-.4-.2667-.28-.4-.63334-.4-1.06v-.44c0-.42667.1333-.77334.4-1.04.28-.28.72-.42 1.32-.42s1.0333.14 1.3.42c.28.26666.42.61333.42 1.04v.44c0 .42666-.14.78-.42 1.06-.2667.26666-.7.4-1.3.4zm-1.48 1.12h2.96V17h-2.96V6.5zM93.5601 17V6.5h2.96v2.28c.0534-.29334.2467-.57334.38-.84.1334-.28.3067-.52667.52-.74.2267-.21334.4934-.38.8-.5.3067-.13334.6667-.2 1.08-.2h.52v2.76h-.74c-.8666.0-1.5133.11333-1.94.34-.4133.22666-.62.6467-.62 1.26V17h-2.96zM105.328 17.24c-.8.0-1.513-.1267-2.14-.38-.626-.2667-1.16-.6333-1.6-1.1-.426-.48-.753-1.06-.98-1.74-.213-.68-.32-1.44-.32-2.28.0-.8267.107-1.5733.32-2.24.214-.68.527-1.26.94-1.74.427-.48.947-.84667 1.56-1.1.614-.26667 1.314-.4 2.1-.4.867.0 1.607.14666 2.22.44.627.29333 1.134.68666 1.52 1.18.4.49333.687 1.06666.86 1.72.187.64.28 1.3133.28 2.02v.88h-6.74v.16c0 .6933.187 1.2467.56 1.66.374.4.96.6 1.76.6.614.0 1.114-.12 1.5-.36.387-.2533.747-.5533 1.08-.9l1.48 1.84c-.466.5467-1.08.9733-1.84 1.28-.746.3067-1.6.46-2.56.46zm-.06-8.8c-.6.0-1.073.2-1.42.6-.333.38666-.5.90666-.5 1.56v.16h3.68v-.18c0-.64-.146-1.15334-.44-1.54-.28-.4-.72-.6-1.32-.6z"></path></svg></a>
		<nav class="hidden items-center space-x-2 text-sm font-medium text-gray-800 md:flex">
		<a href="/" class="rounded bg-white px-3 py-2 transition hover:bg-gray-100">Home</a>
		<a href="/tech" class="rounded bg-white px-3 py-2 transition hover:bg-gray-100">Our Technology</a>
	</nav><button class="flex appearance-none p-1 text-gray-500 md:hidden"><svg class="h-6 w-6" fill="currentcolor" viewBox="0 0 256 256"><line x1="40" y1="128" x2="216" y2="128" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"></line><line x1="40" y1="64" x2="216" y2="64" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"></line><line x1="40" y1="192" x2="216" y2="192" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="24"></line></svg></button>
</div>
</header> -->







  <slot />

  <footer class="footer items-center p-4 bg-neutral text-neutral-content">
	<div class="flex flex-row justify-around" >
	 <p></p>
	 <p class="text-center">
		?? 2023 : Downhole Testing Ltd - All rights reserved
	</p>
	<div class="flex flex-row">
		<!-- <a href="https://www.linkedin.com/"><svg class="w-8 h-8" viewBox="0 0 24 24"><path d="M19,3A2,2 0 0,1 21,5V19A2,2 0 0,1 19,21H5A2,2 0 0,1 3,19V5A2,2 0 0,1 5,3H19M18.5,18.5V13.2A3.26,3.26 0 0,0 15.24,9.94C14.39,9.94 13.4,10.46 12.92,11.24V10.13H10.13V18.5H12.92V13.57C12.92,12.8 13.54,12.17 14.31,12.17A1.4,1.4 0 0,1 15.71,13.57V18.5H18.5M6.88,8.56A1.68,1.68 0 0,0 8.56,6.88C8.56,5.95 7.81,5.19 6.88,5.19A1.69,1.69 0 0,0 5.19,6.88C5.19,7.81 5.95,8.56 6.88,8.56M8.27,18.5V10.13H5.5V18.5H8.27Z" /></svg></a> -->
		<!-- <a href="https://www.google.com/"><svg class="w-8 h-8" viewBox="0 0 24 24"><path d="M12,2A10,10 0 0,1 22,12A10,10 0 0,1 12,22A10,10 0 0,1 2,12A10,10 0 0,1 12,2M12,4A8,8 0 0,0 4,12C4,14.09 4.8,16.06 6.03,17.54L14.9,9.9C13.55,8.92 12,7.5 12,6C12,4.5 13.5,4 15,4A3,3 0 0,1 18,7C18,7.35 17.94,7.7 17.83,8.06L20.24,10.45C20.33,10 20.33,9.7 20.24,9.39L18.83,7.97C19.3,7.19 19.3,6.2 18.83,5.41L20.82,3.42C20.93,3.15 21,2.89 21,2.62A4,4 0 0,0 17,2A4,4 0 0,0 13,6C13,6.31 12.94,6.65 12.83,7L14.9,9C15.06,8.7 15.12,8.37 15.12,8A4,4 0 0,0 11,4C11,4 10.87,4 10.74,4L12,4M7,9C7.55,9 8,9.45 8,10C8,10.55 7.55,11 7,11C6.45,11 6,10.55 6,10C6,9.45 6.45,9 7,9M17,9C17.55,9 18,9.45 18,10C18,10.55 17.55,11 17,11C16.45,11 16,10.55 16,10C16,9.45 16.45,9 17,9M12,14C13.75,14 15.29,14.72 16.19,15.81L14.77,17.23C14.32,16.5 13.25,16 12,16C10.75,16 9.68,16.5 9.23,17.23L7.81,15.81C8.71,14.72 10.25,14 12,14Z" /></svg></a> -->
	
	</div>
	
	</div>
  </footer>