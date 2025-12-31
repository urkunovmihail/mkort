<template>
        <!-- Блок Обратная связь-->
        <div class="bg-[url(assets/img/bg-im.webp)] bg-gray-100 bg-no-repeat bg-bottom-right bg-contain p-4 "> 
            <div class="flex flex-col lg:flex-row lg:justify-around items-start container mx-auto">
                <div class="md:pr-2 pt-2 lg:w-1/4 w-full">
                    <!-- НАЧАЛО Блок контактная инфорамция левая часть-->
                    <div class="flex flex-col flex-wrap px-3  container ">
                        <div class="flex flex-row justify-center items-center">
                            <div class="p-1 w-full ">
                                <p class="uppercase text-green-500 text-left font-[Montserrat] font-semibold ">
                                    остались вопросы ?
                                </p>
                            </div>
                        </div>
                        <div class="flex flex-row justify-center items-center">
                            <div class="p-1 w-full ">
                                <p class="normal-case text-left font-[Montserrat] text-2xl sm:text-3xl">
                                    Получить консультацию
                                </p>
                            </div>
                        </div>
                    </div>
                    <!-- КОНЕЦ Блок контактная инфорамция левая часть-->
                </div>
                <div class="lg:pr-2 lg:w-3/4 w-full">
                    <div class="flex flex-col flex-wrap px-3 container mx-auto">
                        <!-- НАЧАЛО Блок контактная инфорамция-->
                        <div class=" w-full flex flex-col lg:flex-row pt-3">
                            <div class="flex flex-row justify-center items-center w-full lg:w-1/3">
                                <div class="p-1 w-full ">
                                    <div
                                        class="pl-2.5 w-full text-lg text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus-within:outline-1 focus-within:-outline-offset-2 focus-within:outline-green-300 ">
                                        <input id="username" type="text" name="username" placeholder="ВАШЕ ИМЯ"
                                            class="w-full block min-w-0 grow py-5 pr-3 pl-1 text-xl text-gray-900 placeholder:text-gray-400 focus:outline-none sm:text-lg md:text-xl" />
                                    </div>
                                </div>
                            </div>
                            <div class="flex flex-row justify-center items-center w-full lg:w-1/3">
                                <div class="p-1 w-full ">
                                    <div
                                        class="pl-2.5 w-full text-lg text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus-within:outline-1 focus-within:-outline-offset-2 focus-within:outline-green-300">
                                        <input id="phone" type="text" name="phone" placeholder="ТЕЛЕФОН"
                                            class="w-full block min-w-0 grow py-5 pr-3 pl-1 text-xl text-gray-900 placeholder:text-gray-400 focus:outline-none sm:text-lg md:text-xl" />
                                    </div>
                                </div>
                            </div>
                            <div class="flex flex-row justify-center items-center w-full lg:w-1/3">
                                <div class="p-1 w-full ">
                                    <div
                                        class="pl-2.5 w-full text-lg text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus-within:outline-1 focus-within:-outline-offset-2 focus-within:outline-green-300">
                                        <input id="email" type="text" name="email" placeholder="E-MAIL"
                                            class="w-full block min-w-0 grow py-5 pr-3 pl-1 text-xl text-gray-900 placeholder:text-gray-400 focus:outline-none sm:text-lg md:text-xl" />
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- КОНЕЦ Блок контактная инфорамция-->
                        <!-- НАЧАЛО Блок сообщение-->
                        <div class="flex flex-row md:flex-col justify-center items-center">
                            <div class="p-1 w-full">
                                <textarea id="message"  rows="4" 
                                    class=" pl-2.5 pt-2.5 pb-2.5 w-full text-lg text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus-within:outline-1 focus-within:-outline-offset-2 focus-within:outline-green-300"
                                    placeholder="СООБЩЕНИЕ" ></textarea>
                            </div>
                        </div>
                        <!-- КОНЕЦ Блок сообщение-->
                        <div class="flex flex-row md:flex-col justify-center items-center">
                            <div class="p-1 w-full">
                                <button type="button"
                                    class="w-full cursor-pointer text-gray-900 bg-gray-50 border border-black focus:outline-none hover:bg-black hover:text-white focus:ring-4 focus:ring-gray-100  rounded-lg text-xl px-5 py-2.5 me-2 mb-2 ">ОТПРАВИТЬ</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- /Блок Обратная связь-->
</template>