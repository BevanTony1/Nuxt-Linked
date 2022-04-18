<template>
    <nav class="flex p-5 justify-between w-full xl:px-52 md:px-5 sm:px-0 items-center bg-gray-900 fixed">
        <div class="text-gray-200">
            <div class="flex text-bold font-medium text-md items-center hover:text-blue-300 hover:cursor-pointer">
                <nuxt-link to='/'>
                    Linked
                </nuxt-link>
            </div>
        </div>
        
        <div>
            <nuxt-link to='/login'>
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-200 hover:text-blue-300 hover:cursor-pointer" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M3 3a1 1 0 011 1v12a1 1 0 11-2 0V4a1 1 0 011-1zm7.707 3.293a1 1 0 010 1.414L9.414 9H17a1 1 0 110 2H9.414l1.293 1.293a1 1 0 01-1.414 1.414l-3-3a1 1 0 010-1.414l3-3a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
            </nuxt-link>
        </div>
    </nav>
</template>

<script>
    export default {
        name:"Navbar"
}
</script>
