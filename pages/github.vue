<template>
  <div class="text-gray-900 text-sm">
    <nav class="bg-gray-900 text-white px-4 py-3 flex items-center justify-between">
      <div class="flex items-center space-x-4">
        <a href="#" class="text-white hover:text-gray-400">
          <svg class="w-8 fill-current" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
        </a>
        <div class="hidden lg:block relative">
          <input type="text" class="rounded bg-gray-700 placeholder-white w-72 px-3 py-1" placeholder="Search or jump to...">
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div class="border border-gray-600 rounded text-xs text-gray-400 px-2 mr-2">/</div>
          </div>
        </div>
        <ul class="hidden lg:flex items-center font-semibold space-x-4">
          <li><a href="#" class="hover:text-gray-400">Pull Requests</a></li>
          <li><a href="#" class="hover:text-gray-400">Issues</a></li>
          <li><a href="#" class="hover:text-gray-400">Marketplace</a></li>
          <li><a href="#" class="hover:text-gray-400">Explore</a></li>
        </ul>
      </div>
      <div class="flex items-center space-x-4 text-white">
        <a href="#" class="relative hover:text-gray-400">
          <svg class="w-5" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path></svg>
          <div class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0"></div>
        </a>
        <a href="#" class="flex items-center hover:text-gray-400">
          <svg class="w-4" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M12 4v16m8-8H4"></path></svg>
          <svg class="w-3 ml-1" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M19 9l-7 7-7-7"></path></svg>
        </a>
        <a href="#" class="flex items-center hover:text-gray-400">
          <img src="https://avatars0.githubusercontent.com/u/4316355?s=60&v=4" class="w-5 h-5 rounded-full" alt="avatar">
          <svg class="w-3 ml-1" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M19 9l-7 7-7-7"></path></svg>
        </a>
      </div>
    </nav>
    <div class="repo-stats flex flex-col lg:flex-row items-center justify-between px-8 py-4">
      <div class="flex">
        <svg class="w-4 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"></path></svg>
        <div class="flex items-center text-xl ml-2">
          <a href="#" class="text-blue-600 hover:underline">tailwindcss</a>
          <span class="ml-1">/</span>
          <a href="#" class="text-blue-600 hover:underline font-semibold ml-1">tailwindcss</a>
        </div>
      </div>
      <div class="flex space-x-2 mt-4 lg:mt-0">
        <div class="flex text-xs">
          <button class="border border-gray-400 rounded rounded-r-none px-3 py-1 hover:bg-gray-200 flex items-center space-x-1">
            <svg class="fill-current text-gray-600 w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"></path></svg>
            <div>Watch</div>
            <svg class="w-3 ml-1" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M19 9l-7 7-7-7"></path></svg>
          </button>
          <a href="#" class="border border-gray-400 rounded rounded-l-none border-l-0 font-semibold hover:text-blue-600 px-3 py-1">430</a>
        </div>
        <div class="flex text-xs">
          <button class="border border-gray-400 rounded rounded-r-none px-3 py-1 hover:bg-gray-200 flex items-center space-x-1">
            <svg class="fill-current text-gray-600 w-4" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"></path></svg>
            <div class="">Star</div>
          </button>
          <a href="#" class="border border-gray-400 border-l-0 rounded rounded-l-none font-semibold px-3 py-1 hover:text-blue-600">25.3k</a>
        </div>
        <div class="flex text-xs">
          <button class="border border-gray-400 rounded rounded-r-none px-3 py-1 hover:bg-gray-200 flex items-center space-x-1">
            <svg class="fill-current text-gray-600 w-4" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"></path></svg>
            <div class="">Fork</div>
          </button>
          <a href="#" class="border border-gray-400 border-l-0 rounded rounded-l-none font-semibold px-3 py-1 hover:text-blue-600">1.2k</a>
        </div>
      </div>
    </div> <!-- end repo-stats -->

    <ul class="repo-nav border-b border-gray-400 flex items-center px-8 mt-4">
      <li class="font-semibold">
        <a href="#" class="flex items-center border-b-2 border-red-500 px-4 pb-3">
          <svg class="w-4 fill-current" classes="UnderlineNav-octicon" display="none inline" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M4.72 3.22a.75.75 0 011.06 1.06L2.06 8l3.72 3.72a.75.75 0 11-1.06 1.06L.47 8.53a.75.75 0 010-1.06l4.25-4.25zm6.56 0a.75.75 0 10-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 101.06 1.06l4.25-4.25a.75.75 0 000-1.06l-4.25-4.25z"></path></svg>
          <span class="ml-2">Code</span>
        </a>
        <li>
          <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
            <svg class="w-4 fill-current text-gray-600" classes="UnderlineNav-octicon" display="none inline" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"></path></svg>
            <span class="ml-2">Issues</span>
            <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">106</div>
          </a>
        </li>
      <li>
        <a href="#" class="flex items-center border-b-2 border-transparent px-4 pb-3 hover:border-gray-400 transition ease-in duration-150">
          <svg class="w-4 fill-current text-gray-600" classes="UnderlineNav-octicon" display="none inline" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"></path></svg>
          <span class="ml-2">Pull Requests</span>
          <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">25</div>
        </a>
      </li>
      <li class="hidden lg:block">
        <a href="#" class="flex items-center border-b-2 border-transparent px-4 pb-3 hover:border-gray-400 transition ease-in duration-150">
          <svg class="w-4 fill-current text-gray-600" classes="UnderlineNav-octicon" display="none inline" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.5 2.75a.25.25 0 01.25-.25h8.5a.25.25 0 01.25.25v5.5a.25.25 0 01-.25.25h-3.5a.75.75 0 00-.53.22L3.5 11.44V9.25a.75.75 0 00-.75-.75h-1a.25.25 0 01-.25-.25v-5.5zM1.75 1A1.75 1.75 0 000 2.75v5.5C0 9.216.784 10 1.75 10H2v1.543a1.457 1.457 0 002.487 1.03L7.061 10h3.189A1.75 1.75 0 0012 8.25v-5.5A1.75 1.75 0 0010.25 1h-8.5zM14.5 4.75a.25.25 0 00-.25-.25h-.5a.75.75 0 110-1.5h.5c.966 0 1.75.784 1.75 1.75v5.5A1.75 1.75 0 0114.25 12H14v1.543a1.457 1.457 0 01-2.487 1.03L9.22 12.28a.75.75 0 111.06-1.06l2.22 2.22v-2.19a.75.75 0 01.75-.75h1a.25.25 0 00.25-.25v-5.5z"></path></svg>
          <span class="ml-2">Discussions</span>
        </a>
      </li>
      <li class="hidden lg:block">
        <a href="#" class="flex items-center border-b-2 border-transparent px-4 pb-3 hover:border-gray-400 transition ease-in duration-150">
          <svg class="w-4 fill-current text-gray-600" classes="UnderlineNav-octicon" display="none inline" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"></path></svg>
          <span class="ml-2">Actions</span>
        </a>
      </li>
      <li class="hidden lg:block">
        <a href="#" class="flex items-center border-b-2 border-transparent px-4 pb-3 hover:border-gray-400 transition ease-in duration-150">
          <svg class="w-4 fill-current text-gray-600" classes="UnderlineNav-octicon" display="none inline" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"></path></svg>
          <span class="ml-2">Security</span>
        </a>
      </li>
      <li class="hidden lg:block">
        <a href="#" class="flex items-center border-b-2 border-transparent px-4 pb-3 hover:border-gray-400 transition ease-in duration-150">
          <svg class="w-4 fill-current text-gray-600" classes="UnderlineNav-octicon" display="none inline" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"></path></svg>
          <span class="ml-2">Insights</span>
        </a>
      </li>
      </li>
    </ul> <!-- end repo-nav -->
    <div class="container mx-auto my-8 px-4 flex flex-col lg:flex-row">
      <div class="file-explorer-container w-full lg:w-3/4 lg:mr-8">
        <div class="branch-navigation flex items-center justify-between">
          <div class="flex items-center space-x-3">
            <button class="border border-gray-400 rounded-md px-4 py-1 hover:bg-gray-200 flex items-center space-x-2">
              <svg class="fill-current text-gray-600 w-4" text="gray" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path></svg>
            <div class="font-semibold">master</div>
            <svg class="w-3 ml-1" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M19 9l-7 7-7-7"></path></svg>
            </button>
            <a href="#" class="hidden lg:flex items-center space-x-2 py-1 group">
              <svg class="fill-current text-gray-600 group-hover:text-blue-600 w-4" text="gray" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path></svg>
              <span class="group-hover:text-blue-600">
                <span class="font-semibold">25 </span>
                <span class="text-gray-600">branches</span>
              </span>
            </a>
            <a href="#" class="hidden py-1 lg:flex items-center space-x-2 group">
              <svg class="fill-current text-gray-600 group-hover:text-blue-600 w-4" text="gray" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"></path></svg>
              <span class="text-gray-700 group-hover:text-blue-600">
                <span class="font-semibold">79</span>
                <span class="text-gray-600">tags</span>
              </span>
            </a>
          </div>
          <div class="hidden lg:flex items-center space-x-2">
            <button class="border border-gray-400 rounded-md px-3 py-1 hover:bg-gray-200 flex items-center space-x-2">
              <div class="font-semibold">Go to file</div>
            </button>
            <button class="border border-gray-400 rounded-md px-3 py-1 hover:bg-gray-200 flex items-center space-x-1">
              <div class="font-semibold">Add file</div>
              <svg class="w-4" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
            </button>
            <button class="font-semibold border border-gray-400 rounded-md text-white bg-green-600 hover:bg-green-700 px-4 py-1 flex items-center space-x-2">
              <svg class="w-4 fill-current text-gray-200" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.47 10.78a.75.75 0 001.06 0l3.75-3.75a.75.75 0 00-1.06-1.06L8.75 8.44V1.75a.75.75 0 00-1.5 0v6.69L4.78 5.97a.75.75 0 00-1.06 1.06l3.75 3.75zM3.75 13a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5z"></path></svg>
              <div>Code</div>
              <svg class="w-3 ml-1" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M19 9l-7 7-7-7"></path></svg>
            </button>
          </div>
        </div> <!-- end branch-navigation -->

        <div class="commits-container bg-blue-100 rounded-md rounded-b-none border border-blue-200 border-b-0 flex items-center justify-between px-4 py-4 mt-5">
          <div class="flex items-center space-x-2">
            <a href="#"><img src="https://avatars2.githubusercontent.com/u/4323180?s=60&u=4962a4441fae9fba5f0f86456c6c506a21ffca4f&v=4" alt="avatar" class="w-6 h-6 rounded-full"></a>
            <a href="#" class="font-semibold hover:underline">adamwathan</a>
            <a href="#" class="hover:underline hover:text-blue-600">1.5.1</a>
          </div>
          <div class="flex items-end">
            <a href="#">
              <svg  class="w-4 fill-current text-green-500" aria-label="3 / 3 checks OK" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
            </a>
            <a href="#" class="font-mono text-xs text-gray-600 hover:underline hover:text-blue-500 ml-2 hidden lg:block">da070bd</a>
            <a href="#" class="text-gray-600 hover:underline hover:text-blue-500 ml-2">4 days ago</a>
            <a href="#" class="flex items-center ml-3">
              <svg class="w-4 fill-current text-gray-600" text="gray" viewBox="0 0 16 16" version="1.1" aria-hidden="true"><path fill-rule="evenodd" d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"></path></svg>
              <span class="ml-1">
                <span class="font-semibold">3,040</span>
                <span class="hidden lg:inline">commits</span>
              </span>
            </a>
          </div>
        </div> <!-- end commits-container -->
        <div class="file-explorer rounded-md rounded-t-none border border-gray-400 text-gray-700 divide-y divide-gray-400">
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-blue-400" color="blue-3" aria-label="Directory" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">.github</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Update issues template</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">11 days ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-blue-400" color="blue-3" aria-label="Directory" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">__tests__</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Remove stale test</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">4 days ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-blue-400" color="blue-3" aria-label="Directory" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">dist</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Add empty .npmignore so dist files are distributed with releases</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">3 years ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-blue-400" color="blue-3" aria-label="Directory" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">jest</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Use `process.env.JEST_WORKER_ID`</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">15 months ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-blue-400" color="blue-3" aria-label="Directory" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">scripts</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Prevent source maps from being generated</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">21 days ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-blue-400" color="blue-3" aria-label="Directory" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">src</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Only wrap with variants if rules don't already contain any variants</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">4 days ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-blue-400" color="blue-3" aria-label="Directory" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">stubs</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Generate responsive variants for container by default</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">4 days ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-gray-600" color="gray-light" aria-label="File" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">.editorconfig</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Convert new stuff to use ES6 modules</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">3 years ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-gray-600" color="gray-light" aria-label="File" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">.eslintignore</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Updated CLI init commend</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">16 months ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-gray-600" color="gray-light" aria-label="File" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">.eslintrc.json</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Disable lint rule for TODO comments</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">3 months ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-gray-600" color="gray-light" aria-label="File" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">plugin.js</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600 truncate hidden lg:block">Add new `plugin` and `plugin.withOptions` functions for creating plugins</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">7 months ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-gray-600" color="gray-light" aria-label="File" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">README.md</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Add alt attribute to logo</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">2 months ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-gray-600" color="gray-light" aria-label="File" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">tailwind.css</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Undo accidental changes to CDN build process</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">7 months ago</div>
          </div>
          <div class="flex justify-between px-4 py-2 hover:bg-gray-200">
            <div class="w-4/12 flex items-center">
              <svg class="w-4 fill-current text-gray-600" color="gray-light" aria-label="File" viewBox="0 0 16 16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">utilities.css</a>
            </div>
            <div class="w-6/12 truncate hidden lg:block"><a href="#" class="hover:underline hover:text-blue-600">Move CSS files to root for easier imports</a></div>
            <div class="w-4/12 lg:w-2/12 text-right">2 years ago</div>
          </div>
        </div> <!-- end file-explorer -->

        <div class="readme-container rounded-md border border-gray-400 px-4 py-4 mt-4">
          <h4 class="font-semibold">README.md</h4>
          <div v-html="readme" class="prose max-w-none px-4"></div>
        </div> <!-- end readme-container -->

      </div> <!-- end file-explorer-container -->
      <div class="sidebar w-full lg:w-1/4">
        <div class="about mt-4 lg:mt-0">
          <h4 class="text-base font-semibold">About</h4>
          <p class="text-base mt-4">A utility-first CSS framework for rapid UI development.</p>

          <div class="flex items-center space-x-2 mt-4">
            <svg class="w-4 fill-current" mr="2" classes="flex-shrink-0" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>
            <a href="#" class="text-blue-600 hover:underline font-semibold">tailwindcss.com/</a>
          </div>

          <div class="tags text-xs font-semibold flex items-center flex-wrap mt-2">
            <a href="#" class="bg-blue-100 hover:bg-blue-200 text-blue-600 rounded-full px-2 py-1 mt-2 mr-2">tailwindcss</a>
            <a href="#" class="bg-blue-100 hover:bg-blue-200 text-blue-600 rounded-full px-2 py-1 mt-2 mr-2">css</a>
            <a href="#" class="bg-blue-100 hover:bg-blue-200 text-blue-600 rounded-full px-2 py-1 mt-2 mr-2">css-framework</a>
            <a href="#" class="bg-blue-100 hover:bg-blue-200 text-blue-600 rounded-full px-2 py-1 mt-2 mr-2">postcss</a>
            <a href="#" class="bg-blue-100 hover:bg-blue-200 text-blue-600 rounded-full px-2 py-1 mt-2 mr-2">functional-css</a>
            <a href="#" class="bg-blue-100 hover:bg-blue-200 text-blue-600 rounded-full px-2 py-1 mt-2 mr-2">utility-classes</a>
            <a href="#" class="bg-blue-100 hover:bg-blue-200 text-blue-600 rounded-full px-2 py-1 mt-2 mr-2">responsive</a>
          </div>

          <a href="#" class="flex items-center space-x-2 mt-4 group">
            <svg class="w-4 fill-current text-gray-600 group-hover:text-blue-600" mr="2" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path></svg>
            <span class="text-gray-600 group-hover:text-blue-600">Readme</span>
          </a>

          <a href="#" class="flex items-center space-x-2 mt-4 group">
            <svg class="w-4 fill-current text-gray-600 group-hover:text-blue-600" mr="2" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"></path></svg>
            <span class="text-gray-600 group-hover:text-blue-600">MIT License</span>
          </a>
        </div> <!-- end about -->
        <div class="releases border-t border-gray-400 mt-6 pt-6">
          <h4 class="text-base font-semibold flex items-center">
            <span>Releases</span>
            <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">79</div>
          </h4>

          <a href="#" class="flex items-start mt-4 group">
            <svg class="fill-current mt-1 w-4 text-green-500 group-hover:text-blue-500" mt="1" classes="flex-shrink-0" color="green" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"></path></svg>
            <span class="ml-2">
              <span class="font-semibold group-hover:text-blue-600">v1.5.1</span>
              <span class="ml-1 text-xs border border-green-500 text-green-600 rounded-full font-semibold inline-block px-2">Latest</span>
              <span class="block text-xs group-hover:text-blue-600">6 days ago</span>
            </span>
          </a>

          <div class="mt-4">
            <a href="#" class="text-blue-600 hover:underline text-xs">+ 78 releases</a>
          </div>
        </div> <!-- end releases -->

        <div class="used-by border-t border-gray-400 mt-6 pt-6">
          <h4 class="text-base font-semibold flex items-center">
            <span>Used By</span>
            <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">5,000+</div>
          </h4>

          <div class="mt-4">
            <a href="#" class="flex items-center -space-x-2">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/antonyzotov/128.jpg" class="w-8 border-2 border-white rounded-full" alt="avatar">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/pcridesagain/128.jpg" class="w-8 rounded-full border-2 border-white" alt="avatar">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/davidhemphill/128.jpg" class="w-8 rounded-full border-2 border-white" alt="avatar">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/abdots/128.jpg" class="w-8 rounded-full border-2 border-white" alt="avatar">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/kerem/128.jpg" class="w-8 rounded-full border-2 border-white" alt="avatar">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/runningskull/128.jpg" class="w-8 rounded-full border-2 border-white" alt="avatar">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/gusoto/128.jpg" class="w-8 rounded-full border-2 border-white" alt="avatar">
              <img src="https://s3.amazonaws.com/uifaces/faces/twitter/rodnylobos/128.jpg" class="w-8 rounded-full border-2 border-white" alt="avatar">
              <span class="text-xs text-blue-600 font-semibold hover:underline" style="margin-left:0.5rem">+ 58,357</span>
            </a>
          </div>
        </div> <!-- end used-by -->

        <div class="contributors border-t border-gray-400 mt-6 pt-6">
          <h4 class="text-base font-semibold flex items-center">
            <span>Contributors</span>
            <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">115</div>
          </h4>

          <div class="flex items-center flex-wrap mt-2">
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/vitorleal/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/byryan/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/juamperro/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/herkulano/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/jlsolerdeltoro/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/kostaspt/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/trubeatto/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/stan/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/sandywoodruff/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
            <a href="#"><img src="https://s3.amazonaws.com/uifaces/faces/twitter/chacky14/128.jpg" alt="avatar" class="w-8 rounded-full mr-2 mt-2"></a>
          </div>

          <div class="mt-4">
            <a href="#" class="text-blue-600 hover:underline text-xs">+ 104 contributors</a>
          </div>
        </div> <!-- end contributors -->

        <div class="languages border-t border-gray-400 mt-6 pt-6">
          <h4 class="text-base font-semibold">Languages</h4>
          <div class="mt-4 flex">
            <div class="w-11/12 h-2 rounded-md rounded-r-none bg-purple-700"></div>
            <div class="w-1/12 h-2 rounded-md rounded-l-none bg-yellow-400"></div>
          </div>
          <ul class="mt-2 flex space-x-8 items-center text-xs">
            <li class="flex items-center">
              <span class="w-2 h-2 rounded-full bg-purple-700"></span>
              <span class="ml-4">
                <span class="font-semibold">CSS </span>
                <span>93.9%</span>
              </span>
            </li>
            <li class="flex items-center">
              <span class="w-2 h-2 rounded-full bg-yellow-400"></span>
              <span class="ml-4">
                <span class="font-semibold">JavaScript </span>
                <span>6.1%</span>
              </span>
            </li>
          </ul>
        </div> <!-- end languages -->
      </div> <!-- end sidebar -->
    </div>

    <footer class="container mx-auto text-xs border-t border-gray-400 py-10 flex flex-col lg:flex-row items-center justify-between">
      <ul class="flex items-center space-x-6 lg:space-x-12">
        <li>&copy; 2020 GitHub, Inc.</li>
        <li><a href="#" class="text-blue-500 hover:underline">Terms</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">Privacy</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">Security</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">Status</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">Help</a></li>
      </ul>
      <div class="mx-16 hidden lg:block">
        <a href="#">
          <svg class="w-6 fill-current text-gray-400 hover:text-gray-600" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
        </a>
      </div>
      <ul class="flex items-center space-x-6 lg:space-x-12 mt-4 lg:mt-0">
        <li><a href="#" class="text-blue-500 hover:underline">Contact GitHub</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">Pricing</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">API</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">Training</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">Blog</a></li>
        <li><a href="#" class="text-blue-500 hover:underline">About</a></li>
      </ul>
    </footer>
  </div>
</template>

<script>
import readme from './readme-tailwind.md'

export default {
  computed: {
    readme() {
      return readme
    }
  }
}
</script>
