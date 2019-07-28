<template>
  <div class="flex">
    <div class=" bg-gray-900 w-20 flex-none flex flex-col min-h-screen h-screen px-2 py-2">
      <div class="channel-bar overflow-y-auto">
        <ul class="text-center">
          <li><a href="#"><img src="/icon_discord.svg" alt="discord" class="w-12 h-12 rounded-full mx-auto"></a></li>
          <li class="border-b border-gray-700 mx-4 mt-3"></li>
          <li class="mt-3"><a href="#"><img src="/icon_laravel.svg" alt="laravel" class="w-12 h-12 rounded-full mx-auto"></a></li>
          <li class="mt-3"><a href="#"><img src="/icon_tailwind.svg" alt="tailwind" class="w-12 h-12 rounded-full mx-auto"></a></li>
          <li class="mt-3"><a href="#"><img src="/icon_vue.svg" alt="vue" class="w-12 h-12 rounded-full mx-auto"></a></li>
          <li class="mt-3">
            <a href="#" class="w-12 h-12 bg-gray-800 hover:bg-teal-500 text-teal-500 hover:text-white inline-block rounded-full">
              <svg fill="currentColor" class="mt-3 mx-auto" width="24" height="24" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
            </a>
          </li>
          <li class="mt-2">
            <a href="#" class="w-12 h-12 bg-gray-800 hover:bg-teal-500 text-teal-500 hover:text-white inline-block rounded-full">
              <svg fill="currentColor" class="mt-3 mx-auto" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"></path></svg>
            </a>
          </li>
          <li class="border-b border-gray-700 mx-4 mt-3"></li>
          <li class="mt-3">
            <a href="#" class="w-12 h-12 bg-gray-800 hover:bg-teal-500 text-teal-500 hover:text-white inline-block rounded-full">
              <svg fill="currentColor" class="mt-3 mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M11 14.59V3a1 1 0 0 1 2 0v11.59l3.3-3.3a1 1 0 0 1 1.4 1.42l-5 5a1 1 0 0 1-1.4 0l-5-5a1 1 0 0 1 1.4-1.42l3.3 3.3zM3 17a1 1 0 0 1 2 0v3h14v-3a1 1 0 0 1 2 0v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-3z"></path></svg>
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div class="flex-1 flex flex-col min-h-screen h-screen">
      <div class="flex text-white h-12">
        <div class="bg-gray-800 w-56 flex-none flex items-center justify-between border-b border-gray-900 px-3 py-2">
          <div>Tailwind CSS</div>
          <button>
            <svg fill="currentColor" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"></path></svg>
          </button>
        </div>
        <div class="flex-1 bg-gray-750 flex items-center justify-between border-b border-gray-900 px-4">
          <div class="flex items-center">
            <div class="text-gray-500 text-2xl">#</div>
            <div class="ml-2 text-sm text-white">general</div>
            <div class="border-l pl-3 ml-3 border-gray-600 text-xs text-gray-400">general discussion of Tailwind CSS</div>
          </div>
          <div class="flex items-center">
            <a href="#" class="ml-4">
              <svg class="w-6 h-6 text-gray-500 hover:text-gray-200" fill="currentColor" width="24" height="24" viewBox="0 0 24 24"><path d="M12 22c1.1 0 2-.9 2-2h-4c0 1.1.89 2 2 2zm6-6v-5c0-3.07-1.64-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.63 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2z"></path></svg>
            </a>
            <a href="#" class="ml-4">
              <svg class="w-6 h-6 text-gray-500 hover:text-gray-200" fill="currentColor" viewBox="0 0 24 24"><path class="secondary" d="M2.24 20.35l6.5-7.5a1 1 0 0 1 1.47-.06l1 1a1 1 0 0 1-.06 1.47l-7.5 6.5c-.93.8-2.22-.48-1.4-1.41z"></path><path class="primary" d="M15 15.41V18a1 1 0 0 1-.3.7l-1 1a1 1 0 0 1-1.4 0l-8-8a1 1 0 0 1 0-1.4l1-1A1 1 0 0 1 6 9h2.59L13 4.59V3a1 1 0 0 1 1.7-.7l7 7A1 1 0 0 1 21 11h-1.59L15 15.41z"></path></svg>
            </a>
            <a href="#" class="ml-4">
              <svg class="w-6 h-6 text-gray-500 hover:text-gray-200" fill="currentColor" width="24" height="24" viewBox="0 0 24 24"><path d="M0 0h24v24H0z" fill="none"></path><path d="M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 5 8 5C6.34 5 5 6.34 5 8s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V19h14v-2.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V19h6v-2.5c0-2.33-4.67-3.5-7-3.5z"></path></svg>
            </a>
            <a href="#" class="ml-4">
              <form action="#" class="relative">
                <input type="text" placeholder="Search" class="rounded bg-gray-900 text-gray-200 text-xs px-2 py-1">
                <span class="absolute right-0 top-0 mr-1" style="top:6px">
                  <svg class="w-4 h-4 text-gray-500 hover:text-gray-200" fill="currentColor" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"></path></svg>
                </span>
              </form>
            </a>
            <a href="#" class="ml-4">
              <svg class="w-6 h-6 text-gray-500 hover:text-gray-200" fill="currentColor" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M15.6 15.47A4.99 4.99 0 0 1 7 12a5 5 0 0 1 10 0v1.5a1.5 1.5 0 1 0 3 0V12a8 8 0 1 0-4.94 7.4 1 1 0 1 1 .77 1.84A10 10 0 1 1 22 12v1.5a3.5 3.5 0 0 1-6.4 1.97zM12 15a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path></svg>
            </a>
            <a href="#" class="ml-4">
              <svg class="w-6 h-6 text-gray-500 hover:text-gray-200" fill="currentColor" viewBox="0 0 24 24"><g data-name="Layer 2"><g data-name="menu-arrow-circle"><rect width="24" height="24" transform="rotate(180 12 12)" opacity="0"></rect><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2zm0 16a1 1 0 1 1 1-1 1 1 0 0 1-1 1zm1-5.16V14a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1 1.5 1.5 0 1 0-1.5-1.5 1 1 0 0 1-2 0 3.5 3.5 0 1 1 4.5 3.34z"></path></g></g></svg>
            </a>
          </div>
        </div>
      </div>
      <div class="flex-1 flex overflow-y-hidden">
        <div class="bg-gray-800 w-56 flex-none flex flex-col justify-between">
          <div class="hashtag-bar text-sm overflow-y-auto">
            <ul class="px-2 py-3">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">welcome</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">faq</span>
                </a>
              </li>
            </ul>

            <button class="flex items-center text-gray-500 hover:text-gray-200">
              <svg fill="currentColor" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"></path></svg>
              <h3 class="uppercase tracking-wide font-semibold text-xs">Tailwind CSS</h3>
            </button>

            <ul class="px-2 py-3 pt-2">
              <li class="text-gray-200 px-2 hover:text-gray-200 hover:bg-gray-900 bg-gray-750 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">general</span>
                </a>
              </li>
              <li class="text-gray-200 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">core-dev</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">course</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">plugins</span>
                </a>
              </li>
              <li class="text-gray-200 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">docs</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">showcase</span>
                </a>
              </li>
              <li class="text-gray-200 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">help</span>
                </a>
              </li>
            </ul>

            <button class="flex items-center text-gray-500 hover:text-gray-200">
              <svg fill="currentColor" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"></path></svg>
              <h3 class="uppercase tracking-wide font-semibold text-xs">Community</h3>
            </button>

            <ul class="px-2 py-3 pt-2">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">feedback</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">jobs</span>
                </a>
              </li>
            </ul>

            <button class="flex items-center text-gray-500 hover:text-gray-200">
              <svg fill="currentColor" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"></path></svg>
              <h3 class="uppercase tracking-wide font-semibold text-xs">Off Topic</h3>
            </button>

            <ul class="px-2 py-3 pt-2">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">design</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">development</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">random</span>
                </a>
              </li>
            </ul>
          </div>
          <div class="bg-gray-850 px-2 py-2 flex items-center justify-between">
            <div class="flex items-center">
              <a href="#"><img src="/avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a>
              <div class="text-xs ml-2">
                <div class="text-white">drehimself</div>
                <div class="text-gray-500 text-xxs">#9589</div>
              </div>
            </div>
            <div class="flex items-center text-gray-500">
              <a href="#" class="hover:text-white">
                <svg class="w-5 h-5" fill="currentColor" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 14c1.66 0 2.99-1.34 2.99-3L15 5c0-1.66-1.34-3-3-3S9 3.34 9 5v6c0 1.66 1.34 3 3 3zm5.3-3c0 3-2.54 5.1-5.3 5.1S6.7 14 6.7 11H5c0 3.41 2.72 6.23 6 6.72V21h2v-3.28c3.28-.48 6-3.3 6-6.72h-1.7z"></path><path d="M0 0h24v24H0z" fill="none"></path></svg>
              </a>
              <a href="#" class="ml-3 hover:text-white">
                <svg class="w-5 h-5" fill="currentColor" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M0 0h24v24H0z" opacity=".1" fill="none"></path><path d="M12 1c-4.97 0-9 4.03-9 9v7c0 1.66 1.34 3 3 3h3v-8H5v-2c0-3.87 3.13-7 7-7s7 3.13 7 7v2h-4v8h3c1.66 0 3-1.34 3-3v-7c0-4.97-4.03-9-9-9z"></path></svg>
              </a>
              <a href="#" class="ml-3 hover:text-white">
                <svg class="w-5 h-5" fill="currentColor" width="24" height="24" viewBox="0 0 24 24"><path d="M0 0h24v24H0z" fill="none"></path><path d="M19.43 12.98c.04-.32.07-.64.07-.98s-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.12-.22-.39-.3-.61-.22l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1c-.23-.09-.49 0-.61.22l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98s.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46c.12.22.39.3.61.22l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.23.09.49 0 .61-.22l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zM12 15.5c-1.93 0-3.5-1.57-3.5-3.5s1.57-3.5 3.5-3.5 3.5 1.57 3.5 3.5-1.57 3.5-3.5 3.5z"></path></svg>
              </a>
            </div>
          </div>
        </div>
        <div class="flex-1 flex justify-between">
          <div class="bg-gray-750 flex-1 flex flex-col justify-between">
            <div class="chat text-sm text-gray-400 overflow-y-auto">
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>yeah hahaha</div>
                    <div>some other comment</div>
                    <div>why are you so awesome</div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>Here are the <a href="#" class="text-blue-400 hover:underline">Tailwind docs</a></div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>Does that result in the raw svg being inlined in the DOM?</div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>This is handy if you don't want to load SVG as a separate file.</div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>Exactly the same way as in Vue <a href="#" class="text-indigo-400 hover:underline">@impulse</a></div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>I think it can slow down the page if there's too much bloat in the document.</div>
                    <div>Compared to loading it externally.</div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>Comparison would be better if it's not also comparing an vector svg to a raster gif, it's a difference in rendering too.</div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>Thank you that works perfectly! Turns out my z-index (or lack of setting one) was also messing things up on the navbar.</div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>yeah i never really use z-index</div>
                    <div>for anything heh</div>
                  </div>
                </div>
              </div>
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700">
                <div class="flex-none"><a href="#"><img src="avatar.jpg" alt="avatar" class="w-10 h-10 rounded-full"></a></div>
                <div class="ml-5">
                  <div>
                    <a href="#" class="text-white hover:underline">drehimself</a>
                    <span class="text-xs text-gray-600 ml-1">07/17/2019</span>
                  </div>
                  <div>
                    <div>awesome thats cool to hear!</div>
                  </div>
                </div>
              </div>


            </div>
            <div class="bg-gray-750 h-24 flex items-center mx-3 border-t border-gray-600">
              <button class="px-2 py-2 h-10 bg-gray-700 rounded-l text-gray-500 hover:text-white border-r border-gray-600">
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><g data-name="Layer 2"><g data-name="plus-circle"><rect width="24" height="24" opacity="0"></rect><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2zm3 11h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2V9a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2z"></path></g></g></svg>
              </button>
              <div class="flex-1">
                <input type="text" class="w-full text-sm h-10 px-2 py-2 bg-gray-700 text-gray-200 focus:outline-none">
              </div>
              <div class="px-2 py-2 bg-gray-700 rounded-r flex items-center h-10">
                <button class="h-10 bg-gray-700 rounded-l text-gray-500 hover:text-white">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 512 512"><path d="M32 448c0 17.7 14.3 32 32 32h160V320H32v128zm448-288h-42.1c6.2-12.1 10.1-25.5 10.1-40 0-48.5-39.5-88-88-88-41.6 0-68.5 21.3-103 68.3-34.5-47-61.4-68.3-103-68.3-48.5 0-88 39.5-88 88 0 14.5 3.8 27.9 10.1 40H32c-17.7 0-32 14.3-32 32v80c0 8.8 7.2 16 16 16h480c8.8 0 16-7.2 16-16v-80c0-17.7-14.3-32-32-32zm-326.1 0c-22.1 0-40-17.9-40-40s17.9-40 40-40c19.9 0 34.6 3.3 86.1 80h-86.1zm206.1 0h-86.1c51.4-76.5 65.7-80 86.1-80 22.1 0 40 17.9 40 40s-17.9 40-40 40zm-72 320h160c17.7 0 32-14.3 32-32V320H288v160z"></path></svg>
                  </button>
                  <button class="h-10 bg-gray-700 rounded-l text-gray-500 hover:text-white ml-3">
                    <svg class="w-8 h-8" fill="currentColor" width="24" height="24" viewBox="0 0 24 24"><defs><path id="a" d="M24 24H0V0h24v24z"></path></defs><clipPath id="b"><use xlink:href="#a" overflow="visible"></use></clipPath><path d="M11.5 9H13v6h-1.5zM9 9H6c-.6 0-1 .5-1 1v4c0 .5.4 1 1 1h3c.6 0 1-.5 1-1v-2H8.5v1.5h-2v-3H10V10c0-.5-.4-1-1-1zm10 1.5V9h-4.5v6H16v-2h2v-1.5h-2v-1z" clip-path="url(#b)"></path></svg>
                  </button>
                  <button class="h-10 bg-gray-700 rounded-l text-gray-500 hover:text-white ml-3">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 496 512"><path d="M248 8C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zm80 168c17.7 0 32 14.3 32 32s-14.3 32-32 32-32-14.3-32-32 14.3-32 32-32zm-160 0c17.7 0 32 14.3 32 32s-14.3 32-32 32-32-14.3-32-32 14.3-32 32-32zm194.8 170.2C334.3 380.4 292.5 400 248 400s-86.3-19.6-114.8-53.8c-13.6-16.3 11-36.7 24.6-20.5 22.4 26.9 55.2 42.2 90.2 42.2s67.8-15.4 90.2-42.2c13.4-16.2 38.1 4.2 24.6 20.5z"></path></svg>
                  </button>
              </div>
            </div>
          </div>

          <div class="sidebar-users bg-gray-800 w-56 flex-none px-3 py-3 overflow-y-auto">
            <h3 class="uppercase tracking-wide font-semibold text-xs text-gray-500 mb-2">Core Team — 1</h3>
            <ul class="mb-6">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <span><a href="#"><img src="/avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></span>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
            </ul>
            <h3 class="uppercase tracking-wide font-semibold text-xs text-gray-500 mb-2">Online — 243</h3>

            <ul class="mb-6">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2">
                <a href="#" class="flex items-center">
                  <div><a href="#"><img src="avatar.jpg" alt="avatar" class="w-8 h-8 rounded-full"></a></div>
                  <span class="ml-2">adamwathan</span>
                </a>
              </li>
            </ul>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>
