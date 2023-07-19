<template>
    <!-- <CircleSquare /> -->
    <div class="container">
        <div class="item">
            <a class="logo" href="#">KARTINFLIX</a>
        </div>
        <div class="item links-container">
            <a class="link" id="first-link" href="#">About</a>
            <a class="link" href="#">Sign In</a>
            <a class="link" href="#">Sign Up</a>
            <a class="link" id="last-link" href="#">Help</a>
        </div>
    </div>
</template>

<style scoped>
.logo {
    font-family: Lilita One;
    font-size: 2rem;
    border: 1px solid black;
    border-radius: 5px;
    padding: 0 0.5rem;
    text-decoration: none;
    color: indigo;
}
.item {
    /* border: 1px solid indigo; */
    flex-grow: 1;
}

.link {
    background-color: rgb(34, 34, 193);
    /* border-radius: 5px; */
    padding: 0.6rem 0.7rem;
    text-decoration: none;
    font-family: Montserrat;
    color: aliceblue;
}

#first-link {
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
}

#last-link {
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
}

.link:hover {
    background-color: rgb(29, 29, 157);
}

.links-container {
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

.container {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
</style>
