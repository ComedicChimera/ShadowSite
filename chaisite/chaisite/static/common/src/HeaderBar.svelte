<script>

</script>

<style lang="scss">
    @import "chaisite/chaisite/static/common/src/scss/globals.scss";

    .header {
        padding: 1rem;
        margin-bottom: 1rem;

        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;

        box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.16);

        .full-logo a {
            display: flex;
            flex-direction: row;
            justify-content: space-evenly;
            align-items: center;

            text-decoration: none;

            .logo-text {
                padding-left: 1rem;
                font-size: 2.5rem;
                font-family: 'Roboto', sans-serif;
            }
        }

        .nav {
            padding-right: 2rem;

            a {
                padding-left: 1rem;
                padding-right: 1rem;
                font-size: 1.5rem;
                font-family: 'Open Sans', sans-serif;
                color: $text-color;
                text-decoration: none;
                transition-duration: 0.5s;
            }

            a:hover {
                color: $primary-color;
                transition-duration: 0.5s;
            }
        }
    }
</style>

<div class="header">
    <div class="full-logo">
        <a href="/">
            <img src="/static/common/images/chai_logo.png" width="70em" height="83em" alt="Chai logo"/>
            <div class="logo-text">
                <span class="primary-color">Cha</span><span class="secondary-color">i</span>
            </div>
        </a>   
    </div>
    <div class="nav">
        <a href="/install">install</a>
        <a href="/docs">docs</a>
        <a href="/packages">packages</a>
        <a href="/community">community</a>
    </div>
</div>