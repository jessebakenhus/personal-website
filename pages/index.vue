<template>
    <head>
      <title>Jesse Bakenhus</title>
    </head>
    <div class="min-h-screen bg-stone-950">
      <div class="container max-w-3xl mx-auto px-1">  
        <div class="flex flex-col justify-center">
            <header class="flex justify-center py-9">
                <NuxtImg class="size-28 rounded-full" src="avatar.jpg" />
            </header>
            <h1 class="text-center text-5xl font-medium bg-clip-text text-transparent bg-gradient-to-b from-stone-200 to-stone-500 py-4">a third culture creative bridging the east to the west, building companies and documenting it all.</h1>
            <ul class="flex flex-col md:flex-row gap-2 justify-center items-center text-white py-4">
                <a class="flex flex-row items-center justify-center md:justify-start w-fit bg-stone-900 rounded-full font-light px-2 py-1" href="https://www.linkedin.com/in/jessebakenhus/">
                    <NuxtImg class="mr-1 size-5 bg-white bg-clip-text" src="linkedin.svg" />
                    @jessebakenhus
                </a>
                <a class="flex flex-row items-center justify-center md:justify-start w-fit bg-stone-900 rounded-full font-light px-2 py-1" href="https://github.com/jessebakenhus">
                    <NuxtImg class="mr-1 size-5" src="github.svg" />
                    @jessebakenhus
                </a>
                <a class="flex flex-row items-center justify-center md:justify-start w-fit bg-stone-900 rounded-full font-light px-2 py-1" href="https://www.instagram.com/jessebkh/">
                    <NuxtImg class="mr-1 size-5" src="instagram.svg" />
                    @jessebakenhus
                </a>   
            </ul>

            <ol class="flex flex-col gap-3 py-12">
                <li class="p-4 pr-8 text-sm sm:text-base bg-stone-900 border border-stone-700 rounded">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center gap-4">
                            <NuxtImg class="sm:size-16 size-8" src="projects.svg" />                     
                            <div class="max-w-32 sm:max-w-full">
                                <h2 class="text-white">Projects</h2>
                                <p class="text-stone-500 font-light">Projects I have worked on or am working on</p>
                            </div>
                        </div>
                        <div>
                            <NuxtLink class="text-white border border-stone-700 px-6 py-3 rounded" to="/projects">Learn more</NuxtLink>
                        </div>
                    </div>
                </li>
                <li class="p-4 pr-8 text-sm sm:text-base bg-stone-900 border border-stone-700 rounded">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center gap-4" style="flex-shrink: 2;">
                            <NuxtImg class="sm:size-16 size-8" src="spotify.png" />                     
                            <div class="max-w-32 sm:max-w-full">
                                <h2 class="text-white">My Playlist</h2>
                                <p class="text-stone-500 font-light">All my songs I listen to when I'm at the gym or work.</p>
                            </div>
                        </div>
                        <div>
                            <NuxtLink 
                                class="text-white border border-stone-700 px-6 py-3 rounded min-w-32" 
                                to="https://open.spotify.com/playlist/3j4LovT1K6lo5ze6YFE4nZ?si=4010404ecb9f45cf">Learn more</NuxtLink>
                        </div>
                    </div>
                </li>
            </ol>

            <div class="flex pt-4 pb-16 justify-center">
                <p class="text-stone-500">© 2024 Jesse Bakenhus</p>
            </div>
        </div>
      </div>
    </div>
</template>