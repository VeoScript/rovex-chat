<template>
  <div class="flex h-screen">
    <div class="mt-20 sm:mt-12 m-auto ">
      <div class="px-12 flex flex-col">
        <div class="flex-shrink-0 flex justify-center">
          <img class="w-72" src="~/assets/img/rovex.png" alt="avatar" />
        </div>
        <div class="flex-shrink-0 flex justify-center">
          <p class="text-xs text-center">Private conversation, find your partner now.</p>
        </div>
        <div class="mt-10">
          <p class="text-lg text-left">Create Account</p>
        </div>
        <!-- create account form -->
        <div class="flex justify-center mt-5">
          <div class="grid grid-cols-2 gap-2">
            <div>
              <div class="space-y-2">
                <label class="text-xs text-gray-600">First Name</label>
                <input type="text" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
              </div>
            </div>
            <div>
              <div class="space-y-2">
                <label class="text-xs text-gray-600">Last Name</label>
                <input type="text" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
              </div>
            </div>
            <div class="col-span-2">
              <div class="space-y-2">
                <label class="text-xs text-gray-600">Email</label>
                <input type="text" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
              </div>
            </div>
            <div class="col-span-2">
              <div class="space-y-2">
                <label class="text-xs text-gray-600">Create Password</label>
                <input type="password" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
              </div>
            </div>
            <div class="col-span-2">
              <div class="space-y-2">
                <label class="text-xs text-gray-600">Re-enter Password</label>
                <input type="password" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
              </div>
            </div>
          </div>
        </div>
        <!-- create account form end -->
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
