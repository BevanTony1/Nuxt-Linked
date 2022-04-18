<template>
    <div class="flex flex-col bg-gray-50 justify-center min-h-screen">
        <div class="max-w-md w-full mx-auto">
            <div class="text-center mt-3 font-medium text-xl">
                Login Form
            </div>
            <div class="text-3xl font-bold text-gray-800 mt-2 text-center">
                Linked
            </div>
        </div>
        
        <div class="border w-full border-gray-300 max-w-md mx-auto mt-4 p-8">
            <form action="" class="space-y-6">
                <div>
                    <label for="email" class="text-sm font-bold text-gray-600 block">Email</label>
                    <input type="text" id='email' class="placeholder-slate-300 p-2 w-full border border-gray-300 rounded mt-1">
                </div>
                <div>
                    <label for="password" class="text-sm font-bold text-gray-600 block">Password</label>
                    <input type="password" id='password' class="p-2 w-full border border-gray-300 rounded mt-1">
                </div>

                <button class="w-full py-2 px-4 bg-blue-600 hover:bg-blue-700 rounded-md text-white text-sm">Login</button>
            </form>

        </div>
        <div class="text-center mt-4">
            <nuxt-link to='/signup'>
                <span class="hover:cursor-pointer font-bold hover:text-blue-500 transition-transform">Don't have an Account?</span>
            </nuxt-link>
        </div>
    </div>
</template>