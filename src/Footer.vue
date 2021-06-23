<template>
    <footer>
        <div class="box">
            <h2>About</h2>
            <div class="line-space"></div>
            <p>
                We created Everlead to effectively become the
                stepping stone towards meeting all your goals
                & achieving business success.
            </p>
            <span>
              <i class="fab fa-linkedin-in "></i>
              <i class="fab fa-facebook-f "></i>
              <i class="fab fa-twitter "></i>
          </span>
        </div>
        <div class="box">
            <h2>Twiter</h2>
            <div class="line-space"></div>
            <p>
                <i class="fab fa-twitter "></i>
                <span>
                    <a>@aliasadadm</a> Hi <a>@aliasadadm</a> , can you
                    please submit a ticket at
                    <a>https://t.co/JLV61aXG7d</a> and one of our
                    support agent...  <a>https://t.co/yk57k1S9bS</a>
                </span>
            </p>
            <p>
                <i class="fab fa-twitter "></i>
                <span>
                    <a>@aliasadadm</a> Hi <a>@aliasadadm</a> , can you
                    please submit a ticket at
                    <a>https://t.co/JLV61aXG7d</a> and one of our
                    support agent...  <a>https://t.co/yk57k1S9bS</a>
                </span>
            </p>
        </div>

        <div class="box">
            <h2>
                Important Links
            </h2>
            <div class="line-space"></div>
            <p>
                <ul>
                    <li>Abut me</li>
                    <li>Abut us</li>
                    <li>Leanguage packs</li>
                    <li>Become a coach</li>
                    <li>Monthly events</li>
                </ul>
            </p>
        </div>

        <div class="box">
            <h2>Contact me</h2>
            <div class="line-space"></div>
            <p>
                <ul>
                    <li>
                        <i class="fas fa-map-marker-alt"> </i>
                        457 BigBlue Street, NY 10013
                    </li>

                    <li>
                        <i class="fas fa-phone-alt"></i>
                        (315) 5512-2579
                    </li>

                    <li>
                        <i class="far fa-envelope"></i>
                        everlead@mikado.com
                    </li>

                    <li>
                        <input placeholder="Your Name" id="text" type="text">
                        <input id="submit" value="Subscribe" type="submit">
                    </li>
                </ul>
                
            </p>
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    @import "./components/style/General";
    footer {
        padding: 50px;
        width: 100%;
        display: inline-block;
        background-color: black;
    }

    .box {
        width: calc((100% - 200px) / 4);
        margin: 0 15px ;
        float: left;

        h2 {
            color: white;
        }
        p {
            span {
                width: 90%;
                margin-left: 10px;
                margin-bottom: 10px;
                float: left;
                a {
                    border-bottom: 1px solid $greyText ;
                }
            }
            i {
                color: $orange;
                display: block;
                float: left;
            }

            ul {
                padding: 0;
                li {
                    list-style: none;
                    margin-top: 10px;
                    i {
                        margin-right: 14px;
                    }
                    #text {
                        width: 70%;
                        background-color: transparent;
                        border: 0;
                        border-bottom: 1px solid white;
                    }
                    #submit {
                        width: 30%;
                        background-color: transparent;
                        border: 0;
                        color: white;
                        border-bottom: 1px solid white;
                    }
                }
            }
        }
    }

    .line-space {
        margin: 15px 0;
    }
    span {
        .fa-twitter {
            margin: 10px;
            padding: 8px;
            font-size: 13px;
            border-radius: 50%;
            color: black;
            background-color: white;
        }
        .fab {
            margin: 10px;
            padding: 8px 10px;
            font-size: 13px;
            border-radius: 50%;
            color: black;
            background-color: white;
        }

    }


</style>>