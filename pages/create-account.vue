<template>
  <div class="flex h-screen">
    <div class="m-auto p-10 sm:p-0 sm:pt-10 sm:pb-10">
      <div class="px-12 flex flex-col">
        <div class="flex-shrink-0 flex justify-center">
          <img class="w-72" src="~/assets/img/rovex.png" alt="avatar" />
        </div>
        <div class="flex-shrink-0 flex justify-center">
          <p class="text-xs text-center">Private conversation, find your partner now.</p>
        </div>
        <div class="mt-10 flex inline-block">
          <nuxt-link to="/">Login</nuxt-link>&nbsp;/&nbsp;<p>Create Account</p>
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
            <div class="col-span-2">
              <div class="space-y-2">
                <label class="text-xs text-gray-600">Gender</label>
                <select class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
                  <option value=""></option>
                  <option value="Male">Male</option>
                  <option value="Female">Female</option>
                  <option value="Bisexual">Bisexual</option>
                  <option value="Transgender">Transgender</option>
                </select>
              </div>
            </div>
            <div class="col-span-2">
              <div class="space-y-2">
                <label class="text-xs text-gray-600">Birthdate</label>
                <input type="date" class="text-sm w-full py-2 border border-gray-300 rounded shadow-inner focus:outline-none pl-4 focus:ring-2 focus:ring-yellow-300 transition ease-in-out duration-200 focus:border-gray-100">
              </div>
            </div>
            <div class="col-span-2">
              <div class="space-y-2">
                <button class="float-right w-full text-sm text-center text-yellow-300 bg-gray-900 pl-5 pr-5 py-2 rounded shadow-inner focus:outline-none hover:bg-gray-800">Create Account</button>
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
