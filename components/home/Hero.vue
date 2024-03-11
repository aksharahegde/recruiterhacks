<template>
  <header>
    <!-- Hero Container -->
    <div class="mx-auto w-full max-w-7xl px-5 py-16 md:px-10 md:py-24 lg:py-32">
      <!-- Component -->
      <div
        class="grid items-center justify-items-start gap-8 sm:gap-20 lg:grid-cols-2"
      >
        <!-- Hero Content -->
        <div class="flex flex-col">
          <!-- Hero Divider -->
          <div class="mb-4 flex items-center">
            <p class="text-sm font-medium sm:text-base text-green-600">Recruiterment platform for freelance HRs</p>
          </div>
          <!-- Hero Title -->
          <h1 class="mb-4 text-4xl font-bold md:text-6xl">
            The Website You Want Without The Dev Time.
          </h1>
          <p
            class="mb-6 max-w-lg text-sm text-[#636262] sm:text-xl md:mb-10 lg:mb-12"
          >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit ut aliquam,
            purus sit amet luctus venenatis, lectus
          </p>
          <!-- Form -->
          <form
            name="email-form"
            method="get"
            class="relative mb-5 w-full max-w-xl pb-4 md:mb-6 lg:mb-4 lg:max-w-[80%]"
          >
            <input
              type="email"
              class="h-9 w-full rounded-md border border-solid border-black px-3 py-6 text-sm text-[#333333]"
              placeholder="Enter your email"
              required
            />
            <input
              type="submit"
              value="Subscribe"
              class="relative right-0 top-[5px] w-full cursor-pointer rounded-md bg-black px-6 py-2 text-center font-semibold text-white sm:absolute sm:right-[5px] sm:w-auto"
            />
          </form>
          <!-- Hero Info -->
          <div class="flex justify-between sm:justify-start sm:gap-8 lg:gap-12">
            <div class="flex items-center">
              <img
                src="https://assets.website-files.com/6458c625291a94a195e6cf3a/6458c625291a9481ece6cf9c_Vector%20(9).svg"
                alt=""
                class="mr-1 inline-block sm:mr-2"
              />
              <p class="text-sm">Customers</p>
            </div>
            <div class="flex items-center">
              <img
                src="https://assets.website-files.com/6458c625291a94a195e6cf3a/6458c625291a9481ece6cf9c_Vector%20(9).svg"
                alt=""
                class="mr-1 inline-block sm:mr-2"
              />
              <p class="text-sm">24/7 Support</p>
            </div>
            <div class="flex items-center">
              <img
                src="https://assets.website-files.com/6458c625291a94a195e6cf3a/6458c625291a9481ece6cf9c_Vector%20(9).svg"
                alt=""
                class="mr-1 inline-block sm:mr-2"
              />
              <p class="text-sm">Cloud-based</p>
            </div>
          </div>
        </div>
        <!-- Hero Image -->
        <img
          src="https://assets.website-files.com/6458c625291a94a195e6cf3a/6458c625291a940836e6cf8d_Group%2047854%20(2).svg"
          alt=""
          class="inline-block h-full w-full max-w-[640px]"
        />
      </div>
    </div>
  </header>
</template>
