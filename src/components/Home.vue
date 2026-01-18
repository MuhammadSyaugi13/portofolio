<script setup>
    // import image1 from '@/assets/images/image1.webp'

</script>

<template>
    <!-- <div class="min-h-screen bg-[#171717] text-slate-100">
        <div class="flex justify-center bg-red-300 w-full p-4">
            <img :src="image1" alt="image-1" class="w-[250px]">
        </div>
        <h3 class="font-bold text-xl">Halo nama saya Ogiii</h3>

    </div> -->

    <div class="min-h-screen bg-neutral-900 text-slate-100 font-mono">

        <div class="xl:flex w-full px-6 py-8 xl:py-16 xl:px-20">
            
            <aside class="xl:w-1/4 p-4">

                <img src="@/assets/images/profile-picture.webp" alt="image-1" width="100" height="100" class="rounded-lg">

                <h5 class="text-2xl mt-2 font-bold">Muhammad Saugi</h5>
                <p class="font-bold">Software Engineer</p>
                
                <hr class="border-r border-neutral-800 my-4">
                
                <button class="px-4 py-1 rounded-lg border border-slate-100 cursor-pointer hover:bg-neutral-600 transition">Curriculum Vitae</button>
                
                <hr class="border-r border-neutral-800 my-4">
                
                <p class="text-sm">
                    © 2026 Muhammad Saugi. Rights reserved.
                </p>

            </aside>

            <main class="xl:w-3/4 p-4">
                
                <div class="space-y-2">
                    <h4 class="font-bold text-3xl">Hello!</h4>
                    <h4 class="font-bold text-2xl">I'm Muhammad Saugi</h4>
                    
                    <div class="flex mt-4">
                        <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#e3e3e3"><path d="M480-480q33 0 56.5-23.5T560-560q0-33-23.5-56.5T480-640q-33 0-56.5 23.5T400-560q0 33 23.5 56.5T480-480Zm0 294q122-112 181-203.5T720-552q0-109-69.5-178.5T480-800q-101 0-170.5 69.5T240-552q0 71 59 162.5T480-186Zm0 106Q319-217 239.5-334.5T160-552q0-150 96.5-239T480-880q127 0 223.5 89T800-552q0 100-79.5 217.5T480-80Zm0-480Z"/></svg>
                        <span class="mx-2">Bogor, Indonesia</span>
                    </div>

                    <p class="text-xl text-justify">
                        I am a Software Engineer with over four years of professional experience. I am highly motivated to explore innovation and solve complex problems using my technical skills. I have a strong background in software development, with a particular interest in Web Development and Data Analytics. I aspire to contribute to technology-driven projects that enhance efficiency and deliver meaningful positive impact.
                    </p>

                    <hr class="border-r border-neutral-800 my-4">

                    <h4 class="font-bold text-2xl mt-6 mb-4">SKILLS</h4>

                    <div class="">

                        <div class="p-4 border border-slate-100 rounded-lg my-4">
                            <div class="text-xl mb-3">FRONTEND</div>
                            <div class="flex flex-wrap gap-2">
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="HTML" class="w-4 h-4" src="@/assets/images/skills/html.png"> -->
                                    <span>HTML</span>
                                </div>
                                
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>CSS</span>
                                </div>
        
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="JAVASCRIPT" class="w-4 h-4" src="@/assets/images/skills/javascript.png"> -->
                                    <span>JAVASCRIPT</span>
                                </div>
        
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="TAILWIND" class="w-4 h-4" src="@/assets/images/skills/tailwindcss.png"> -->
                                    <span>BOOTSTRAPT</span>
                                </div>
        
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="TAILWIND" class="w-4 h-4" src="@/assets/images/skills/tailwindcss.png"> -->
                                    <span>TAILWIND</span>
                                </div>
        
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="VUEJS" class="w-4 h-4" src="@/assets/images/skills/vuejs.png"> -->
                                    <span>VUEJS</span>
                                </div>
    
                                
                            </div>
                        </div>

                        <div class="p-4 border border-slate-100 rounded-lg my-4">
                            <div class="text-xl mb-3">BACKEND</div>
                            <div class="flex flex-wrap gap-2">
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="HTML" class="w-4 h-4" src="@/assets/images/skills/html.png"> -->
                                    <span>GOLANG</span>
                                </div>
                                
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>PHP</span>
                                </div>
        
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="JAVASCRIPT" class="w-4 h-4" src="@/assets/images/skills/javascript.png"> -->
                                    <span>NODEJS</span>
                                </div>
        
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="TAILWIND" class="w-4 h-4" src="@/assets/images/skills/tailwindcss.png"> -->
                                    <span>PYTHON</span>
                                </div>
                                
                            </div>
                        </div>

                        <div class="p-4 border border-slate-100 rounded-lg my-4">
                            <div class="text-xl mb-3">WEB FRAMEWORK</div>
                            <div class="flex flex-wrap gap-2">
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="HTML" class="w-4 h-4" src="@/assets/images/skills/html.png"> -->
                                    <span>LARAVEL</span>
                                </div>
                                
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>GIN</span>
                                </div>
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>GO ECHO</span>
                                </div>
        
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="JAVASCRIPT" class="w-4 h-4" src="@/assets/images/skills/javascript.png"> -->
                                    <span>EXPRESS JS</span>
                                </div>
                                
                            </div>
                        </div>

                        <div class="p-4 border border-slate-100 rounded-lg my-4">
                            <div class="text-xl mb-3">DATABASE</div>
                            <div class="flex flex-wrap gap-2">
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="HTML" class="w-4 h-4" src="@/assets/images/skills/html.png"> -->
                                    <span>SQL</span>
                                </div>
                                
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>MYSQL</span>
                                </div>
                                
                            </div>
                        </div>

                        <div class="p-4 border border-slate-100 rounded-lg my-4">
                            <div class="text-xl mb-3">MONITORING</div>
                            <div class="flex flex-wrap gap-2">
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="HTML" class="w-4 h-4" src="@/assets/images/skills/html.png"> -->
                                    <span>GRAFANA</span>
                                </div>
                                
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>PROMETEUS</span>
                                </div>
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>LOKI</span>
                                </div>
                                
                            </div>
                        </div>

                        <div class="p-4 border border-slate-100 rounded-lg my-4">
                            <div class="text-xl mb-3">DEPLOYMENT</div>
                            <div class="flex flex-wrap gap-2">
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="HTML" class="w-4 h-4" src="@/assets/images/skills/html.png"> -->
                                    <span>WINDOWS SERVER</span>
                                </div>
                                
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>UBUNTU/CENTOS</span>
                                </div>
    
                                <div class="text-center px-4 py-2 flex items-center justify-center gap-2 rounded-full  bg-gradient-to-b from-gray-100 to-gray-200 text-black dark:bg-none dark:bg-[#171717] dark:text-white dark:border dark:border-gray-400">
                                    <!-- <img alt="CSS" class="w-4 h-4" src="@/assets/images/skills/css.png"> -->
                                    <span>DOCKER</span>
                                </div>
                                
                            </div>
                        </div>

                        
                    </div>

                </div>

            </main>

        </div>

        <!-- Menu Float -->

        <div class="fixed bottom-5 left-0 w-full flex justify-center">
            <div class="w-7/8 md:w-4/5 xl:w-2/4 bg-neutral-600 border-2 border-neutral-300 rounded-lg p-2 flex justify-center space-x-2 overflow-scroll"> 

                <button class="
                bg-neutral-800 px-3 py-1 rounded transition
                active:bg-neutral-300 active:text-neutral-900 
                hover:bg-neutral-300 hover:text-neutral-900 
                ">
                    Home  
                </button>

                <button class="
                bg-neutral-800 px-3 py-1 rounded transition
                active:bg-neutral-300 active:text-neutral-900 
                hover:bg-neutral-300 hover:text-neutral-900 
                ">
                    Article
                </button>

                <button class="
                bg-neutral-800 px-3 py-1 rounded transition
                active:bg-neutral-300 active:text-neutral-900 
                hover:bg-neutral-300 hover:text-neutral-900 
                ">
                    Contact
                </button>

            </div>
        </div>
         
        <!-- ./ Menu Float -->

    </div>

</template>