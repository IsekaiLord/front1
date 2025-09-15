<template>
        <h1>GitKraken</h1>
        <div class="df">
        <h2>Welcome to GitKraken!</h2>
        <img alt="GitKraken logo" class="logo vue" src="../assets/gitkraken.png"/>
        </div>

        <form class="df">
            <input type="email" id="email" name="email" placeholder="Your email" />
            <input type="text" id="name" name="name" placeholder="Your name"/>
            <button type="submit">Login</button> 
        </form>
</template>


<script>

</script>

<style scoped>
h1{
    background-color: var(--primary-color);
}

.logo.vue {
  height: 10em;
  padding: 1.5em;
  position: relative;
    top: 0;
    left: 0;
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
form {
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
    gap: 10px;
}
</style>