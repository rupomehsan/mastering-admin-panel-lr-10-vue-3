<template>
    <li class="nav-item dropdown dropdown-lg">
        <a class="nav-link dropdown-toggle dropdown-toggle-nocaret position-relative" data-toggle="dropdown"
            href="javascript:void();" aria-expanded="false">
            <i class="zmdi zmdi-comment-outline align-middle"></i><span class="bg-danger text-white badge-up">12</span></a>
        <div class="dropdown-menu dropdown-menu-right">
            <ul class="list-group list-group-flush">
                <li class="list-group-item d-flex justify-content-between align-items-center">
                    New Messages <a href="javascript:void();" class="extra-small-font">Clear All</a>
                </li>
                <li class="list-group-item">
                    <a href="javaScript:void();">
                        <div class="media">
                            <div class="avatar"><img class="align-self-start mr-3" src="assets/images/avatars/avatar-5.png"
                                    alt="user avatar"></div>
                            <div class="media-body">
                                <h6 class="mt-0 msg-title">Jhon Deo</h6>
                                <p class="msg-info">Lorem ipsum dolor sit amet...</p>
                                <small>Today, 4:10 PM</small>
                            </div>
                        </div>
                    </a>
                </li>
                <li class="list-group-item">
                    <a href="javaScript:void();">
                        <div class="media">
                            <div class="avatar"><img class="align-self-start mr-3" src="assets/images/avatars/avatar-6.png"
                                    alt="user avatar"></div>
                            <div class="media-body">
                                <h6 class="mt-0 msg-title">Sara Jen</h6>
                                <p class="msg-info">Lorem ipsum dolor sit amet...</p>
                                <small>Yesterday, 8:30 AM</small>
                            </div>
                        </div>
                    </a>
                </li>
                <li class="list-group-item">
                    <a href="javaScript:void();">
                        <div class="media">
                            <div class="avatar"><img class="align-self-start mr-3" src="assets/images/avatars/avatar-7.png"
                                    alt="user avatar"></div>
                            <div class="media-body">
                                <h6 class="mt-0 msg-title">Dannish Josh</h6>
                                <p class="msg-info">Lorem ipsum dolor sit amet...</p>
                                <small>5/11/2018, 2:50 PM</small>
                            </div>
                        </div>
                    </a>
                </li>
                <li class="list-group-item">
                    <a href="javaScript:void();">
                        <div class="media">
                            <div class="avatar"><img class="align-self-start mr-3" src="assets/images/avatars/avatar-8.png"
                                    alt="user avatar"></div>
                            <div class="media-body">
                                <h6 class="mt-0 msg-title">Katrina Mccoy</h6>
                                <p class="msg-info">Lorem ipsum dolor sit amet.</p>
                                <small>1/11/2018, 2:50 PM</small>
                            </div>
                        </div>
                    </a>
                </li>
                <li class="list-group-item text-center"><a href="javaScript:void();">See All Messages</a></li>
            </ul>
        </div>
    </li>
    <li class="nav-item dropdown dropdown-lg">
        <a @click.prevent="show_notification = !show_notification" href="#"
            class="nav-link dropdown-toggle dropdown-toggle-nocaret position-relative">
            <i class="zmdi zmdi-notifications-active align-middle"></i>
            <span class="bg-info text-white badge-up">14</span>
        </a>
        <div class="dropdown-menu dropdown-menu-right show" v-show="show_notification">
            <ul class="list-group list-group-flush">
                <li class="list-group-item d-flex justify-content-between align-items-center">
                    New Notifications <a href="javascript:void();" class="extra-small-font">Clear
                        All</a>
                </li>
                <li class="list-group-item">
                    <a href="javaScript:void();">
                        <div class="media">
                            <i class="zmdi zmdi-accounts fa-2x mr-3 text-info"></i>
                            <div class="media-body">
                                <h6 class="mt-0 msg-title">New Registered Users</h6>
                                <p class="msg-info">Lorem ipsum dolor sit amet...</p>
                            </div>
                        </div>
                    </a>
                </li>
            </ul>
        </div>
    </li>
</template>

<script>
export default {
    data: () => ({
        show_notification: 0,
    })
}
</script>

<style></style>
