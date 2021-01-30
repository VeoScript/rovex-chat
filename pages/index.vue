<template>
  <div class="flex h-screen">
    <div class="mt-40 sm:mt-12 m-auto ">
      <div class="px-12 flex flex-col">
        <div class="flex-shrink-0 flex justify-center">
          <img class="w-72" src="~/assets/img/rovex.png" alt="avatar" />
        </div>
        <div class="flex-shrink-0 flex justify-center">
          <p>Private Conversation</p>
        </div>
        <div class="py-4 mt-2 space-y-2">
          <div class="space-y-2">
            <div class="space-y-2">
              <label class="text-sm text-gray-600">Email</label>
              <input type="text" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
            </div>
          </div>
          <div class="space-y-2">
            <div class="space-y-2">
              <label class="text-sm text-gray-600">Password</label>
              <input type="password" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
            </div>
          </div>
          <div class="space-y-2">
            <button class="float-right text-sm bg-yellow-300 pl-5 pr-5 py-2 rounded shadow-inner focus:outline-none hover:bg-gray-900 hover:text-yellow-300">Login</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
