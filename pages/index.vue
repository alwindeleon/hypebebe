<template>
  <div>
    <div class="relative bg-white overflow-hidden">
      <div class="max-w-7xl mx-auto">
        <div
          class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32"
        >
          <svg
            class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2"
            fill="currentColor"
            viewBox="0 0 100 100"
            preserveAspectRatio="none"
            aria-hidden="true"
          >
            <polygon points="50,0 100,0 50,100 0,100" />
          </svg>

          <div>
            <div class="relative pt-6 px-4 sm:px-6 lg:px-8">
              <nav
                class="relative flex items-center justify-between sm:h-10 lg:justify-start"
                aria-label="Global"
              >
                <div
                  class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0"
                >
                  <div
                    class="flex items-center justify-between w-full md:w-auto"
                  >
                    <a href="#">
                      <span class="sr-only">Workflow</span>
                      <img
                        class="h-8 w-auto sm:h-10"
                        src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg"
                      />
                    </a>
                    <div class="-mr-2 flex items-center md:hidden">
                      <button
                        type="button"
                        class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500"
                        aria-expanded="false"
                      >
                        <span class="sr-only">Open main menu</span>
                        <!-- Heroicon name: outline/menu -->
                        <svg
                          class="h-6 w-6"
                          xmlns="http://www.w3.org/2000/svg"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                          aria-hidden="true"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M4 6h16M4 12h16M4 18h16"
                          />
                        </svg>
                      </button>
                    </div>
                  </div>
                </div>
                <div class="hidden md:block md:ml-10 md:pr-4 md:space-x-8">
                  <a
                    href="#"
                    class="font-medium text-gray-500 hover:text-gray-900"
                    >Product</a
                  >

                  <a
                    href="#"
                    class="font-medium text-gray-500 hover:text-gray-900"
                    >Features</a
                  >

                  <a
                    href="#"
                    class="font-medium text-gray-500 hover:text-gray-900"
                    >Marketplace</a
                  >

                  <a
                    href="#"
                    class="font-medium text-gray-500 hover:text-gray-900"
                    >Company</a
                  >

                  <a
                    href="#"
                    class="font-medium text-indigo-600 hover:text-indigo-500"
                    >Log in</a
                  >
                </div>
              </nav>
            </div>

            <!--
          Mobile menu, show/hide based on menu open state.

          Entering: "duration-150 ease-out"
            From: "opacity-0 scale-95"
            To: "opacity-100 scale-100"
          Leaving: "duration-100 ease-in"
            From: "opacity-100 scale-100"
            To: "opacity-0 scale-95"
        -->
            <div
              class="absolute top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden"
            >
              <div
                class="rounded-lg shadow-md bg-white ring-1 ring-black ring-opacity-5 overflow-hidden"
              >
                <div class="px-5 pt-4 flex items-center justify-between">
                  <div>
                    <img
                      class="h-8 w-auto"
                      src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg"
                      alt=""
                    />
                  </div>
                  <div class="-mr-2">
                    <button
                      type="button"
                      class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500"
                    >
                      <span class="sr-only">Close main menu</span>
                      <!-- Heroicon name: outline/x -->
                      <svg
                        class="h-6 w-6"
                        xmlns="http://www.w3.org/2000/svg"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        aria-hidden="true"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M6 18L18 6M6 6l12 12"
                        />
                      </svg>
                    </button>
                  </div>
                </div>
                <div class="px-2 pt-2 pb-3 space-y-1">
                  <a
                    href="#"
                    class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50"
                    >Product</a
                  >

                  <a
                    href="#"
                    class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50"
                    >Features</a
                  >

                  <a
                    href="#"
                    class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50"
                    >Marketplace</a
                  >

                  <a
                    href="#"
                    class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50"
                    >Company</a
                  >
                </div>
                <a
                  href="#"
                  class="block w-full px-5 py-3 text-center font-medium text-indigo-600 bg-gray-50 hover:bg-gray-100"
                >
                  Log in
                </a>
              </div>
            </div>
          </div>

          <main
            class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28"
          >
            <div class="sm:text-center lg:text-left">
              <h1
                class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl"
              >
                <span class="block xl:inline">HypeBebe Online</span>
                <span class="block text-indigo-600 xl:inline"
                  >sustainable baby clothes subscription</span
                >
              </h1>
              <p
                class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0"
              >
                Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui
                lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat
                fugiat aliqua.
              </p>
              <div
                class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start"
              >
                <div class="rounded-md shadow">
                  <a
                    href="#"
                    class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 md:py-4 md:text-lg md:px-10"
                  >
                    Get started
                  </a>
                </div>
                <div class="mt-3 sm:mt-0 sm:ml-3">
                  <a
                    href="#"
                    class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-indigo-700 bg-indigo-100 hover:bg-indigo-200 md:py-4 md:text-lg md:px-10"
                  >
                    Live demo
                  </a>
                </div>
              </div>
            </div>
          </main>
        </div>
      </div>
      <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
        <img
          class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full"
          src="https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=100&q=60%20100w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=200&q=60%20200w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=300&q=60%20300w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=60%20400w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60%20500w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=60%20600w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=60%20700w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60%20800w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=900&q=60%20900w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=60%201000w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1100&q=60%201100w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1200&q=60%201200w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1296&q=60%201296w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1400&q=60%201400w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1600&q=60%201600w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1800&q=60%201800w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2000&q=60%202000w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2200&q=60%202200w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2400&q=60%202400w,%20https://images.unsplash.com/photo-1522771930-78848d9293e8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8YmFieXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2448&q=60%202448w"
          alt=""
        />
      </div>
    </div>
    <div class="py-12 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="lg:text-center">
          <h2
            class="text-base text-indigo-600 font-semibold tracking-wide uppercase"
          >
            Transactions
          </h2>
          <p
            class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl"
          >
            A better way to send money
          </p>
          <p class="mt-4 max-w-2xl text-xl text-gray-500 lg:mx-auto">
            Lorem ipsum dolor sit amet consect adipisicing elit. Possimus magnam
            voluptatum cupiditate veritatis in accusamus quisquam.
          </p>
        </div>

        <div class="mt-10">
          <dl
            class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10"
          >
            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/globe-alt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                    />
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  Competitive exchange rates
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Maiores impedit perferendis suscipit eaque, iste dolor
                cupiditate blanditiis ratione.
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/scale -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3"
                    />
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  No hidden fees
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Maiores impedit perferendis suscipit eaque, iste dolor
                cupiditate blanditiis ratione.
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/lightning-bolt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13 10V3L4 14h7v7l9-11h-7z"
                    />
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  Transfers are instant
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Maiores impedit perferendis suscipit eaque, iste dolor
                cupiditate blanditiis ratione.
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/annotation -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"
                    />
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  Mobile notifications
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Maiores impedit perferendis suscipit eaque, iste dolor
                cupiditate blanditiis ratione.
              </dd>
            </div>
          </dl>
        </div>
      </div>
    </div>
    <section>
      <div class="container flex flex-col max-w-full mx-auto py-24 px-6">
        <h1
          class="text-center text-4xl text-black font-medium leading-snug tracking-wider"
        >
          Pricing
        </h1>
        <p class="text-center text-lg text-gray-700 mt-2 px-6">
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam.
        </p>
        <div
          class="h-1 mx-auto bg-indigo-200 w-24 opacity-75 mt-4 rounded"
        ></div>

        <div class="max-w-full md:max-w-6xl mx-auto my-3 md:px-8">
          <div class="relative block flex flex-col md:flex-row items-center">
            <div
              class="w-11/12 max-w-sm sm:w-3/5 lg:w-1/3 sm:my-5 my-8 relative z-0 rounded-lg shadow-lg md:-mr-4"
            >
              <div
                class="bg-white text-black rounded-lg shadow-inner shadow-lg overflow-hidden"
              >
                <div
                  class="block text-left text-sm sm:text-md max-w-sm mx-auto mt-2 text-black px-8 lg:px-6"
                >
                  <h1
                    class="text-lg font-medium uppercase p-3 pb-0 text-center tracking-wide"
                  >
                    Hobby
                  </h1>
                  <h2 class="text-sm text-gray-500 text-center pb-6">FREE</h2>

                  Stripe offers everything needed to run an online business at
                  scale. Get in touch for details.
                </div>

                <div class="flex flex-wrap mt-3 px-6">
                  <ul>
                    <li class="flex items-center">
                      <div class="rounded-full p-2 fill-current text-green-700">
                        <svg
                          class="w-6 h-6 align-middle"
                          width="24"
                          height="24"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                          <polyline points="22 4 12 14.01 9 11.01"></polyline>
                        </svg>
                      </div>
                      <span class="text-gray-700 text-lg ml-3">No setup</span>
                    </li>
                    <li class="flex items-center">
                      <div class="rounded-full p-2 fill-current text-green-700">
                        <svg
                          class="w-6 h-6 align-middle"
                          width="24"
                          height="24"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                          <polyline points="22 4 12 14.01 9 11.01"></polyline>
                        </svg>
                      </div>
                      <span class="text-gray-700 text-lg ml-3">No setups</span>
                    </li>
                    <li class="flex items-center">
                      <div class="rounded-full p-2 fill-current text-green-700">
                        <svg
                          class="w-6 h-6 align-middle"
                          width="24"
                          height="24"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                          <polyline points="22 4 12 14.01 9 11.01"></polyline>
                        </svg>
                      </div>
                      <span class="text-gray-700 text-lg ml-3">Speed</span>
                    </li>
                  </ul>
                </div>
                <div class="block flex items-center p-8 uppercase">
                  <button
                    class="mt-3 text-lg font-semibold bg-black w-full text-white rounded-lg px-6 py-3 block shadow-xl hover:bg-gray-700"
                  >
                    Select
                  </button>
                </div>
              </div>
            </div>
            <div
              class="w-full max-w-md sm:w-2/3 lg:w-1/3 sm:my-5 my-8 relative z-10 bg-white rounded-lg shadow-lg"
            >
              <div
                class="text-sm leading-none rounded-t-lg bg-gray-200 text-black font-semibold uppercase py-4 text-center tracking-wide"
              >
                Most Popular
              </div>
              <div
                class="block text-left text-sm sm:text-md max-w-sm mx-auto mt-2 text-black px-8 lg:px-6"
              >
                <h1
                  class="text-lg font-medium uppercase p-3 pb-0 text-center tracking-wide"
                >
                  Expert
                </h1>
                <h2 class="text-sm text-gray-500 text-center pb-6">
                  <span class="text-3xl">€19</span> /mo
                </h2>

                Stripe offers everything needed to run an online business at
                scale. Get in touch for details.
              </div>
              <div class="flex pl-12 justify-start sm:justify-start mt-3">
                <ul>
                  <li class="flex items-center">
                    <div class="rounded-full p-2 fill-current text-green-700">
                      <svg
                        class="w-6 h-6 align-middle"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      >
                        <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                        <polyline points="22 4 12 14.01 9 11.01"></polyline>
                      </svg>
                    </div>
                    <span class="text-gray-700 text-lg ml-3">No setup</span>
                  </li>
                  <li class="flex items-center">
                    <div class="rounded-full p-2 fill-current text-green-700">
                      <svg
                        class="w-6 h-6 align-middle"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      >
                        <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                        <polyline points="22 4 12 14.01 9 11.01"></polyline>
                      </svg>
                    </div>
                    <span class="text-gray-700 text-lg ml-3">Hidden fees</span>
                  </li>
                  <li class="flex items-center">
                    <div class="rounded-full p-2 fill-current text-green-700">
                      <svg
                        class="w-6 h-6 align-middle"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      >
                        <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                        <polyline points="22 4 12 14.01 9 11.01"></polyline>
                      </svg>
                    </div>
                    <span class="text-gray-700 text-lg ml-3">Original</span>
                  </li>
                </ul>
              </div>

              <div class="block flex items-center p-8 uppercase">
                <button
                  class="mt-3 text-lg font-semibold bg-black w-full text-white rounded-lg px-6 py-3 block shadow-xl hover:bg-gray-700"
                >
                  Select
                </button>
              </div>
            </div>
            <div
              class="w-11/12 max-w-sm sm:w-3/5 lg:w-1/3 sm:my-5 my-8 relative z-0 rounded-lg shadow-lg md:-ml-4"
            >
              <div
                class="bg-white text-black rounded-lg shadow-inner shadow-lg overflow-hidden"
              >
                <div
                  class="block text-left text-sm sm:text-md max-w-sm mx-auto mt-2 text-black px-8 lg:px-6"
                >
                  <h1
                    class="text-lg font-medium uppercase p-3 pb-0 text-center tracking-wide"
                  >
                    Enteprise
                  </h1>
                  <h2 class="text-sm text-gray-500 text-center pb-6">
                    €39 /mo
                  </h2>

                  Stripe offers everything needed to run an online business at
                  scale. Get in touch for details.
                </div>
                <div class="flex flex-wrap mt-3 px-6">
                  <ul>
                    <li class="flex items-center">
                      <div class="rounded-full p-2 fill-current text-green-700">
                        <svg
                          class="w-6 h-6 align-middle"
                          width="24"
                          height="24"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                          <polyline points="22 4 12 14.01 9 11.01"></polyline>
                        </svg>
                      </div>
                      <span class="text-gray-700 text-lg ml-3">Electric</span>
                    </li>
                    <li class="flex items-center">
                      <div class="rounded-full p-2 fill-current text-green-700">
                        <svg
                          class="w-6 h-6 align-middle"
                          width="24"
                          height="24"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                          <polyline points="22 4 12 14.01 9 11.01"></polyline>
                        </svg>
                      </div>
                      <span class="text-gray-700 text-lg ml-3">Monthly</span>
                    </li>
                    <li class="flex items-center">
                      <div class="rounded-full p-2 fill-current text-green-700">
                        <svg
                          class="w-6 h-6 align-middle"
                          width="24"
                          height="24"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                          <polyline points="22 4 12 14.01 9 11.01"></polyline>
                        </svg>
                      </div>
                      <span class="text-gray-700 text-lg ml-3">No setup</span>
                    </li>
                  </ul>
                </div>

                <div class="block flex items-center p-8 uppercase">
                  <button
                    class="mt-3 text-lg font-semibold bg-black w-full text-white rounded-lg px-6 py-3 block shadow-xl hover:bg-gray-700"
                  >
                    Select
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="flex flex-col justify-center m-auto">
      <div
        class="flex md:flex-row flex-col bg-teal-200 justify-center md:text-left text-center"
      >
        <div class="flex flex-col justify-center items-center relative">
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div class="h-full border-teal-300 border-dashed"></div>
          </div>
          <div
            class="rounded-full w-12 h-12 text-xl text-teal-100 bg-teal-700 font-black flex justify-center items-center absolute top-0 right-0 mt-16 shadow-lg mr-2"
          >
            1
          </div>
          <img
            alt="step1"
            class="w-56 h-56 rounded-full shadow my-5 object-scale-down"
            src="https://image.flaticon.com/icons/svg/1330/1330216.svg"
          />
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div class="h-full border-r-4 border-teal-300 border-dashed"></div>
          </div>
        </div>
        <div
          class="ml-5 p-10 flex flex-col justify-center max-w-2xl rounded bg-teal-200"
        >
          <div class="text-xs uppercase font-bold text-teal-500">
            Step 1 - Idea
          </div>
          <div class="md:text-3xl text-xl font-bold text-teal-700">
            Find your best idea
          </div>
          <div class="mt-4 text-teal-800">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam
            facilis, voluptates error alias dolorem praesentium sit soluta iure
            incidunt labore explicabo eaque, quia architecto veritatis dolores,
            enim consequatur nihil ipsum.
          </div>
        </div>
      </div>
      <div
        class="flex md:flex-row flex-col bg-orange-200 justify-center md:text-left text-center"
      >
        <div class="flex flex-col justify-center items-center relative">
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div
              class="h-full border-r-4 border-orange-300 border-dashed"
            ></div>
          </div>
          <div
            class="rounded-full w-12 h-12 text-xl text-orange-100 bg-orange-700 font-black flex justify-center items-center absolute top-0 right-0 mt-16 shadow-lg mr-2"
          >
            2
          </div>
          <img
            alt="step2"
            class="w-56 h-56 rounded-full shadow my-5 object-scale-down"
            src="https://image.flaticon.com/icons/svg/1330/1330216.svg"
          />
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div
              class="h-full border-r-4 border-orange-300 border-dashed"
            ></div>
          </div>
        </div>
        <div
          class="ml-5 p-10 flex flex-col justify-center max-w-2xl rounded bg-orange-200"
        >
          <div class="text-xs uppercase font-bold text-orange-500">
            Step 2 - Collaboration
          </div>
          <div class="md:text-3xl text-xl font-bold text-orange-700">
            Find your team and collaborate
          </div>
          <div class="mt-4 text-orange-800">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam
            facilis, voluptates error alias dolorem praesentium sit soluta iure
            incidunt labore explicabo eaque, quia architecto veritatis dolores,
            enim consequatur nihil ipsum.
          </div>
        </div>
      </div>
      <div
        class="flex md:flex-row flex-col bg-indigo-200 justify-center md:text-left text-center"
      >
        <div class="flex flex-col justify-center items-center relative">
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div
              class="h-full border-r-4 border-indigo-300 border-dashed"
            ></div>
          </div>
          <div
            class="rounded-full w-12 h-12 text-xl text-indigo-100 bg-indigo-700 font-black flex justify-center items-center absolute top-0 right-0 mt-16 shadow-lg mr-2"
          >
            3
          </div>
          <img
            alt="step3"
            class="w-56 h-56 rounded-full shadow my-5 object-scale-down"
            src="https://image.flaticon.com/icons/svg/1330/1330216.svg"
          />
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div
              class="h-full border-r-4 border-indigo-300 border-dashed"
            ></div>
          </div>
        </div>
        <div
          class="ml-5 p-10 flex flex-col justify-center max-w-2xl rounded bg-indigo-200"
        >
          <div class="text-xs uppercase font-bold text-indigo-500">
            Step 3 - Planification
          </div>
          <div class="md:text-3xl text-xl font-bold text-indigo-700">
            Make a good plan and prepare tasks
          </div>
          <div class="mt-4 text-indigo-800">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam
            facilis, voluptates error alias dolorem praesentium sit soluta iure
            incidunt labore explicabo eaque, quia architecto veritatis dolores,
            enim consequatur nihil ipsum.
          </div>
        </div>
      </div>
      <div
        class="flex md:flex-row flex-col bg-pink-200 justify-center md:text-left text-center"
      >
        <div class="flex flex-col justify-center items-center relative">
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div class="h-full border-r-4 border-pink-300 border-dashed"></div>
          </div>
          <div
            class="rounded-full w-12 h-12 text-xl text-pink-100 bg-pink-700 font-black flex justify-center items-center absolute top-0 right-0 mt-16 shadow-lg mr-2"
          >
            4
          </div>
          <img
            alt="step4"
            class="w-56 h-56 rounded-full shadow my-5 object-scale-down"
            src="https://image.flaticon.com/icons/svg/1330/1330216.svg"
          />
          <div class="w-56 h-12 md:flex hidden justify-center">
            <div class="h-full border-pink-300 border-dashed"></div>
          </div>
        </div>
        <div
          class="ml-5 p-10 flex flex-col justify-center max-w-2xl rounded bg-pink-200"
        >
          <div class="text-xs uppercase font-bold text-pink-500">
            Step 4 - Implementation
          </div>
          <div class="md:text-3xl text-xl font-bold text-pink-700">
            Execute, impletement your solution
          </div>
          <div class="mt-4 text-pink-800">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam
            facilis, voluptates error alias dolorem praesentium sit soluta iure
            incidunt labore explicabo eaque, quia architecto veritatis dolores,
            enim consequatur nihil ipsum.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
