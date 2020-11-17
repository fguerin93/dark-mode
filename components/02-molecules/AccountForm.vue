<template>
    <div class="m-account-form">
        <form action="get" id="accountForm">
            <label for="email" class="a-label">Email</label>
            <input type="email" id="email" name="email" placeholder="example@gmail.com" class="a-input">
            <label for="fullname" class="a-label">Full name</label>
            <input type="text" id="fullname" name="fullname" placeholder="Sacha Tourtoulou" class="a-input">
        </form>

        <button class="a-button a-button-primary" value="Save">Save</button>
    </div>
</template>