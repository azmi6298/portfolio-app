<template>
    <div class="text-lg bg-gray-900 text-gray-100">
        <full-page ref="fullpage" :options="options" id="fullpage">
            <div class="section">
                <div class="container px-16 lg:px-0 mx-auto mt-10 flex flex-row justify-between">
                    <div class="text-7xl mt-10">
                        <p class="hello1 text-gray-100 pointer-events-none">Hello</p>
                        <p class="hello2 text-gray-100 pointer-events-none text-opacity-75">Hello</p>
                        <p class="hello3 text-gray-100 pointer-events-none text-opacity-50">Hello</p>
                        <p class="hello4 text-gray-100 pointer-events-none text-opacity-25">Hello</p>
                        <p class="hello5 text-gray-500 pointer-events-none text-opacity-25">Hello</p>
                        <div class="social mt-10 flex flex-row space-x-8">
                            <a href="#" target="_blank">
                                <svg viewBox="0 0 512 512" class="h-16 w-16 fill-current text-gray-100"><path d="m305 256c0 27.0625-21.9375 49-49 49s-49-21.9375-49-49 21.9375-49 49-49 49 21.9375 49 49zm0 0"/><path d="m370.59375 169.304688c-2.355469-6.382813-6.113281-12.160157-10.996094-16.902344-4.742187-4.882813-10.515625-8.640625-16.902344-10.996094-5.179687-2.011719-12.960937-4.40625-27.292968-5.058594-15.503906-.707031-20.152344-.859375-59.402344-.859375-39.253906 0-43.902344.148438-59.402344.855469-14.332031.65625-22.117187 3.050781-27.292968 5.0625-6.386719 2.355469-12.164063 6.113281-16.902344 10.996094-4.882813 4.742187-8.640625 10.515625-11 16.902344-2.011719 5.179687-4.40625 12.964843-5.058594 27.296874-.707031 15.5-.859375 20.148438-.859375 59.402344 0 39.25.152344 43.898438.859375 59.402344.652344 14.332031 3.046875 22.113281 5.058594 27.292969 2.359375 6.386719 6.113281 12.160156 10.996094 16.902343 4.742187 4.882813 10.515624 8.640626 16.902343 10.996094 5.179688 2.015625 12.964844 4.410156 27.296875 5.0625 15.5.707032 20.144532.855469 59.398438.855469 39.257812 0 43.90625-.148437 59.402344-.855469 14.332031-.652344 22.117187-3.046875 27.296874-5.0625 12.820313-4.945312 22.953126-15.078125 27.898438-27.898437 2.011719-5.179688 4.40625-12.960938 5.0625-27.292969.707031-15.503906.855469-20.152344.855469-59.402344 0-39.253906-.148438-43.902344-.855469-59.402344-.652344-14.332031-3.046875-22.117187-5.0625-27.296874zm-114.59375 162.179687c-41.691406 0-75.488281-33.792969-75.488281-75.484375s33.796875-75.484375 75.488281-75.484375c41.6875 0 75.484375 33.792969 75.484375 75.484375s-33.796875 75.484375-75.484375 75.484375zm78.46875-136.3125c-9.742188 0-17.640625-7.898437-17.640625-17.640625s7.898437-17.640625 17.640625-17.640625 17.640625 7.898437 17.640625 17.640625c-.003906 9.742188-7.898437 17.640625-17.640625 17.640625zm0 0"/><path d="m256 0c-141.363281 0-256 114.636719-256 256s114.636719 256 256 256 256-114.636719 256-256-114.636719-256-256-256zm146.113281 316.605469c-.710937 15.648437-3.199219 26.332031-6.832031 35.683593-7.636719 19.746094-23.246094 35.355469-42.992188 42.992188-9.347656 3.632812-20.035156 6.117188-35.679687 6.832031-15.675781.714844-20.683594.886719-60.605469.886719-39.925781 0-44.929687-.171875-60.609375-.886719-15.644531-.714843-26.332031-3.199219-35.679687-6.832031-9.8125-3.691406-18.695313-9.476562-26.039063-16.957031-7.476562-7.339844-13.261719-16.226563-16.953125-26.035157-3.632812-9.347656-6.121094-20.035156-6.832031-35.679687-.722656-15.679687-.890625-20.6875-.890625-60.609375s.167969-44.929688.886719-60.605469c.710937-15.648437 3.195312-26.332031 6.828125-35.683593 3.691406-9.808594 9.480468-18.695313 16.960937-26.035157 7.339844-7.480469 16.226563-13.265625 26.035157-16.957031 9.351562-3.632812 20.035156-6.117188 35.683593-6.832031 15.675781-.714844 20.683594-.886719 60.605469-.886719s44.929688.171875 60.605469.890625c15.648437.710937 26.332031 3.195313 35.683593 6.824219 9.808594 3.691406 18.695313 9.480468 26.039063 16.960937 7.476563 7.34375 13.265625 16.226563 16.953125 26.035157 3.636719 9.351562 6.121094 20.035156 6.835938 35.683593.714843 15.675781.882812 20.683594.882812 60.605469s-.167969 44.929688-.886719 60.605469zm0 0"/></svg>
                            </a>
                            <a href="#" target="_blank">
                                <svg viewBox="0 0 512 512" class="h-16 w-16 fill-current text-gray-100"><path d="m256 0c-141.363281 0-256 114.636719-256 256s114.636719 256 256 256 256-114.636719 256-256-114.636719-256-256-256zm-74.390625 387h-62.347656v-187.574219h62.347656zm-31.171875-213.1875h-.40625c-20.921875 0-34.453125-14.402344-34.453125-32.402344 0-18.40625 13.945313-32.410156 35.273437-32.410156 21.328126 0 34.453126 14.003906 34.859376 32.410156 0 18-13.53125 32.402344-35.273438 32.402344zm255.984375 213.1875h-62.339844v-100.347656c0-25.21875-9.027343-42.417969-31.585937-42.417969-17.222656 0-27.480469 11.601563-31.988282 22.800781-1.648437 4.007813-2.050781 9.609375-2.050781 15.214844v104.75h-62.34375s.816407-169.976562 0-187.574219h62.34375v26.558594c8.285157-12.78125 23.109375-30.960937 56.1875-30.960937 41.019531 0 71.777344 26.808593 71.777344 84.421874zm0 0"/></svg>
                            </a>
                            <a href="#" target="_blank">
                                <svg viewBox="0 0 512 512" class="h-16 w-16 fill-current text-gray-100"><path d="m224.113281 303.960938 83.273438-47.960938-83.273438-47.960938zm0 0"/><path d="m256 0c-141.363281 0-256 114.636719-256 256s114.636719 256 256 256 256-114.636719 256-256-114.636719-256-256-256zm159.960938 256.261719s0 51.917969-6.585938 76.953125c-3.691406 13.703125-14.496094 24.507812-28.199219 28.195312-25.035156 6.589844-125.175781 6.589844-125.175781 6.589844s-99.878906 0-125.175781-6.851562c-13.703125-3.6875-24.507813-14.496094-28.199219-28.199219-6.589844-24.769531-6.589844-76.949219-6.589844-76.949219s0-51.914062 6.589844-76.949219c3.6875-13.703125 14.757812-24.773437 28.199219-28.460937 25.035156-6.589844 125.175781-6.589844 125.175781-6.589844s100.140625 0 125.175781 6.851562c13.703125 3.6875 24.507813 14.496094 28.199219 28.199219 6.851562 25.035157 6.585938 77.210938 6.585938 77.210938zm0 0"/></svg>
                            </a>
                            <a href="#" target="_blank">
                                <svg viewBox="0 0 24 24" class="h-16 w-16 fill-current text-gray-100"><path d="m12 .5c-6.63 0-12 5.28-12 11.792 0 5.211 3.438 9.63 8.205 11.188.6.111.82-.254.82-.567 0-.28-.01-1.022-.015-2.005-3.338.711-4.042-1.582-4.042-1.582-.546-1.361-1.335-1.725-1.335-1.725-1.087-.731.084-.716.084-.716 1.205.082 1.838 1.215 1.838 1.215 1.07 1.803 2.809 1.282 3.495.981.108-.763.417-1.282.76-1.577-2.665-.295-5.466-1.309-5.466-5.827 0-1.287.465-2.339 1.235-3.164-.135-.298-.54-1.497.105-3.121 0 0 1.005-.316 3.3 1.209.96-.262 1.98-.392 3-.398 1.02.006 2.04.136 3 .398 2.28-1.525 3.285-1.209 3.285-1.209.645 1.624.24 2.823.12 3.121.765.825 1.23 1.877 1.23 3.164 0 4.53-2.805 5.527-5.475 5.817.42.354.81 1.077.81 2.182 0 1.578-.015 2.846-.015 3.229 0 .309.21.678.825.56 4.801-1.548 8.236-5.97 8.236-11.173 0-6.512-5.373-11.792-12-11.792z"/></svg>
                            </a>
                            <a href="#" target="_blank">
                                <svg viewBox="0 0 97.75 97.75" class="h-16 w-16 fill-current text-gray-100" ><path d="M46.927 38.775C42.032 30.117 36.8 22.816 35.746 21.367c-8.416 4.016-14.719 11.764-16.74 21.088h.299c2.816 0 14.484-.226 27.622-3.68zM69.01 25.984C63.628 21.266 56.582 18.4 48.875 18.4c-2.37 0-4.676.273-6.893.789 1.242 1.678 6.471 8.9 11.243 17.631 10.314-3.9 14.934-9.672 15.785-10.836zM57.713 45.988c.208.488.41.975.609 1.459a57.325 57.325 0 016.967-.404c6.951 0 12.768 1.088 14.141 1.365a30.348 30.348 0 00-6.753-18.607c-1.067 1.383-6.229 7.498-16.925 11.904a94.395 94.395 0 011.961 4.283zM50.969 49.018c.336-.108.676-.207 1.016-.307a101.527 101.527 0 00-2.336-4.879c-13.565 4.027-26.731 4.342-30.522 4.342-.35 0-.617-.002-.801-.006-.006.252-.013.504-.013.754.001 7.752 2.91 14.834 7.693 20.223 1.291-2.133 9.689-15.194 24.963-20.127z"/><path d="M48.875 0C21.882 0 0 21.883 0 48.875S21.882 97.75 48.875 97.75 97.75 75.867 97.75 48.875 75.868 0 48.875 0zm0 85.004c-19.948 0-36.176-16.207-36.177-36.129.002-19.922 16.229-36.127 36.177-36.129 19.948.002 36.175 16.207 36.176 36.129-.001 19.922-16.228 36.129-36.176 36.129z"/><path d="M60.327 52.631c3.801 10.484 5.448 19.082 5.856 21.432 6.692-4.608 11.461-11.811 12.84-20.141-1.16-.354-6.157-1.752-12.543-1.752-1.945 0-4.02.133-6.153.461zM54.184 54.143c-16.742 5.826-23.078 17.236-23.95 18.949a30.442 30.442 0 0018.642 6.352c4.183 0 8.172-.844 11.806-2.37-.49-2.843-2.269-12.013-6.464-22.943l-.034.012z"/></svg>
                            </a>
                        </div>
                    </div>
                    <div class="flex justify-end invisible lg:visible">
                        <img :src="'/img/acro.png'" class="logo self-center" alt="">
                    </div>
                </div>
                <div class="absolute space-y-8 bottom-0 right-0 mr-10 md:mr-32 mb-3">
                    <div class="rectangle" v-for="i in 3" :key="i"></div>
                </div>
            </div>
            <div class="section items-center">
                <div class="container mx-auto px-16 lg:px-0">
                    <h1 class="title text-5xl lg:text-7xl text-gray-100 text-opacity-25 hover:text-opacity-100">Write some code</h1>
                    <div class="hide">
                        <div class="flex flex-row space-x-6 items-center">
                            <img :src="'/img/ruby.png'" class="mt-4 mb-4 h-12 w-12" alt="">
                            <img :src="'/img/rails.png'" class="mt-4 mb-4 h-24 w-32" alt="">
                            <img :src="'/img/angular.png'" class="mt-4 mb-4 h-12 w-12" alt="">
                            <img :src="'/img/laravel.png'" class="mt-4 mb-4 h-12 w-12" alt="">
                        </div>
                    </div>
                    <h1 class="title text-5xl lg:text-7xl text-gray-100 text-opacity-25 hover:text-opacity-100">Producing music</h1>
                    <div class="hide">
                        <div class="flex flex-row space-x-6 items-center mt-10 mb-10">
                            <img :src="'/img/fl.png'" class="h-12 w-36" alt="">
                            <img :src="'/img/logic.jpg'" class="h-12 w-12" alt="">
                        </div>
                    </div>
                    <h1 class="title text-5xl lg:text-7xl text-gray-100 text-opacity-25 hover:text-opacity-100">Graphic designing</h1>
                    <div class="hide">
                        <div class="flex flex-row space-x-6 items-center mt-10 mb-10">
                            <img :src="'/img/designer.png'" class="h-12 w-16" alt="">
                            <img :src="'/img/photo.jpg'" class="h-12 w-16" alt="">
                        </div>
                    </div>
                    <p class="mt-10">Hover to see</p>
                </div>
                <div class="absolute space-y-8 top-0 right-0 mr-10 md:mr-32 mt-5">
                    <div class="rectangle" v-for="i in 18" :key="i"></div>
                </div>
            </div>
            <div class="section">
                <div class="container mx-auto">
                    <h1>Past work section</h1>
                </div>
            </div>
        </full-page>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        },
        data() {
            return {
                options: {
                    anchors: ['hello', 'what_i_do', 'past_work'],
                    menu: '#menu',
                }
            }
        },
    }
</script>
