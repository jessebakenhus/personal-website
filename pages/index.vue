<template>
    <head>
      <title>Jesse Bakenhus</title>
    </head>
    <div class="min-h-screen bg-stone-950">
      <div class="container mx-auto lg:px-96 md:px-28 sm:px-1">  
        <div class="flex flex-col justify-center">
            <header class="flex justify-center py-9">
                <NuxtImg class="size-28 rounded-full" src="avatar.jpg" />
            </header>
            <h1 class="text-center text-5xl font-medium bg-clip-text text-transparent bg-gradient-to-b from-stone-200 to-stone-500 py-4">a third culture creative bridging the east to the west, building companies and documenting it all.</h1>
            <ul class="flex flex-row gap-2 justify-center text-white py-4">
                <a class="flex flex-row items-center bg-stone-900 rounded-full font-light px-2 py-1" href="https://www.linkedin.com/in/jessebakenhus/">
                    <NuxtImg class="mr-1 size-5 bg-white bg-clip-text" src="linkedin.svg" />
                    @jessebakenhus
                </a>
                <a class="flex flex-row items-center bg-stone-900 rounded-full font-light px-2 py-1" href="https://github.com/jessebakenhus">
                    <NuxtImg class="mr-1 size-5" src="github.svg" />
                    @jessebakenhus
                </a>
                <a class="flex flex-row items-center bg-stone-900 rounded-full font-light px-2 py-1" href="https://www.instagram.com/jessebkh/">
                    <NuxtImg class="mr-1 size-5" src="instagram.svg" />
                    @jessebakenhus
                </a>   
            </ul>

            <ol class="py-12">
                <li class="p-4 pr-8 bg-stone-900 border border-stone-700 rounded">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center gap-4">
                            <NuxtImg class="size-16" src="projects.svg" />                     
                            <div>
                                <h2 class=" text-white">Projects</h2>
                                <p class="text-stone-500 font-light">Projects I have worked on or am working on</p>
                            </div>
                        </div>
                        <div>
                            <NuxtLink class="text-white border border-stone-700 px-6 py-3 rounded" to="/projects">Learn more</NuxtLink>
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