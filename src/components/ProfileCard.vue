/* 
* Inside the script tag we declare the imports
* and the component logic
*/
<script setup>
    const developer = {
        name: "Cristian Camilo",
        role: "Full Stack Developer",
        country: "Colombia 🇨🇴"
    };
</script>

/*
* Inside the template tag we declare the HTML
* elements inside the component
*/
<template>
    <div class="profile-card">
        <img 
            src="https://litslink.com/wp-content/uploads/2024/06/8-1024x682.jpg" 
            alt="Profile picture"
        >

        <h2>{{ developer.name }}</h2>
        <p>{{ developer.role  }}</p>
        <span>{{ developer.country }}</span>
    </div>
</template>