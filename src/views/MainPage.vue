<template>
        <div class="flex w-full h-3/4 justify-center items-top mt-10">
            <div class="w-full max-w-xs rounded-lg shadow-lg bg-whites-300">
                    <div class="text-lg font-bold px-5">A타입 성향질문을 시작합니다.<br>클릭하세요!</div>
                    <div class="px-5 py-5">
                        <router-link to="/QuestionList">
                            <button class="flex h-48 w-full bg-blue-500 hover:bg-blue-700 text-white justify-center items-center font-bold rounded-xl">
                            A타입(소비성향)
                            </button>    
                        </router-link>
                    </div>
            </div>
                <!-- <h1 class="font-bold text-xl text-center text-gray-600"> -->
                <!-- <LikertQuestion /> -->
        </div>
</template>
<script setup>
    import QuestionList from '../components/QuestionList.vue'
    import LikertQuestion from '../components/LikertQuestion.vue'
    import VehicleQuestion from '../components/VehicleQuestion.vue'
    
</script>