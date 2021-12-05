<style>
body { background-color:#d5d5d5;background-image:url(https://i.ibb.co/6XPXZBp/brushed.png);background-position:fixed;margin:0px; }
.favthings-grad { position:fixed;height:500px;width:100vw;z-index:1;background:linear-gradient(to bottom,#6197BA,rgba(255,255,255,0));opacity:.35;opacity:0;top:0px; }
#wrapper { position:relative;z-index:1;margin: 0 auto 35px auto; width:1000px;min-height:150vh;background-color:#eeeeee;box-shadow:0px 0px 5px rgba(33,33,33,.2);padding:33px;border:solid 2px #f3f3f3; border-radius:5px; }

.favthings-nav { background:#333333;padding:10px 0px;width:100%;min-width:1150px;overflow:hidden;height:40px;border-bottom:solid 2px #eeeeee;box-shadow:0px 0px 5px rgba(33,33,33,.2);position:sticky;z-index:100000000;top:0px;right:0px; }
.favthings-nav-0 { margin:0px auto;max-width:1150px; }

.favthings-banner { background-color:#c5c5c5;height:600px!important;position:relative;z-index:1;overflow:hidden;min-width:1150px; }
.favthings-banner-2 { min-width:1150px;overflow:hidden;margin-bottom:0px;height:250px;background-color:#eeeeee;position:relative;z-index:1;box-shadow:0px 0px 5px rgba(33,33,33,.2); }
.favthings-banner-imgg { height:600px;width:100%;background-image:url(https://i.ibb.co/61qzVPQ/MikuMk.png);position:absolute;margin-top:37px;mix-blend-mode:lighten;filter:grayscale(100%) contrast(150%) brightness(80%); }
.favthings-banner-grad { margin-top:37px;position:absolute;z-index:11;height:600px;width:100%;min-width:1150px;background:radial-gradient(rgba(235,235,235,.3),rgba(235,235,235,0));mix-blend-mode:overlay;pointer-events:none; }
.favthings-banner-color { background:linear-gradient(to bottom left,#347DAE,#DCBB9D);height:600px;width:50vw;min-width:575px;transform:skew(-20deg);position:absolute;z-index:1;margin-left:-315px;margin-top:37px;text-align:right;overflow:hidden; }
.favthings-banner-color div { background-image:url(https://i.ibb.co/wBWc2DD/Barrrb.png);background-size:100% auto;height:869px;width:1080px;background-repeat:no-repeat;background-size:100% auto;transform:skew(20deg);margin:-250px 0px 0px -75px; mix-blend-mode:multiply;filter:grayscale(100%) blur(3px);opacity:.3; }
.favthings-banner-img { background-image:url(https://i.ibb.co/wBWc2DD/Barrrb.png);height:869px;width:720px;background-repeat:no-repeat;background-size:100% auto;position:relative;z-index:10;margin:-37px 0px 0px -550px;pointer-events:none; }
.favthings-banner-centering { width:1140px;margin:0px auto; }
.favthings-banner-name { text-shadow:2px 2px 10px rgba(33,33,33,.1);font:800 150px Montserrat;line-height:120px;color:#eeeeee;position:absolute;white-space:nowrap;width:0px;height:0px;z-index:2;margin:100px 0px 0px 352px;pointer-events:none; }
.favthings-banner-name-2 { position:absolute;z-index:3;margin:108px 0px 0px 829px;pointer-events:none; }
.favthings-banner-name-2 div { background-color:#eeeeee;color:#c5c5c5;padding:33px 30px 32px 30px;font:20px Roboto Condensed;line-height:20px;height:40px;text-align:left;letter-spacing:-.35px;width:186px;white-space:nowrap;box-shadow:2px 2px 10px rgba(33,33,33,.1);border-radius:5px; }
.favthings-banner-icon { position:absolute;z-index:2;margin:130px 0px 0px -20px; }
.favthings-banner-icon-2 { height:100px;width:100px;padding:30px;margin:-1px;background-color:#eeeeee;border-radius:100%;box-shadow:2px 2px 10px rgba(33,33,33,.25); }
.favthings-banner-icon-2 img { height:100px;width:100px;border-radius:100%;filter:grayscale(100%); }
.favthings-banner-icon-1 { border:dotted 3px #eeeeee;border-radius:100%;height:160px;width:160px;padding:17px;box-shadow:2px 2px 10px rgba(33,33,33,.25); }
.favthings-banner-user { font:800 40px Montserrat;line-height:30px;letter-spacing:-1.75px;text-transform:lowercase;color:#eeeeee;text-shadow:2px 2px 10px rgba(33,33,33,.25);position:absolute;z-index:3;margin:355px 0px 0px -95px;text-align:right;width:275px; }
.favthings-updates { height:200px;width:400px;overflow:auto;padding-right:15px;position:absolute;transform:skew(-20deg);margin:365px 0px 0px 510px;color:#333333; }
.favthings-updates::-webkit-scrollbar { width:10px;background-color:transparent; }
.favthings-updates::-webkit-scrollbar-thumb { background-color:#eeeeee;width:10px;border-radius:10px;box-shadow:2px 2px 10px rgba(33,33,33,.1); }
.favthings-updates-1 { background:linear-gradient(to bottom,rgba(238,238,238,.65),rgba(238,238,238,.25));border-left:solid 10px #DCBB9D;border-radius:5px;padding:15px 30px 15px 20px;margin-bottom:10px;cursor:pointer;transition:.2s all;box-shadow:2px 2px 10px rgba(33,33,33,.1); }
.favthings-updates-1 div { transform:skew(20deg);text-align:left;font:12px Roboto; }
.favthings-updates-1 h1 { margin:0px;padding:0px 0px 10px 10px;font:700 20px Roboto Condensed;line-height:20px; }
.favthings-updates-1 h1 b { color:#DCBB9D;transition:.2s all; }
.favthings-updates-1:hover { border-color:#6197BA;background-color:rgba(238,238,238,.65); }
.favthings-updates-1:hover .favthings-updates-2 { color:#6197BA; }

.favthings-nav-left { padding-left:10px;display:flex;position:relative;z-index:1; }
a { text-decoration:none!important;text-shadow:0px 0px 4px rgba(0,0,0,.25); }
.favthings-nav-1 { width:30px;height:40px;overflow:hidden;padding-right:10px;color:#c5c5c5;transition:.2s; }
.favthings-nav-2 { width:130px; }
.favthings-nav-3 { float:left;height:36px;width:36px;text-align:center;border:solid 2px #333333;border-radius:100%;font-size:18px;transition:.2s; }
.favthings-nav-3 i::before { display:block;line-height:36px; }
.favthings-nav-4 { float:left;opacity:0;font:bold 10px Roboto;line-height:10px;padding:10px;border-radius:3px;background-color:#393939;margin:5px 0px 0px 5px;width:60px;white-space:nowrap;text-align:center;letter-spacing:1px;box-shadow:0px 0px 3px rgba(20,20,20,.2);transition:.2s; }
.favthings-nav-5 { position:absolute;box-shadow:0px 0px 3px rgba(20,20,20,.2);background-color:#393939;border-radius:100%;font:800 7px Montserrat;text-shadow:none;line-height:15px;width:15px;color:#6197BA;text-align:center;margin:2px 0px 0px 22px; }
.favthings-navv { width:50vw;min-width:575px;background:linear-gradient(to left,#333333,#393939);margin-top:-10px;padding-right:35px;transform:skew(-20deg);right:-20px;height:60px;position:absolute;box-shadow:0px 0px 3px rgba(20,20,20,.2); }
.favthings-tog { cursor:pointer;transition:.5s all;background-color:#DCBB9D;margin:-10px 15px 0px -21px;height:60px;width:80px;transform:skew(-20deg); }
.favthings-tog div { transform:skew(20deg);text-align:center;color:#333333;text-shadow:none;font-size:25px; }
.favthings-tog div i::before { display:block;line-height:60px;}

.favthings-nav-1:hover { width:125px; }
.favthings-nav-1:hover .favthings-nav-3 { font-size:25px;color:#6197BA; }
.favthings-nav-1:hover .favthings-nav-4 { opacity:1; }
.favthings-tog:hover { background-color:#6197BA; }
.favthings-nav-right { font:bold 12px Roboto;line-height:12px;padding:8px 17px 8px 0px;color:#c5c5c5;text-align:right;text-transform:uppercase;letter-spacing:.5px;flex-grow:1; }
.favthings-nav-right b, .favthings-nav-right a { color:#6197BA; }
.favthings-nav-right div { float:right;padding:8px;margin:-2px 0px -1px 15px;font:bold 10px Roboto;color:#eeeeee;line-height:10px;background-color:#6197BA;border-radius:3px;transition:.5s all; }
.favthings-nav-right div i::before { float:left;line-height:10px;padding-right:5px; }
.favthings-nav-right div:hover { background-color:#DCBB9D; }



.favthings-benner-image { position:relative;z-index:15;margin:-323px auto -202px auto;margin:0px auto;width:1150px;height:0px;pointer-events:none; }
.favthings-benner-img { width:1150px;overflow:visible;height:525px;margin:-323px 0px -202px 0px;position:absolute; }
.favthings-benner-img div { background-image:url(https://i.ibb.co/r2145H1/Scuro23.png);height:525px;width:464px;background-repeat:no-repeat;background-position:right top;margin:0px -100px 0px 725px;position:relative;float:left; }
.favthings-benner { border-top:solid 2px #eeeeee;height:200px;background-color:#e7e7e7;width:100%;min-width:1150px;position:relative;z-index:3;box-shadow:0px -3px 5px -3px rgba(33,33,33,.2); }
.favthings-benner-imgg { height:200px;width:100%;min-width:1150px;position:absolute;background-image:url(https://i.ibb.co/LkB6xgQ/yerrrrrr.png);background-repeat:no-repeat;mix-blend-mode:multiply;background-position:center right;filter:grayscale(100%);transform:scaleX(-1);opacity:.075; }
.favthings-benner-0 { padding:20px;width:1110px;margin:0px auto;display:flex;position:relative;z-index:1; }

.favthings-benner-0 input { display:none; }
.favthings-benner-0 label { position:absolute;z-index:100000000;height:36px;width:36px;cursor:pointer;border-radius:100%;margin:-4px 0px 0px 696px; }

.favthings-benner-right { height:200px;width:300px;background-color:#333333;margin:-20px 0px 0px 0px;transform:skew(-20deg);position:absolute;z-index:10;margin-left:655px;border-left:solid 70px #6197BA; }

.favthings-benner-right div { display:block;position:absolute;z-index:10000;height:200px;width:335px;background:linear-gradient(to bottom,rgba(240,240,240,.2),rgba(0,0,0,0));margin-left:-71px; }
.favthings-benner-right h1 { height:30px;width:30px;transform:skew(20deg) scale(.9);position:absolute;background:radial-gradient(rgba(51,51,51,.75),rgba(51,51,51,0));padding:5px;border-radius:100%;margin:14px 0px 0px -55px; }
.favthings-benner-right h1 span { display:block;height:15px;width:30px;background-color:#333333;border-radius:100%;overflow:hidden;font:700 22px Roboto;line-height:15px;text-align:right;padding-top:15px;letter-spacing:-1.5px;color:#6197BA; }
.favthings-benner-num { position:absolute;font:800 300px Roboto;line-height:200px;height:200px;width:660px;padding-right:65px;overflow:hidden;text-align:right;margin:-20px 0px 0px 250px;letter-spacing:-55px;color:#eeeeee;text-shadow:2px 2px 10px rgba(33,33,33,.065);transition:.3s all;pointer-events:none; }
.favthings-benner-ad { position:absolute;padding:10px;background-color:#eeeeee;box-shadow:2px 2px 10px rgba(33,33,33,.065);height:140px;width:485px;border-radius:10px;opacity:0;margin-left:-25px;transition:.4s all;pointer-events:none; }
.favthings-benner-ad-1 { height:140px;width:485px;border-radius:5px;position:relative;overflow:hidden; }
.favthings-benner-ad-2 { height:140px;width:270px;transform:skew(-20deg);border-right:solid 5px #eeeeee;box-shadow:0px 0px 5px rgba(33,33,33,.2);overflow:hidden;margin-left:-25px;position:absolute;z-index:1;background-color:#333333;transition:.3s all; }
.favthings-benner-ad-2 div { transform:skew(20deg);mix-blend-mode:lighten; }
.favthings-benner-ad-2 div img { height:140px;width:300px;filter:grayscale(100%) contrast(90%); }
.favthings-benner-ad-3 { position:absolute;background:linear-gradient(to bottom right,#347DAE,#DCBB9D);padding-left:250px;text-align:right;height:140px;font:800 40px Montserrat;letter-spacing:-3px;line-height:31px;display:flex;flex-direction:column;justify-content:flex-end;color:#eeeeee;text-transform:uppercase; }
.favthings-benner-ad-3 h1 { margin:0px 11px 10px 0px;font:bold 10px Roboto;text-shadow:none;line-height:10px;letter-spacing:1px;background-color:#eeeeee;color:#333333;align-self:flex-end;padding:10px;border-radius:5px;box-shadow:0px 0px 5px rgba(33,33,33,.2);mix-blend-mode:lighten; }
.favthings-benner-ad-3 div { margin:0px -5px -2px 0px;text-shadow:0px 0px 5px rgba(33,33,33,.2); }
.favthings-benner-ad-4 { position:absolute;margin:162px 0px 0px 22px;font:12px Roboto;letter-spacing:.25px;text-align:justify;color:#eeeeee;width:225px; padding-right:15px;height:96px;overflow:auto;text-shadow:0px 0px 3px rgba(33,33,33,.2);transition:.3s all; }
.favthings-benner-ad-4::-webkit-scrollbar { width:6px;background-color:transparent; }
.favthings-benner-ad-4::-webkit-scrollbar-thumb { background-color:#eeeeee;width:10px;border-radius:10px;box-shadow:2px 2px 10px rgba(33,33,33,.1); }
.favthings-benner-ad:hover .favthings-benner-ad-2 { margin-left:-300px; }
.favthings-benner-ad:hover .favthings-benner-ad-4 { margin-top:22px; }

.favthings-benner-affs { position:absolute;z-index:1;margin-left:540px;margin-top:-4px;opacity:0;transition:.4s all;pointer-events:none; }
.favthings-benner-affs div { margin-bottom:1px;height:31px;width:88px;padding:5px;background-color:#eeeeee;border-radius:5px;transform:scale(.85);transition:.2s;box-shadow:2px 2px 10px rgba(33,33,33,.065); }
.favthings-benner-affs img { border-radius:3px;filter:grayscale(100%) contrast(90%);transition:.2s; }
.favthings-benner-affs div:hover { transform:scale(1); }
.favthings-benner-affs img:hover { filter:grayscale(0%) contrast(100%); }

.favthings-tree { background-color:#e8e8e8;border-bottom:solid 2px #eeeeee;box-shadow:0px 0px 5px rgba(33,33,33,.2);width:100%;min-width:1150px;position:relative;z-index:1;margin-bottom:40px; }

.favthings-staff { display:flex;position:absolute;z-index:1;transition:.4s all;transform:scale(.75);opacity:0;pointer-events:none;margin-left:10px; }
.favthings-staff-1 { margin-right:20px;height:160px;width:110px;background-color:#393939;border-radius:10px;box-shadow:2px 2px 10px rgba(33,33,33,.065);overflow:hidden;position:relative; }
.favthings-staff-img { mix-blend-mode:lighten;transition:.2s all;background-color:#eeeeee;width:110px;height:160px;border-radius:10px; }
.favthings-staff-1:hover .favthings-staff-img { background-color:#DCBB9D; }
#FVSE:hover .favthings-staff-img { background-color:#347DAE!important; }
#FVSO:hover .favthings-staff-img { background-color:#6197BA!important; }
.favthings-staff-img img { height:160px;width:110px;mix-blend-mode:multiply;border-radius:10px;filter:contrast(120%) brightness(110%); }
.favthings-staff-2 { position:absolute;font:800 35px Montserrat;line-height:25px;margin:-50px 0px 0px -3px;letter-spacing:-3px;color:#e7e7e7;transition:.2s all; }
.favthings-staff-1:hover .favthings-staff-2 { margin-top:-79px; }
.favthings-staff-3 { text-shadow:none;position:absolute;font:bold 10px Roboto;line-height:10px;padding:7px;border-radius:2px;background-color:#e7e7e7;color:#333333;mix-blend-mode:lighten;margin:0px 0px 0px 15px;text-transform:uppercase;letter-spacing:.5px;transition:.2s all; }
.favthings-staff-1:hover .favthings-staff-3 { margin-top:-39px; }

.favthings-quick { display:flex;padding:10px 20px;position:absolute;z-index:1;opacity:0;margin-top:25px;pointer-events:none;transition:.4s all; }
.favthings-quick div { background-color:#333333;border-radius:15px;margin-right:10px;height:136px;border:solid 2px #eeeeee;width:92px;display:flex;flex-direction:column;justify-content:center;text-align:center;color:#eeeeee;font:bold 10px Roboto;line-height:10px;text-transform:uppercase;box-shadow:2px 2px 10px rgba(33,33,33,.065);transform:scale(1);transition:.2s all; }
.favthings-quick div:hover { transform:scale(1.1); }
.favthings-quick div i::before { display:block;margin-bottom:10px;font-size:35px;line-height:35px;background:linear-gradient(to bottom right,#347DAE,#DCBB9D);-webkit-background-clip: text;-webkit-text-fill-color: transparent; }

.favthings-cred { border:solid 3px #eeeeee;padding:27px;height:100px;background-color:#e7e7e7;border-radius:10px;width:350px;font:12px Roboto;color:#333333;line-height:17px;letter-spacing:.4px;text-align:justify;box-shadow:2px 2px 10px rgba(33,33,33,.065);text-shadow:none;margin-top:-25px;opacity:0;pointer-events:none;transition:.4s all; }
.favthings-cred b { color:#6197BA; }

#favthings-tab1:checked ~ .favthings-benner-ad { opacity:1;margin-left:0px;pointer-events:auto; }
#favthings-tab1:checked ~ .favthings-benner-affs { opacity:1;margin-left:515px;pointer-events:auto; }
#favthings-tab1:checked ~ #FT1 { opacity:1;margin-left:0px;transition-delay: .3s; }
#favthings-tab2:checked ~ .favthings-staff { transform:scale(1);opacity:1;pointer-events:auto; }
#favthings-tab2:checked ~ #FT2 { opacity:1;margin-left:0px;transition-delay: .3s; }
#favthings-tab3:checked ~ .favthings-quick { margin-top:0px;opacity:1;pointer-events:auto; }
#favthings-tab3:checked ~ #FT3 { opacity:1;margin-left:0px;transition-delay: .3s; }
#favthings-tab4:checked ~ .favthings-cred { margin-top:0px;opacity:1;pointer-events:auto; }
#favthings-tab4:checked ~ #FT4 { opacity:1;margin-left:0px;transition-delay: .3s; }





.favthings-title { margin:-33px -33px 0px -33px;background-color:#e9e9e9;background-image:url(https://i.ibb.co/cLg19CJ/Babbbar.png);background-blend-mode:overlay;padding:50px;border-radius:4px 4px 0px 0px;color:#333333;text-transform:uppercase; }
.favthings-title h1 { margin:0px;font:800 50px Montserrat;line-height:40px;letter-spacing:-2px;color:#eeeeee;text-shadow:2px 2px 5px rgba(31,31,31,.065); }
.favthings-title h2 { margin:0px;font:bold 12px Roboto;line-height:10px;letter-spacing:1px;padding-top:10px;padding-left:3px; }
.favthings-nav-tree { margin:0px -33px 33px -33px;background-color:#393939;height:40px;padding:0px 35px; }
.favthings-nav-tree ul { transform:skew(-20deg);margin-block-start:0px;margin-block-end:0px;padding-inline-start:0px;letter-spacing:1px; }
.favthings-nav-tree li { display:block;text-align:left;float:left;background-color:#3f3f3f;margin-right:0px;font:bold 10px Roboto;line-height:40px;height:40px;text-transform:uppercase;transition:.2s all; }
.favthings-nav-tree li div { transform:skew(20deg); }
.favthings-nav-tree li div a { padding:15px 20px;text-shadow:none;color:#999999;transition:.2s all; }
.favthings-nav-tree li div a:hover { color:#eeeeee; }
.favthings-nav-tree li:nth-child(1) { background-color:#6197BA!important; }
.favthings-nav-tree li:nth-child(1):hover { background-color:#347DAE!important; }
.favthings-nav-tree li:nth-child(even) { background-color:#393939!important; }
.favthings-nav-tree li:nth-child(1) a { color:#eeeeee!important; }



.favthings-cat { display:flex;gap:20px; }
.favthings-cat-left { background:linear-gradient(to top right,#6197BA,#DCBB9D);border-radius:10px;width:45px;padding:50px;min-height:440px;color:#eeeeee;display:flex;flex-direction:column;justify-content:flex-end; }
.favthings-cat-left div { height:0px;width:0px;transform:rotate(-90deg);white-space:nowrap;margin-top:0px;text-transform:uppercase;mix-blend-mode:lighten; }
.favthings-cat-left div h1 { margin:0px;font:800 35px Montserrat;line-height:25px;padding-bottom:10px; }
.favthings-cat-left div h2 { font:800 7px Montserrat;padding:5px;line-height:7px;letter-spacing:2px;margin:0px;background-color:#eeeeee;color:#333333;display:inline-block;border-radius:5px; }
.favthings-cat-right { width:935px;display:grid;grid-template-columns:auto auto;gap:20px; }

.favthings-bored { background-color:#e9e9e9;padding:15px;border-radius:10px;border:solid 2px #f9f9f9;box-shadow:2px 2px 5px rgba(31,31,31,.065);position:relative;overflow:hidden; }
.favthings-bored-1 { background-color:#6197BA;border-radius:5px;display:grid;grid-template-columns:61px auto; }
.favthings-bored-left { background-color:#333333;border-radius:5px 0px 0px 5px;display:flex;flex-direction:column;justify-content:flex-end;padding-bottom:60px;overflow:visible; }
.favthings-bored-left div { transform:rotate(-90deg);height:10px;padding:10px;background-color:#393939;border-radius:3px;width:100px;text-align:center;margin:100px 0px 0px -29px;white-space:nowrap;font:800 10px Roboto;line-height:10px;color:#eeeeee;text-transform:uppercase;letter-spacing:2px; }
.favthings-bored-right { margin-top:100px;background-color:#eeeeee;padding:35px;border-radius:0px 0px 5px 0px; }
.favthings-bored-icon { position:absolute;height:70px;width:70px;padding:10px;background-color:#333333;border-radius:100%;margin:-100px 0px 0px 165px;z-index:10; }
.favthings-bored-icon img { height:70px;width:70px;border-radius:100%;filter:grayscale(100%) contrast(85%);mix-blend-mode:lighten; }
.favthings-bored-name { font:800 30px Montserrat;line-height:20px;height:40px;display:flex;align-items:flex-end;padding-bottom:20px; }
.favthings-bored-name a { font:800 30px Montserrat;line-height:20px;color:#6197BA;text-shadow:none; }
.favthings-bored-desc { font:12px Roboto;line-height:15px;text-align:justify;letter-spacing:.5px;height:105px;overflow:auto;padding-right:15px; }
.favthings-bored-desc img { position:absolute;height:100px;width:315px;margin:-195px 0px 0px -35px;border-radius:0px 5px 0px 0px;mix-blend-mode:multiply; }
.favthings-bored-last { padding:20px 0px 35px 0px;text-transform:uppercase;font:bold 10px Roboto;line-height:10px;height:25px; }
.favthings-bored-last a { font:bold 10px Roboto;line-height:10px;text-shadow:none;color:#6197BA; }
.favthings-bored-last div { float:left;margin-right:15px;background-color:#6197BA;border-radius:5px;height:35px;width:35px; }
.favthings-bored-last div i::before { display:block;font-size:15px;line-height:35px;width:35px;text-align:center;color:#eeeeee; }
.favthings-bored-last h1 { margin:0px; padding:4px 0px;font:bold 12px Roboto;line-height:12px; }
.favthings-bored-last h1 a { font:bold 12px Roboto;line-height:12px;text-shadow:none; }
.favthings-bored-subs { display:flex;flex-wrap:wrap;gap:3px;text-transform:uppercase;letter-spacing:1px;height:85px; }
.favthings-bored-subs div { background-color:#6197BA;font:bold 10px Roboto;line-height:10px;color:#eeeeee;padding:8px;border-radius:3px; }
</style>

  
  
  
  

</head>

<body translate="no" >
  <body>
<div class="favthings-grad"></div>
<div class="favthings-nav"><div class="favthings-navv"></div><div class="favthings-nav-0">
<div class="favthings-nav-left">
  
  <a href="" title="CLICK FOR QUICK LINKS"><div class="favthings-tog"><div><i class="th th-dial"></i></div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-home"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-loupe"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-users"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-5"></div>
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-code"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-5"></div>
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-id-card-2"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-5"></div>
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-envelope"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-list"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-pencil"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <a href=""><div class="favthings-nav-1">
    <div class="favthings-nav-2">
    <div class="favthings-nav-3"><i class="th th-discord"></i></div>
    <div class="favthings-nav-4"></div>
  </div></div></a>
  
  <div class="favthings-nav-right">
    <a href=""><div><i class="th th-chevron-up"></i>BACK TO TOP</div></a>
    Eto , <b>Xatspace</b><br>
    Sen Takatsuki <a></a> <a> - 隻眼の梟</a> 
  </div>
  
</div>
</div></div>
<div class="favthings-banner"><center>
  <div class="favthings-banner-imgg"></div>
  <div class="favthings-banner-grad"></div>
  <div class="favthings-banner-color"><div></div></div>
  
  <div class="favthings-banner-centering">
  <div class="favthings-banner-icon"><div class="favthings-banner-icon-1"><div class="favthings-banner-icon-2"><img src="https://i.ibb.co/Prmzp9d/847caa60fc31d053b8af6a289f381042-4164209119373489320.png"></div></div></div>
  <div class="favthings-banner-user">
    welcome,<br>guest!</div>
  <div class="favthings-banner-name"><div>ETO</div>XATSPACE</div>
  <div class="favthings-banner-name-2"><div>INSTAGRAM, TUMBLR. <br>   芳村 エト @shiissue</div></div>
  <div class="favthings-updates">
    
    <div class="favthings-updates-1"><div>
      <h1><b class="favthings-updates-2">00.01</b> 芳村 エト</h1>
      How weak is the mind when it wants to forget. Maybe you didn't forget. Maybe you lie to me Is it a lie that you tell everyone around you, or maybe a lie that you tell yourself?
      </div></div>
    
    <div class="favthings-updates-1"><div>
      <h1><b class="favthings-updates-2">00.02</b> 芳村 愛支</h1>
      You don't need a name. You can be happy without one. We are monsters without names after all.
      </div></div>
    
  </div></div>
  
  <div class="favthings-banner-img"></div>
</center></div>
<div class="favthings-benner-image"><div class="favthings-benner-img"><div></div></div></div>
<div class="favthings-benner"><div class="favthings-benner-imgg"></div><div class="favthings-benner-0">
  <div class="favthings-benner-right"><div></div>
    <h1><span>01</span></h1>
    <h1 style="margin:58px 0px 0px -55px;"><span>02</span></h1>
    <h1 style="margin:102px 0px 0px -55px;"><span>03</span></h1>
    <h1 style="margin:146px 0px 0px -55px;"><span>04</span></h1>
  </div>
  
  
  
  <input type="radio" id="favthings-tab1" name="favthings-tab" checked>
  <label for="favthings-tab1" title="ADS"></label>
  <input type="radio" id="favthings-tab2" name="favthings-tab">
  <label for="favthings-tab2" title="STAFF" style="margin:40px 0px 0px 680px;"></label>
  <input type="radio" id="favthings-tab3" name="favthings-tab">
  <label for="favthings-tab3" title="LINKS" style="margin:84px 0px 0px 664px;"></label>
  <input type="radio" id="favthings-tab4" name="favthings-tab">
  <label for="favthings-tab4" title="CREDITS" style="margin:128px 0px 0px 648px;"></label>
  
  
  
  <div class="favthings-benner-num" id="FT1">01</div><div class="favthings-benner-num" id="FT2">02</div><div class="favthings-benner-num" id="FT3">03</div><div class="favthings-benner-num" id="FT4">04</div>
  
  <div class="favthings-benner-ad"><div class="favthings-benner-ad-1"><div class="favthings-benner-ad-2"><div>
    <img src="https://i.ibb.co/cwY6ZzN/DWDBann.png">
    </div></div>
    <a href="LINK TO SITE">
      <div class="favthings-benner-ad-3"><h1>
      a something rp
      </h1><div>
      Never trust someone too much, remember that the devil was an angel before.
      </div></div></a><div class="favthings-benner-ad-4">      
      The surest way to be loved by someone is to look at their past and their pain and gently reach out to them.<br><br>
       
    </div></div></div>
  
  <div class="favthings-benner-affs">
    <div><img src="https://i.postimg.cc/8c1cvq8k/vKVfwN.png"></div>
    <div><img src="https://i.postimg.cc/8c1cvq8k/vKVfwN.png"></div>
    <div><img src="https://i.postimg.cc/8c1cvq8k/vKVfwN.png"></div>
    <div><img src="https://i.postimg.cc/8c1cvq8k/vKVfwN.png"></div>
  </div>
  
  <div class="favthings-staff">
    <a href=""><div class="favthings-staff-1"><div class="favthings-staff-img"><img src="https://i.ibb.co/chZ9RHh/Fav-Things-Staff1.png"></div><div class="favthings-staff-2">H</div><div class="favthings-staff-3">space</div></div></a>
    <a href=""><div class="favthings-staff-1" id="FVSE"><div class="favthings-staff-img"><img src="https://i.ibb.co/b2k6DJR/Fav-Things-Staff3.png"></div><div class="favthings-staff-2">N</div><div class="favthings-staff-3">space</div></div></a>
    <a href=""><div class="favthings-staff-1" id="FVSO"><div class="favthings-staff-img"><img src="https://i.ibb.co/bL7PJtC/Fav-Things-Staff4.png"></div><div class="favthings-staff-2">G</div><div class="favthings-staff-3">space</div></div></a>
    <a href=""><div class="favthings-staff-1" id="FVSE"><div class="favthings-staff-img"><img src="https://i.ibb.co/pjVWqr9/Fav-Things-Staff2.png"></div><div class="favthings-staff-2">K</div><div class="favthings-staff-3">space</div></div></a>
    <a href=""><div class="favthings-staff-1"><div class="favthings-staff-img"><img src="https://i.ibb.co/0t88h4p/Fav-Things-Staff5.png"></div><div class="favthings-staff-2">N</div><div class="favthings-staff-3">space</div></div></a>
  </div>
  
  <div class="favthings-quick">
    <a href=""><div><i class="th th-agenda-1"></i>Instagram</div></a>
    <a href=""><div><i class="th th-hashtag"></i>Tumblr</div></a>
    <a href=""><div><i class="th th-flag-1"></i>help</div></a>
    <a href=""><div><i class="th th-credit-card"></i>store</div></a>
    <a href=""><div><i class="th th-bookmark-1"></i>directory</div></a>
    <a href=""><div><i class="th th-heart-1"></i>Eto</div></a>
  </div>
  
  <div class="favthings-cred">
   <iframe width="350" height="90" src="https://www.youtube-nocookie.com/embed/wP1_iGNlXL8?controls=0&amp;autoplay" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  
  
  
  

</body>

</html>
