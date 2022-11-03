<template>
    <div class="flex flex-col bg-gray-50 justify-center h-full p-6">
        <h1 class="text-5xl text-center mb-2">Welcome Back!</h1>
        <span class="text-sm text-center text-gray-600 mb-2">The faster you fill up, the faster you get a ticket</span>
        <label for="email" class="text-gray-700 text-left">Email</label>
        <input type="text" placeholder="Enter your email" class="inputs">
        <label for="password">Password</label>
        <input type="text" placeholder="********" class="inputs">

        <div class="flex flex-row justify-between items-center mt-2 mb-3 text-sm text-gray-700">
            <div class="inline-flex items-center ">
                <input type="checkbox" name="remember-me" class="mr-2">
                <span>remember me</span>
            </div>
            <span class="hover:text-blue-500 cursor-pointer">Forgot password</span>
        </div>
        <div class="font-semibold">
            <button class="bg-blue-500 w-full p-2 mb-3 rounded-md text-gray-50 hover:shadow-lg hover:bg-blue-700 transition-all ">Sign in</button>
            <button class="flex flex-row bg-transparent p-2 border-2 border-black border-opacity-4 rounded-md items-center justify-center w-full hover:bg-gray-800 hover:text-gray-200 hover:shadow-lg transition-all">
                <img src="../assets/google.svg" alt="google" class="p-1">
                Sign in with Google
            </button>
        </div>

        <div class="mt-10 flex justify-center items-center">
            <span class="text-gray-600 pr-1">Don't have an account?</span>
            <span class="font-bold">Sign up</span>
        </div>
    </div>
</template>
<style>
@import '../assets/main.css';

.inputs {
    @apply focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent rounded-md p-3 mb-2 border-2 focus:bg-transparent bg-gray-200 transition-all;
}
</style>