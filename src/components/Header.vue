<template>
    <header>
        <nav class="navbar-container">
            <div class="navbar">
                <p>Where in the world?</p>
                <button>
                    <img src="../assets/images/moon-icon.svg" alt="icon moon"/>
                    <span>Dark Mode</span>
                </button>
            </div>
        </nav>
    </header>
</template>

<script>
export default {
    setup() {},
}
</script>

<style scoped>
    .navbar-container {
        width: 100%;
        position: fixed;
        top: 0;
        padding: 1.5em;
        box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
    }
    .navbar {
        display: flex;
        max-width: 1170px;
        justify-content: space-between;
        margin: 0 auto;
    }
    p {
        font-size: 16px;
        font-weight: 800;
    }
    button {
        font-size: 14px;
        font-weight: 600;
        background-color: transparent;
        border: none;
        display: flex;
        align-items: center;
    }
    img {
        padding-right: 3px;
        width: 20px;
    }
</style>