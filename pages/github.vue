<template>
  <div class="text-sm text-gray-800 bg-github-gray">
    <nav class="flex items-center justify-between px-4 py-3 text-white bg-gray-900">

      <div class="flex items-center space-x-4">
        <a href="#" class="text-white hover:text-gray-400">
          <svg class="w-8 fill-current" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path>
          </svg>
        </a>

        <div class="relative">
          <input type="text" class="px-3 py-1 placeholder-white bg-gray-700 rounded w-72"
                 placeholder="Search or jump to...">
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div class="px-2 mr-2 text-xs text-gray-400 border border-gray-600 rounded">/</div>
          </div>
        </div>

        <ul class="flex items-center space-x-4 font-semibold">
          <li><a href="#" class="hover:text-gray-400">Pull Requests</a></li>
          <li><a href="#" class="hover:text-gray-400">Issues</a></li>
          <li><a href="#" class="hover:text-gray-400">Marketplace</a></li>
          <li><a href="#" class="hover:text-gray-400">Explore</a></li>
        </ul>

      </div> <!-- end of left -->

      <div class="flex items-center space-x-4 text-white">
        <a href="#" class="relative hover:text-gray-400">
          <svg class="w-4 fill-current" viewBox="0 0 16 16" aria-hidden="true">
            <path
              d="M8 16a2 2 0 001.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 008 16z"></path>
            <path fill-rule="evenodd"
                  d="M8 1.5A3.5 3.5 0 004.5 5v2.947c0 .346-.102.683-.294.97l-1.703 2.556a.018.018 0 00-.003.01l.001.006c0 .002.002.004.004.006a.017.017 0 00.006.004l.007.001h10.964l.007-.001a.016.016 0 00.006-.004.016.016 0 00.004-.006l.001-.007a.017.017 0 00-.003-.01l-1.703-2.554a1.75 1.75 0 01-.294-.97V5A3.5 3.5 0 008 1.5zM3 5a5 5 0 0110 0v2.947c0 .05.015.098.042.139l1.703 2.555A1.518 1.518 0 0113.482 13H2.518a1.518 1.518 0 01-1.263-2.36l1.703-2.554A.25.25 0 003 7.947V5z"></path>
          </svg>
          <div class="absolute top-0 right-0 w-2 h-2 bg-blue-600 rounded-full"
               style="margin-top: -2px; margin-right: -1px"></div>
        </a>

        <a href="#" class="flex items-center hover:text-gray-400">
          <svg class="w-4 fill-current" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M8 2a.75.75 0 01.75.75v4.5h4.5a.75.75 0 010 1.5h-4.5v4.5a.75.75 0 01-1.5 0v-4.5h-4.5a.75.75 0 010-1.5h4.5v-4.5A.75.75 0 018 2z"></path>
          </svg>
          <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>

        </a>

        <a href="#" class="flex items-center hover:text-gray-400">
          <img class="w-5 rounded-full" alt="@samfurlong"
               src="https://avatars2.githubusercontent.com/u/7388567?s=60&amp;v=4">
          <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"
               xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>

        </a>


      </div>

    </nav> <!--  end of nav  -->

    <!--  Repo Stats  -->
    <div class="flex items-center justify-between px-8 py-4">
      <div class="flex">
        <svg class="w-4 text-gray-600 fill-current" viewBox="0 0 16 16" aria-hidden="true">
          <path fill-rule="evenodd"
                d="M4 4v2h-.25A1.75 1.75 0 002 7.75v5.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 13.25v-5.5A1.75 1.75 0 0012.25 6H12V4a4 4 0 10-8 0zm6.5 2V4a2.5 2.5 0 00-5 0v2h5zM12 7.5h.25a.25.25 0 01.25.25v5.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-5.5a.25.25 0 01.25-.25H12z"></path>
        </svg>
        <div class="flex items-center ml-2 text-xl">
          <a href="#" class="text-blue-600 hover:underline">tailwindcss</a>
          <span class="ml-1">/</span>
          <a href="#" class="ml-1 font-semibold text-blue-600 hover:underline">tailwindcss</a>
        </div>

        <div class="flex items-center justify-center ml-2">
          <div class="h-5 px-2 text-xs font-semibold text-gray-600 border border-gray-400 rounded-full">Private
          </div>
        </div>
      </div>

      <div class="flex space-x-2 text-xs">
        <div class="flex">
          <button
            class="flex items-center px-3 py-1 space-x-1 border border-gray-400 rounded rounded-r-none hover:bg-gray-200">
            <svg class="w-4 fill-current" viewBox="0 0 16 16" aria-hidden="true">
              <path fill-rule="evenodd"
                    d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"></path>
            </svg>
            <div class="font-semibold">Watch</div>
            <svg class="w-4 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                 xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
            </svg>
          </button>
          <a href="#"
             class="px-3 py-1 font-semibold border border-l-0 border-gray-400 rounded rounded-l-none hover:text-blue-600">430</a>
        </div>

        <div class="flex">
          <button
            class="flex items-center px-3 py-1 space-x-1 border border-gray-400 rounded rounded-r-none hover:bg-gray-200">
            <svg class="w-4 h-3" viewBox="0 0 16 16" aria-hidden="true">
              <path fill-rule="evenodd"
                    d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"></path>
            </svg>
            <div class="font-semibold">Star</div>
          </button>
          <a href="#"
             class="px-3 py-1 font-semibold border border-l-0 border-gray-400 rounded rounded-l-none hover:text-blue-600">23.5k</a>
        </div>

        <div class="flex">
          <button
            class="flex items-center px-3 py-1 space-x-1 border border-gray-400 rounded rounded-r-none hover:bg-gray-200">
            <svg class="w-4 h-3" viewBox="0 0 16 16" aria-hidden="true">
              <path fill-rule="evenodd"
                    d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"></path>
            </svg>
            <div class="font-semibold">Fork</div>
          </button>
          <a href="#"
             class="px-3 py-1 font-semibold border border-l-0 border-gray-400 rounded rounded-l-none hover:text-blue-600">1.2k</a>
        </div>
      </div>

    </div> <!--  end of repo-stats  -->

    <ul class="flex items-center px-8 mt-4 border-b border-gray-400 repo-nav">
      <li class="font-semibold">
        <a href="#" class="flex items-center px-4 pb-3 space-x-2 border-b-2 border-red-500">
          <svg class="w-4 fill-current" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M4.72 3.22a.75.75 0 011.06 1.06L2.06 8l3.72 3.72a.75.75 0 11-1.06 1.06L.47 8.53a.75.75 0 010-1.06l4.25-4.25zm6.56 0a.75.75 0 10-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 101.06 1.06l4.25-4.25a.75.75 0 000-1.06l-4.25-4.25z"></path>
          </svg>
          <span> Code </span>
        </a>
      </li>

      <li class="">
        <a href="#"
           class="flex items-center px-4 pb-3 space-x-2 duration-150 border-b-2 border-transparent hover:border-gray-400 transition-ease-in-out">
          <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"></path>
          </svg>
          <span> Issues </span>
          <span class="px-2 text-xs bg-gray-300 rounded-full">8</span>
        </a>
      </li>

      <li class="">
        <a href="#"
           class="flex items-center px-4 pb-3 space-x-2 duration-150 border-b-2 border-transparent hover:border-gray-400 transition-ease-in-out">
          <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"></path>
          </svg>
          <span> Pull Requests </span>
          <span class="px-2 text-xs bg-gray-300 rounded-full">8</span>
        </a>
      </li>

      <li class="">
        <a href="#"
           class="flex items-center px-4 pb-3 space-x-2 duration-150 border-b-2 border-transparent hover:border-gray-400 transition-ease-in-out">
          <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M1.5 2.75a.25.25 0 01.25-.25h8.5a.25.25 0 01.25.25v5.5a.25.25 0 01-.25.25h-3.5a.75.75 0 00-.53.22L3.5 11.44V9.25a.75.75 0 00-.75-.75h-1a.25.25 0 01-.25-.25v-5.5zM1.75 1A1.75 1.75 0 000 2.75v5.5C0 9.216.784 10 1.75 10H2v1.543a1.457 1.457 0 002.487 1.03L7.061 10h3.189A1.75 1.75 0 0012 8.25v-5.5A1.75 1.75 0 0010.25 1h-8.5zM14.5 4.75a.25.25 0 00-.25-.25h-.5a.75.75 0 110-1.5h.5c.966 0 1.75.784 1.75 1.75v5.5A1.75 1.75 0 0114.25 12H14v1.543a1.457 1.457 0 01-2.487 1.03L9.22 12.28a.75.75 0 111.06-1.06l2.22 2.22v-2.19a.75.75 0 01.75-.75h1a.25.25 0 00.25-.25v-5.5z"></path>
          </svg>
          <span> Discussions </span>
        </a>
      </li>

      <li class="">
        <a href="#"
           class="flex items-center px-4 pb-3 space-x-2 duration-150 border-b-2 border-transparent hover:border-gray-400 transition-ease-in-out">
          <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"></path>
          </svg>
          <span> Actions </span>
        </a>
      </li>

      <li class="">
        <a href="#"
           class="flex items-center px-4 pb-3 space-x-2 duration-150 border-b-2 border-transparent hover:border-gray-400 transition-ease-in-out">
          <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"></path>
          </svg>
          <span> Security </span>
        </a>
      </li>

      <li class="">
        <a href="#"
           class="flex items-center px-4 pb-3 space-x-2 duration-150 border-b-2 border-transparent hover:border-gray-400 transition-ease-in-out">
          <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true">
            <path fill-rule="evenodd"
                  d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"></path>
          </svg>
          <span> Insights </span>
        </a>
      </li>

    </ul>

  </div>
</template>

