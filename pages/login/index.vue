<template>
  <div class="bg-gray-200 h-screen flex justify-center items-center">
    <div class="p-5 bg-white w-[500px] h-[600px] rounded-2xl shadow-md border-b-8 border-blue-500">
      <h1 class="text-center text-4xl mb-20 font-bold">Login</h1>
			<form class="space-y-4">
				<input class="w-full p-3 outline-none bg-gray-100 rounded-lg focus:border focus:border-blue-500" type="text" placeholder="Enter username">
				<input class="w-full p-3 outline-none bg-gray-100 rounded-lg focus:border focus:border-blue-500" type="password" placeholder="Enter password">
				<button class="w-full p-3 bg-blue-500 rounded-lg text-white" type="submit">Submit</button>
			</form>
		</div>
  </div>
</template>
