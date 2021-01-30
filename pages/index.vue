<template>
  <div class="flex h-screen">
    <div class="mt-38 sm:mt-38 m-auto ">
      <div class="px-12 flex flex-col">
        <div class="flex-shrink-0 flex justify-center">
          <img class="w-72" src="~/assets/img/rovex.png" alt="avatar" />
        </div>
        <div class="flex-shrink-0 flex justify-center">
          <p class="text-xs text-center">Private conversation, find your partner now.</p>
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
            <button class="float-right text-sm text-yellow-300 bg-gray-900 pl-5 pr-5 py-2 rounded shadow-inner focus:outline-none hover:bg-yellow-300 hover:text-gray-900">Login</button>
          </div>
        </div>
        <div class="text-center">
          <div>
            <nuxt-link to="/create-account" @click.prevent class="inline-block text-xs">Create Account</nuxt-link> |
            <nuxt-link to="/forgot-password" @click.prevent class="inline-block text-xs">Forgot Password</nuxt-link>
          </div>
        </div>
        <div class="mt-12 text-center">
          <div>
            <p class="text-gray-500 text-xs">© {{ new Date().getFullYear() }} Rovexchat, All rights reserved.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
