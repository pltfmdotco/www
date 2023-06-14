---
layout: default
title: PLTFM
bodyclass: "md:bg-gradient-to-bl bg-gradient-to-b bg-no-repeat md:from-indigo-700 from-indigo-500 md:from-5% via-pink-200 md:via-pink-600 md:via-20% md:to-white-500 md:to-white md:to-40%"
---
    <div class="container mx-auto px-6 md:px-0 py-10">
      <header class="flex items-center justify-between">
        <h1 class="text-2xl text-white md:text-black font-extrabold">PLTFM</h1>
        <nav>
          <ul class="flex space-x-4 text-white">
            <li><a href="#">About</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </nav>
      </header>

      <main class="flex flex-col md:mt-16"></main>
    </div>
    <div class="md:hidden block w-full h-full bg-black">
      <div class="pt-6 text-center md:text-left">
        <div>
          <p class="text-white font-inter font-light">
            Sign up to join the waiting list!
          </p>
          <form name="prospectives" class="w-full md:mt-16 p-4" netlify>
            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
                <label
                  class="block uppercase tracking-wide text-white text-xs font-bold mb-2"
                  for="grid-first-name"
                >
                  First Name
                </label>
                <input
                  name="firstname"
                  class="font-inter appearance-none block w-full text-black py-3 px-4 mb-3 leading-tight focus:bg-white"
                  id="grid-first-name"
                  type="text"
                  placeholder="Jane"
                  required
                />
              </div>
              <div class="w-full md:w-1/2 px-3">
                <label
                  class="block uppercase tracking-wide text-white text-xs font-bold mb-2"
                  for="grid-last-name"
                >
                  Last Name
                </label>
                <input
                  name="lastname"
                  class="font-inter appearance-none block w-full text-black py-3 px-4 leading-tight"
                  id="grid-last-name"
                  type="text"
                  placeholder="Doe"
                  required
                />
              </div>
            </div>
            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full px-3">
                <label
                  class="block uppercase tracking-wide text-white text-xs font-bold mb-2"
                  for="grid-email-address"
                >
                  Email Address
                </label>
                <input
                  name="email"
                  class="font-inter appearance-none block w-full text-black py-3 px-4 mb-3 leading-tight"
                  id="grid-email-address"
                  type="email"
                  placeholder="jane.doe@example.com"
                  required
                />
              </div>
            </div>
            <div class="flex flex-wrap -mx-3 mb-2">
              <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
                <label
                  class="block uppercase tracking-wide text-white text-xs font-bold mb-2"
                  for="grid-city"
                >
                  City
                </label>
                <input
                  name="city"
                  class="font-inter appearance-none block w-full text-black py-3 px-4 leading-tight"
                  id="grid-city"
                  type="text"
                  placeholder="London"
                  required
                />
              </div>
              <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
                <label
                  class="block uppercase tracking-wide text-white text-xs font-bold mb-2"
                  for="grid-country"
                >
                  Country
                </label>
                <input
                  name="country"
                  class="font-inter appearance-none block w-full text-black py-3 px-4 leading-tight"
                  id="grid-city"
                  type="text"
                  placeholder="United Kingdom"
                  required
                />
              </div>
            </div>
            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full px-3"></div>
            </div>
            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full px-3">
                <label
                  class="block uppercase tracking-wide text-white text-xs font-bold mb-2"
                  for="grid-group-type"
                >
                  Group Type
                </label>
                <div class="relative">
                  <select
                    name="grouptype"
                    class="block appearance-none w-full text-gray-700 py-3 px-4 pr-8 leading-tight"
                    id="grid-group-type"
                  >
                    <option value="syndicate">Syndicate</option>
                    <option value="angel">Angel Investing Club</option>
                    <option value="fundcollective">Fund Collective</option>
                    <option value="undecided">Undecided</option>
                  </select>
                  <div
                    class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700"
                  >
                    <svg
                      class="fill-current h-4 w-4"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                      />
                    </svg>
                  </div>
                </div>
              </div>
            </div>
            <div class="flex flex-wrap -mx-3 justify-center mt-2">
              <button
                class="font-inter bg-black border text-white font-bold py-2 px-4 focus:outline-none"
                type="submit"
              >
                Submit to join the waiting list!
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
