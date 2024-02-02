# raffle
<!DOCTYPE html>
<html>
    <title> You have earned a raffle entry to (NAME OF CAMPAIGN)! </title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inter%3A400%2C500%2C600%2C700"/>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source+Sans+Pro%3A400%2C500%2C600%2C700"/>
    <head>
        <style>
            body {
                margin: 0;
                padding: 20px;
                font-family: Inter, sans-serif;
                background-color: #F2F5F9;
            }
            p {
                color: #0d0d0d;
                font-size: 25.6px; 
            }
            hr {
                color: #0d0d0d;
                opacity: .25;
                margin-top: 5%;
                margin-bottom: 5%;
            }
            ol li {
                color: #0d0d0d;
                font-size: 25.6px;
                line-height: 2.5rem;
            }
            .card {
                max-width: 900px;
                margin: 0 auto;
                background-color: #F2F5F9;
                box-sizing: border-box;
                margin-top: 5%;
                margin-bottom: 5%;
                box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            }
            .header {
                background-color: #0d0d0d;
                margin: 3% 5% 3% 5%;
                display: flex;
                margin-left: auto;
                margin-right: auto;
                width: 20%;
            }
            .header {
                margin-top: 0;
                background-color: #F2F5F9;
                padding: 10px;
                display: flex;
                justify-content: center;
                align-items: center; 
            }
            .txt{
                text-align: center;
                margin-top: -10px;
            }
            .title {
                font-family: Inter, 'Source Sans Pro';
                font-size: 38.4px; /* Convert rem to px */
                font-weight: 600;
                color:#0d0d0d;
            }
            .info {
                border: 0.5px solid #4a1564;
                display: flex;
                justify-content: center;
                align-items: center; 
                color:#AC895B;
            }
            .link{
                color: #AC895B;
                text-decoration: underline;
                font-weight: bold;
            }
            .contxt{
                text-align: left;
                margin-top: 20px;
            }
            .body {
                margin: 3% 5% 3% 5%;
            }
            .footer {
                background-color: #F2F5F9;
                margin: 3% 5% 3% 5%;
            }
            .ftr{
                text-align: left;
                color: #0d0d0d;
                font-size: 25.6px;
            }
            .post-mailing{
                text-align: left;
                margin-top: 10px;
                margin-bottom: 10px;
                color: #0d0d0d;
                font-size: 25.6px;
            }
            .info-container{
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                grid-gap: 5px;
                padding: 0;
                margin: 0;
                text-align: center;
            }
            .icon {
                width: 40px;
                height: 40px;
                /* padding-top: 15px; */
                padding: 10px;
            }
            .badge{
                width: 120px;
                height: auto;
            }
            .badge-wrapper {
                margin: 15px 10px;
            }
            .msg{
                text-align: center;
                font-size: small;
                font-style: italic;
                color:#444444;
                margin-top: 20px;
            }
            h3 {
                font-size: 22px;
            }
            .responsive-image {
                width: 100%;
                border-top-right-radius: 10px;
                border-top-left-radius: 10px;
            }
            a{
                text-decoration: none;
            }
            .paragraph {
                padding: 20px 50px;
            }
            .logo {
                display: block; 
                margin: 20px auto 0 auto; 
                height: 40px; 
                width:auto;
            }
            .xure-memo {
                color: #AC895B; 
                font-weight: 700; 
                font-size: 25.6pxpx;
            }
            @media only screen and (min-width: 600px) {
                .card {
                    width: 100%;
                }
                .responsive-image {
                    max-width: 100%;
                    height: auto;
                }
                .paragraph {
                    padding: 10px 20px !important;
                }
            }
            @media only screen and (max-width: 540px ) and (min-width: 320px) {
                .card {
                    width: 100%;
                }
                .responsive-image {
                    max-width: 100%;
                    height: auto;
                }
                .title {
                    font-size: 12px !important;
                }
                .paragraph {
                    padding: 10px 15px !important;
                }
                p, .ftr {
                    font-size: 10px; 
                }
                ol li {
                    font-size: 10px;
                    line-height: 1rem;
                }
                .container-social-media a .icon {
                    width: 20px;
                    height: 20px;
                    padding: 5px;
                    /* padding-top: 15px; */
                }
                .header .logo {
                    height: 16px !important;
                }
                ol {
                    padding-inline-start: 20px !important;
                }
                .ftr{
                    text-align: left;
                    color: #0d0d0d;
                    font-size: 10px;
                }
                .post-mailing{
                    margin-top: 10px;
                    margin-bottom: 10px;
                    text-align: left;
                    color: #0d0d0d;
                }
                .xure-memo {
                    color: #AC895B; 
                    font-weight: 700; 
                    font-size: 16px;
                }
                .logo {
                    display: block; 
                    margin: 10px auto 0 auto; 
                    height: 40px; 
                    width:auto;
                }
            }
        </style>
    </head>
    <body>
        <div class="card">
            <div class="header">
                <img class="logo" src="https://firebasestorage.googleapis.com/v0/b/xure-9f8a6.appspot.com/o/XURE%2Fviber_image_2024-01-11_10-11-19-511.png?alt=media&token=9254d5ea-d365-4bbd-adde-b3eaa4f90a3c" alt="Logo">
            </div>
            <div class="body">
                <div style="background-color: #ffffff; border-radius: 10px;">
                    <img class="responsive-image" src="https://firebasestorage.googleapis.com/v0/b/xure-9f8a6.appspot.com/o/banner_1.png?alt=media&token=856ef259-dfbb-4dfc-9eb7-d136f043980d" />
                    <div class="paragraph">
                        <label class="title">
                            You have earned a [Number] raffle entry/entries to (NAME OF
                            CAMPAIGN) !
                        </label>
                        <p>
                           <br> 00001356
                        </p>
                        <p>
                           00098762
                        </p>
                        <p>
                           00004648
                        </p>
                        <p class="greeting">
                            <br>
                            <span >Hi&nbsp;</span>
                            <span style="font-weight: 600;">Ricquela</span>
                            <span >,</span>
                        </p>
                        <p>
                            Thank you for participating in (NAME OF CAMPAIGN). You have earned a raffle entry that gives you a chance to win (PRIZE) from Aftermarket and Real or Fake Official.
                        </p>
                        <p>
                           Keep on completing tasks to earn more raffle entries!
                        </p>
                        <p>
                           View your progress when you visit the Xclusives tab in your Xure account.
                        </p>
                        <p>
                            <br> Best,
                            <br> Xure team
                        </p>
                    </div>
                </div>
                <br>
                <p class="xure-memo">
                   Xure
                </p>
                <p>
                    Mechanics:
                </p>
                <ol>
                    <li>
                        Winners will be selected through an electronic raffle.
                    </li>
                    <li>
                        Winners will be notified on [DATE] via email that is registered on their Xure Account
                    </li>
                    <li>
                        Winners can claim their prizes at the Aftermarket branch in Greenhills, San Juan.
                    </li>
                    <li>
                        Participants are encouraged to read and understand the complete terms and conditions of the &#34;         &#34; available at [link to full terms and conditions].
                    </li>
                    <li>
                        Failure to meet one of these qualifications will not be eligible to be part of the raffle.
                    </li>
                </ol>
                <div class="contxt">
                    <p>
                        <br/>If you have any questions or concerns, we're here to help. Contact us at  <a href = "email" class = "link"> support@xuredeal.com</a>
                    </p>
                    <p class="contxt">Follow us on:</p>
                    <div class="container-social-media">
                        <a href="https://twitter.com/xureofficial" target="_blank">
                            <img class="icon" src="https://firebasestorage.googleapis.com/v0/b/xure-9f8a6.appspot.com/o/x.png?alt=media&token=08f22cc0-bcea-4112-9384-7bb64073b0ff"/>
                        </a>
                        <a href="https://www.youtube.com" target="_blank">
                            <img class="icon" src="https://firebasestorage.googleapis.com/v0/b/xure-9f8a6.appspot.com/o/yt.png?alt=media&token=f8fc9e93-2668-4666-90e9-97ce1e2355a9"/>
                        </a>
                        <a href="https://www.tiktok.com" target="_blank">
                            <img class="icon" src="https://firebasestorage.googleapis.com/v0/b/xure-9f8a6.appspot.com/o/tiktok.png?alt=media&token=a2fae5b0-c8e6-479e-9041-e4cb1247721d"/>
                        </a>
                        <a href="https://www.facebook.com/xureofficial" target="_blank">
                            <img class="icon" src="https://firebasestorage.googleapis.com/v0/b/xure-9f8a6.appspot.com/o/fb.png?alt=media&token=a07c53b1-7cad-40c3-97c4-6e80a966eb74"/>
                        </a>
                        <a href="https://www.instagram.com/xureofficial/" target="_blank">
                            <img class="icon" style="padding-right: 0;" src="https://firebasestorage.googleapis.com/v0/b/xure-9f8a6.appspot.com/o/ig.png?alt=media&token=37f4999a-5d21-480f-8ea5-faf569f37c2e"/>
                        </a>
                    </div>
                </div>
                <div style="margin-top: 0.5rem;">
                    <p class="address">
                        XURE DEAL PTE. LTD.
                        <br>
                        39/F Marina Bay Financial Center Tower 2
                        <br>
                        Marina Blvd., Singapore 018983
                    </p>
                    <p class="address">
                        <br>
                        © 2023 All Rights Reserved.
                        <br><br>
                        This is a post-only mailing. Please do not reply to this email.
                    </p>
                    <div class="ftr"><br>
                    </div>
                </div>
            </div>
        </div>
    </body>
</html>
