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
        <div class="mt-10 flex">
          <nuxt-link to="/">Login</nuxt-link>&nbsp;/&nbsp;<p class="font-medium">Forgot Password</p>
        </div>
        <div class="py-4 mt-2 space-y-2">
          <div>
            <p class="text-xs">
              We will send you instructions on how to reset your password by email.
            </p>
          </div>
          <div class="space-y-2">
            <div class="space-y-2">
              <label class="text-sm text-gray-600">Enter you email</label>
              <input type="text" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
            </div>
          </div>
          <div class="space-y-2">
            <button class="float-right w-full text-sm text-yellow-300 bg-gray-900 pl-5 pr-5 py-2 rounded shadow-inner focus:outline-none hover:bg-yellow-300 hover:text-gray-900">Submit</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
