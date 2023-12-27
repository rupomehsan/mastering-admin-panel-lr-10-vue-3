<template>
    <!--Start topbar header-->
    <header class="topbar-nav">
        <nav class="navbar navbar-expand fixed-top">

            <div class="toggle-menu">
                <i @click.prevent="toggle_menu" class="zmdi zmdi-menu"></i>
            </div>

            <div class="search-bar flex-grow-1">

            </div>

            <ul class="navbar-nav align-items-center right-nav-link ml-auto">
                <li class="nav-item dropdown language">
                    <a class="nav-link dropdown-toggle dropdown-toggle-nocaret position-relative" data-toggle="dropdown"
                        href="javascript:void();" aria-expanded="false"><i
                            class="flag-icon flag-icon-gb align-middle"></i></a>
                    <ul class="dropdown-menu dropdown-menu-right">
                        <li class="dropdown-item"><i class="flag-icon flag-icon-gb mr-3"></i>English</li>
                        <li class="dropdown-item"><i class="flag-icon flag-icon-fr mr-3"></i>French</li>
                        <li class="dropdown-item"><i class="flag-icon flag-icon-cn mr-3"></i>Chinese</li>
                        <li class="dropdown-item"><i class="flag-icon flag-icon-de mr-3"></i>German</li>
                    </ul>
                </li>
                <nofication></nofication>

                <top-right-profile></top-right-profile>
            </ul>
        </nav>
    </header>
    <!--End topbar header-->
</template>

<script>
import Nofication from './Nofication.vue'
import TopRightProfile from './TopRightProfile.vue'
export default {
    components: { Nofication, TopRightProfile },
    methods: {
        toggle_menu: function () {
            document.getElementById('wrapper').classList.toggle('toggled');
        }
    }
}
</script>

