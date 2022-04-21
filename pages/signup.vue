<template>
    <div class="flex flex-col min-h-screen justify-center bg-slate-50">
        <div class="max-w-md w-full mx-auto">
            <div class="text-center mt-3 font-medium text-xl">
                Signup Form
            </div>
            <div class="text-3xl font-bold text-gray-800 mt-2 text-center">
                Linked
            </div>
        </div>

        <div class="border w-full border-gray-400 max-w-md bg-white mx-auto mt-4 p-8">
            <form action="" class="space-y-6">
                <div>
                    <label for="email" class="text-sm font-bold text-gray-600 block">Email</label>
                    <input type="text" id="email" class=" p-2 w-full border border-gray-300 rounded mt-1">
                </div>
                <div class="">
                    <label for="firstName" class="text-sm font-bold text-gray-600 block">First Name</label>
                    <input type="text" id="firstName" class="p-2 w-full border border-gray-300 rounded mt-1">
                </div>
                <div class="">
                    <label for="middleName" class="text-sm font-bold text-gray-600 block">Middle Name</label>
                    <input type="text" id="middleName" class="border border-gray-300 p-2 w-full mt-1 rounded">
                </div>
                <div class="">
                    <label for="lastName" class="font-bold text-sm text-gray-600 block">Last Name</label>
                    <input type="text" id="lastName" class="border border-gray-300 text-sm p-2 w-full mt-1 rounded">
                </div>
                
                <button class="w-full py-2 px-4 bg-blue-600 hover:bg-blue-700 transition-transform text-white text-sm rounded-md">Signup!</button>
            </form>
        </div>
          
            <div class="text-center mt-4">
                <nuxt-link to='/login'>
                    <span class="hover:cursor-pointer font-bold hover:text-blue-500 transition-transform">
                        Already have an account?
                    </span>
                </nuxt-link>
            </div>

    </div>
</template>