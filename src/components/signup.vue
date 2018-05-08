<template>
    <div id="signup">
        <h2>Sign Up for BodyTwins</h2>
        <div id="signup-form">
            Name: <input placeholder="Enter Name" class="signup-input" type="text">
            <br>
            Age: <input placeholder="Enter Age" class="signup-input" type="text">
            <br>
            Gender: <input placeholder="Enter Gender" class="signup-input" type="text">
            <br>
            Height: <input placeholder="Enter Height" class="signup-input" type="text">
            <br>
            Weight: <input placeholder="Enter Weight" class="signup-input" type="text">
        </div>
        <button id="signup-btn" class="btn btn-success" @click="signUp">Sign Up</button><br>
        Have an account?<button id="login-btn" class="btn btn-primary btn-sm">Login</button>
    </div>
</template>

<script>
    export default {
        name: "signup",
        data () {
            return {
            }
        }
    }
</script>

<style scoped>
    h2{
        margin-bottom:50px;
    }
    #signup{
        text-align: center;
        border: 1px solid black;
        box-shadow: 8px 14px #888888;
        height: 500px;
        width:500px;
        padding-top:30px;
        position: absolute;
        top:0;
        bottom: 0;
        left: 0;
        right: 0;
        margin: auto;
    }
    #signup-form{
        font-size: 20px;
        font-weight: bold;
    }
    #signup-btn{
        width:300px;
        margin-bottom:40px;
        margin-top:20px;
    }
    .signup-input{
        border-radius:5px;
        border: 1px solid grey;
        margin-bottom:10px;
        padding-left:10px;
    }
    #login-btn{
        margin-left:10px;
    }
</style>