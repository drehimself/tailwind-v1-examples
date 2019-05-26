<template>
  <div class="font-sans bg-gray-200">
    <header class="bg-white flex flex-col lg:flex-row items-center justify-between p-4">
      <div class="w-32">
        <a href="/"><img src="~assets/img/logo-meetup.svg" alt="logo"></a>
      </div>
      <ul class="flex items-center text-sm text-gray-600">
        <li class="border-r border-gray-400 pr-4 mr-4"><a href="#" class="text-red-600 font-bold">Start a new group</a></li>
        <li class="mr-6"><a href="#" class="hover:text-red-600">Explore</a></li>
        <li class="mr-6"><a href="#" class="hover:text-red-600">Messages</a></li>
        <li class="mr-6 relative">
          <a href="#" class="hover:text-red-600">Notifications</a>
          <div class="absolute w-2 h-2 rounded-full bg-green-500 right-0 top-0" style="right:-10px"></div>
        </li>
        <li>
          <a href="#" class="flex items-center">
            <img src="https://res.cloudinary.com/dqzxpn5db/image/upload/v1554258216/andremadarang.com/dre.jpg" alt="avatar" class="rounded-full w-8 h-8">
            <svg class="w-4 h-4" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"></path></svg>
          </a>
        </li>
      </ul>
    </header>

    <div class="bg-meetup-blue text-center py-8 pb-20">
      <div class="text-white text-4xl font-bold">Find your next event</div>
      <div class="text-gray-400">
        <span class="mr-2">41 events in your groups</span>
        <span class="mr-2">&middot;</span>
        <span>3,981 events near you</span>
      </div>
    </div>

    <div class="container mx-auto px-8 xl:px-40 mb-8">
      <div class="bg-gray-900 text-white flex flex-col lg:flex-row items-center justify-between p-3 -mt-8">
        <div class="flex flex-col lg:flex-row items-center">
          <span class="relative my-4 lg:my-1">
            <input type="text" placeholder="Search" class="text-gray-600 rounded px-2 py-3 w-72">
            <span class="absolute right-0 top-0 mr-3" style="top:10px">
              <svg class="text-gray-600" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"></path></svg>
            </span>
          </span>
          <span class="ml-4">
            within <a href="#" class="border-b border-gray-500 hover:border-gray-100">50 miles</a> of <a href="#" class="border-b border-gray-500 hover:border-gray-100">Mississauga, Ontario</a>
          </span>
        </div>
        <div class="flex items-center my-4 lg:my-0">
          <button class="border-l border-b border-t border-gray-700 px-6 py-2">Groups</button>
          <button class="border-r border-b border-t border-gray-700 bg-gray-700 text-white px-6 py-2 font-bold">Calendar</button>
        </div>
      </div>
    </div> <!-- end container -->

    <div class="container mx-auto px-8 xl:px-40 flex flex-col flex-col-reverse lg:flex-row pb-8">
      <div class="w-full lg:w-7/10">
        <div class="pl-3 uppercase font-bold text-sm py-2 pb-4 sticky top-0 bg-gray-200">
          Saturday, May 25
        </div>

        <div class="events border border-gray-400 bg-white mb-8">
          <div class="event border-b border-gray-400 flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>
          <div class="event border-b border-gray-400 flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>
          <div class="event flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>

        </div> <!-- end events -->

        <div class="pl-3 uppercase font-bold text-sm py-2 pb-4 sticky top-0 bg-gray-200">
          Monday, May 27
        </div>

        <div class="events border border-gray-400 bg-white mb-8">
          <div class="event border-b border-gray-400 flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>
          <div class="event border-b border-gray-400 flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>
          <div class="event flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>

        </div> <!-- end events -->

        <div class="border-t border-b border-gray-400 py-8 mb-8">
          <div class="text-center font-bold text-2xl mb-2">
            Host events in Mississauga
          </div>
          <div class="text-center mb-8">Can't find what you're looking for? Create a Meetup group to start hosting local events.</div>

          <div class="flex flex-col sm:flex-row -mx-2">
            <div class="w-full sm:w-1/2 mx-2 bg-white shadow mb-4">
              <div class="px-6 py-4">
                <div class="font-bold"><a href="#">Usability</a></div>
                <div class="text-gray-700 mb-1">593 Follow this topic</div>
                <div><a href="#" class="text-teal-600 hover:underline">Host events</a></div>
              </div>
            </div>

            <div class="w-full sm:w-1/2 mx-2 bg-white shadow mb-4">
              <div class="px-6 py-4">
                <div class="font-bold"><a href="#">Web Development</a></div>
                <div class="text-gray-700 mb-1">11,079 follow this topic</div>
                <div><a href="#" class="text-teal-600 hover:underline">Host events</a></div>
              </div>
            </div>
          </div>
          <div class="flex flex-col sm:flex-row -mx-2">
            <div class="w-full sm:w-1/2 mx-2 bg-white shadow mb-4">
              <div class="px-6 py-4">
                <div class="font-bold"><a href="#">Technology</a></div>
                <div class="text-gray-700 mb-1">10,093 Follow this topic</div>
                <div><a href="#" class="text-teal-600 hover:underline">Host events</a></div>
              </div>
            </div>

            <div class="w-full sm:w-1/2 mx-2 bg-white shadow mb-4">
              <div class="px-6 py-4">
                <div class="font-bold"><a href="#">PHP</a></div>
                <div class="mb-1 text-gray-700">1,227 follow this topic</div>
                <div><a href="#" class="text-teal-600 hover:underline">Host events</a></div>
              </div>
            </div>
          </div>
        </div>

        <div class="pl-3 uppercase font-bold text-sm py-2 pb-4 sticky top-0 bg-gray-200">
          Tuesday, May 28
        </div>

        <div class="events border border-gray-400 bg-white mb-8">
          <div class="event border-b border-gray-400 flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>
          <div class="event border-b border-gray-400 flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>
          <div class="event flex p-4">
            <div class="w-16 mr-4 text-gray-600"><a href="#">6:00PM</a></div>
            <div>
              <div class="uppercase font-bold text-gray-700 text-sm"><a href="#">Mississauga .NET user group</a></div>
              <div class="font-bold text-gray-800 text-xl"><a href="#">Visual Studio 2019 Launch Party</a></div>
              <div class="text-gray-600">31 .NET coders going</div>
            </div>
          </div>

        </div> <!-- end events -->
      </div>

      <div class="w-full lg:w-3/10 ml-0 lg:ml-6">
        <div class="pt-2 pb-4">
          &nbsp;
        </div>

        <div class="border border-gray-400 bg-white text-sm mb-8">
          <div class="border-b border-gray-400 flex px-4 py-2">
            <a href="#">All upcoming events</a>
          </div>
          <div class="border-b border-gray-400 flex font-bold bg-purple-100 text-meetup-purple">
            <div class="border-l-4 border-meetup-purple px-4 pl-3 py-2">
              <a href="#">Your groups and suggestions</a>
            </div>
          </div>
          <div class="border-b border-gray-400 flex px-4 py-2">
            <a href="#">Your groups only</a>
          </div>
          <div class="flex px-4 py-2">
            <a href="#">Your events only</a>
          </div>
        </div>

        <div class="flex lg:justify-end mb-4">
          <button class="bg-white px-4 py-1 text-sm border border-gray-500">Today</button>
        </div>

          <div class="datepicker-trigger mb-4">
            <input
              class="hidden"
              type="text"
              id="datepicker-trigger"
              placeholder="Select dates"
              :value="formatDates(dateOne, dateTwo)"
            >

            <AirbnbStyleDatepicker
              :trigger-element-id="'datepicker-trigger'"
              :mode="'single'"
              :inline="true"
              :monthsToShow="1"
              :date-one="dateOne"
              @date-one-selected="val => { dateOne = val }"
            />
          </div>


        <div class="flex lg:justify-center mb-8">
          <a href="#" class="flex">
            <svg class="mr-2" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M19 6.41L8.7 16.71a1 1 0 1 1-1.4-1.42L17.58 5H14a1 1 0 0 1 0-2h6a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0V6.41zM17 14a1 1 0 0 1 2 0v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7c0-1.1.9-2 2-2h5a1 1 0 0 1 0 2H5v12h12v-5z"></path></svg>
            <span>Export to...</span>
          </a>
        </div>
      </div>
    </div> <!-- end container -->

    <footer class="bg-gray-900 text-white">
      <div class="container mx-auto px-8 xl:px-40 py-8">
        <div class="flex items-center justify-between border-b border-gray-700 pb-4 mb-4">
          <div><a href="#" class="font-bold">Start a new group</a></div>
          <div><a href="#">Logout</a></div>
        </div>
        <div class="links mb-8">
          <ul class="flex">
            <li class="mr-4"><a href="#">Help</a></li>
            <li class="mr-4"><a href="#">About Us</a></li>
            <li class="mr-4"><a href="#">Meetup Pro</a></li>
            <li class="mr-4"><a href="#">Jobs</a></li>
            <li class="mr-4"><a href="#">Apps</a></li>
            <li class="mr-4"><a href="#">API</a></li>
            <li class="mr-4"><a href="#">Topics</a></li>
            <li class="mr-4"><a href="#">Browse Cities</a></li>
            <li class="mr-4"><a href="#">Blog</a></li>
          </ul>
        </div>
        <div class="social mb-6">
          <div>Follow us</div>
          <div>Lazy to put social icons here</div>
        </div>

        <div class="copyright text-sm text-gray-400 mb-4">
          &copy; 2019 Meetup
        </div>

        <div class="privacy">
          <ul class="flex">
            <li class="mr-4"><a href="#">Privacy</a></li>
            <li class="mr-4"><a href="#">Terms</a></li>
          </ul>
        </div>
      </div>
    </footer>

  </div>
</template>

<script>
import format from 'date-fns/format'

export default {
  head() {
    return {
      title: 'Meetup' + ' | Tailwind CSS v1.0 - Examples of Web Pages'
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
  .asd__days-legend {
    width: 288px !important;
  }

  .asd__wrapper--datepicker-open {
    width: 288px !important;
  }

  .asd__month {
    width: 295px !important;
  }
</style>
