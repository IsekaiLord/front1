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
input {
    padding: 10px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    width: 200px;
    background-color: var(--bg-color);
    color: var(--text-color);
    border: 1px solid var(--border-color);
}
form {
    background-color: var(--primary-color);
    flex-direction: column;
    align-items: center;
    margin-top: 2rem;
    justify-content: center;
    gap: 10px;
    border-radius: 10px;
    padding: 2rem;
}
</style>