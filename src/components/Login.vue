<template>
    <div>
        <header class="bar bar-nav">
            <h1 class='title'>登录</h1>
        </header>
        <div class="content">
            <div class="list-block">
                <ul>
                    <!-- Text inputs -->
                    <li>
                        <div class="item-content">
                            <div class="item-media"><i class="icon icon-form-name"></i></div>
                            <div class="item-inner">
                                <div class="item-title label">用户名</div>
                                <div class="item-input">
                                    <input type="text" placeholder="Your name">
                                </div>
                            </div>
                        </div>
                    </li>

                    <li>
                        <div class="item-content">
                            <div class="item-media"><i class="icon icon-form-password"></i></div>
                            <div class="item-inner">
                                <div class="item-title label">密码</div>
                                <div class="item-input">
                                    <input type="password" placeholder="Password" class="">
                                </div>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="content-block">
                <div class="row">
                    <div ><a href="#" class="button button-big button-fill button-success">提交</a></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'login',
        mounted() {
            //alert(this.msg);
        },
        data () {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        methods: {
            zan() {
                $.alert('点个赞');
            }
        }
    }
</script>