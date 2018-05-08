<template>
    <div id="login">
        <h1>Log In</h1>
<!--            input forms for login-->
        <input id="email" class="inputForm" type="text" v-model="email" placeholder="Email"><br>
        <input id="password" class="inputForm" type="password" v-model="password" placeholder="Password"><br>
        <button id="loginButton" class="btn btn-primary" @click="logIn">Log In</button><br>
        <br>
        <!--redirect to sign up-->
        Don't have an account? <button id="signUpButton" class="btn btn-success btn-sm">Sign Up</button>
    </div>
    
</template>

<script>
    export default {
        name: "login",
        data () {
            return {
                
            }
        }
    }
</script>

<style scoped>
    h1{
        font-size:60px;
        margin-bottom:30px;
    }
    #login{
        text-align: center;
        border: 1px solid black;
        box-shadow: 8px 14px #888888;
        height: 500px;
        width:500px;
        padding-top:80px;
        position: absolute;
        top:0;
        bottom: 0;
        left: 0;
        right: 0;
        margin: auto;
    }
    #loginButton{
        width:200px;
    }
    #email{
        width:200px;
        border-radius:5px;
        border: 1px solid grey;
        padding: 5px 5px 5px 5px; 
        margin-bottom:5px;
    }
    #password{
        width:200px;
        border-radius:5px;
        border: 1px solid grey;
        padding: 5px 5px 5px 5px; 
        margin-bottom:10px;
    }
    
</style>