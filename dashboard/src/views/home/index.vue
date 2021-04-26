<template>
    <custom-header
        @create-account="handleAccountCreate"
        @login="handleLogin"
    />
    <contact />
    <div class="flex justify-center py-10 bg-brand-gray">
        <p class="font-medium text-center text-gray-800">Feedbacker &copy; 2021</p>
    </div>

</template>

<script>
import CustomHeader from './CustomHeader'
import Contact from './Contact'
export default {
    components : { CustomHeader, Contact},
    setup()
    {
        function handleLogin()
        {

        }

        function handleAccountCreate()
        {

        }

        return
        {
            handleLogin,
            handleAccountCreate
        }
    }

}
</script>
