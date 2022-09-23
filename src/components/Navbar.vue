    <template>
    <section>
        <nav class="navbar navbar-expand-lg fixed-top py-3" style="background-color:#fff;">
        <div class="container">
            <router-link class="navbar-brand" to="/">Romax</router-link>
            <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
            >
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item me-2">
                <router-link to="/" :class="{active : $route.name == 'Home'}" class="nav-link">Home</router-link>
                </li>
                <li class="nav-item me-2">
                <router-link to="/about" :class="{active : $route.name == 'About'}" class="nav-link">About Us</router-link>
                </li>
                <li class="nav-item me-2">
                <router-link to="/projects" :class="{active : $route.name == 'Projects'}" class="nav-link">Our Projects</router-link>
                </li>
                <li class="nav-item me-2">
                <router-link to="/contact" :class="{active : $route.name == 'Contact'}" class="nav-link">Contact Us</router-link>
                </li>
            </ul>
            </div>
        </div>
        </nav>
    </section>
        
    </template>

    <script>
    export default {
        name : 'Navbar',
    }
    </script>

    <style lang="scss" scoped>
    .navbar-brand{
        color: orange;
        font-size: 20px;
    }
    li{
        font-size: 18px !important;
    }
    </style>