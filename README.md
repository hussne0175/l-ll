# l-ll
ccc;
.vertical-align {
  top: 50%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
}
.horizontal-align {
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
}
.vert-wrapper {
  display: table;
  width: 100%;
  height: 100%;
}
.vert-wrapper .vert {
  display: table-cell;
  height: 100%;
  vertical-align: middle;
}


/*
* General Styles
*/
body {
  color: #2e2e2e;
  font-family: 'Noto Kufi Arabic','Hind Guntur', sans-serif;
  font-size: 16px;
  background-color: #ffffff;
}
body.light {
  background-color: #ffffff;
}
body.light .content-wrapper {
  background-color: #fbfdfe;
}
body.dark {
  background-color: #242424;
  overflow-y: scroll;
  overflow-x: hidden;
}
body.dark .content-wrapper {
  background-color: #343434;
}

body::-webkit-scrollbar {
  width: 0.2em;
}

body::-webkit-scrollbar-track {
  -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3);
}

body::-webkit-scrollbar-thumb {
  background-color: #a92334;
  outline: 1px solid slategrey;
}


.scroll {
  background-color: #242424;
  overflow-y: scroll;
  overflow-x: hidden;
}
.scroll.dark .content-wrapper {
  background-color: #343434;
}

.scroll::-webkit-scrollbar {
  width: 0.2em;
}

.scroll::-webkit-scrollbar-track {
  -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3);
}

.scroll::-webkit-scrollbar-thumb {

  background-color: #a92334;
  outline: 1px solid slategrey;
}


.logo {
  width: 44px;
  height: 44px;
}
a {
  color: #2e2e2e;
}
a:hover {
  color: #ea2c5a;
  text-decoration: none;
}
a:focus {
  color: #ea2c5a;
}
.form-control,
.btn {
  font-size: 16px;
}
.form-control {
  border-radius: 3px;
  border: solid 1px #e0e1e2;
  padding: 15px 18px;
  height: 46px;
}
.form-group {
  margin-bottom: 25px;
}
label {
  margin-bottom: 10px;
}
.color-default {
  color: #2e2e2e;
}
.color-active {
  color: #ea2c5a;
}

.active {
  color: #c6d4ce;
}
.padding-def {
  padding: 10px 0;
}
.delimiter {
  margin: 23px 0;
  height: 1px;
  border-top: solid 1px #eceff0;
}
.bg-clean .btn-default {
  border: none;
  background: transparent;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn:active,
.btn.active {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-default {
  color: #637076;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-default:hover,
.btn-default:active,
.btn-default.active,
.btn-default:focus,
.btn-default.focus,
.open > .dropdown-toggle.btn-default {
  color: #637076;
  background-color: transparent;
  border-color: transparent;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #637076;
  background-color: transparent;
  border-color: transparent;
}
.pull-right > .dropdown-menu {
  right: -1px;
}
ul.dropdown-menu {
  border-color: #eceff0;
  border-radius: 0px;
  -webkit-box-shadow: none;
  box-shadow: none;
  padding: 0;
  margin: 0;
}
ul.dropdown-menu li {
  border-bottom: solid 1px #eceff0;
}
ul.dropdown-menu li a {
  padding: 14px 16px;
}
ul.dropdown-menu li a i {
  padding-right: 5px;
  font-size: 19px;
}
ul.dropdown-menu li:last-child {
  border: none;
}
ul.dropdown-menu li:nth-child(even) {
  background-color: #fbfdfe;
}
.tooltip-inner {
  background-color: #44474e;
  font-family: 'Hind Guntur', sans-serif;
  font-size: 14px;
  padding: 5px 9px 1px 9px;
}
.tooltip.top .tooltip-arrow {
  border-top-color: #44474e;
}
.ta-r {
  text-align: right;
}
a.active {
  color: #ea2c5a;
}
.head-div {
  border-top: solid 1px #eceff0;
}
.btn-cv1 {
  border-radius: 3px;
  border: solid 1px #ea2c5a;
  background-color: #ea2c5a;
  color: #ffffff;
  font-size: 18px;
  font-weight: 500;
  padding: 20px;
  width: 100%;
}
.btn-cv1:hover {
  color: #ea2c5a;
  background-color: #ffffff;
}
/*
* General Styles END
*/
.col-xs-1-5,
.col-sm-1-5,
.col-md-1-5,
.col-lg-1-5 {
  position: relative;
  min-height: 1px;
  padding-right: 10px;
  padding-left: 10px;
}
.col-xs-1-5 {
  width: 20%;
  float: left;
}
@media (min-width: 768px) {
  .col-sm-1-5 {
    width: 20%;
    float: left;
  }
}
@media (min-width: 992px) {
  .col-md-1-5 {
    width: 20%;
    float: left;
  }
}
@media (min-width: 1200px) {
  .col-lg-1-5 {
    width: 20%;
    float: left;
  }
}
input[type="text"],
input[type="email"],
input[type="number"],
input[type="search"],
textarea,
label.checkbox {
  border: solid 1px #e0e1e2;
  border-radius: 2px;
}
input[type="text"],
input[type="email"],
input[type="number"],
input[type="search"],
textarea {
  width: 100%;
  padding-left: 14px;
  padding-right: 14px;
  color: #7e7e7e;
  font-size: 16px;
  font-weight: normal;
  -webkit-transition: border 0.3s;
  -moz-transition: border 0.3s;
  -ms-transition: border 0.3s;
  -o-transition: border 0.3s;
}
input[type="text"]:focus,
input[type="email"]:focus,
input[type="number"]:focus,
input[type="search"]:focus,
textarea:focus {
  outline: none;
  border-color: #b5b5b5;
}
input[type="text"][readonly]:focus,
input[type="email"][readonly]:focus,
input[type="number"][readonly]:focus,
input[type="search"][readonly]:focus,
textarea[readonly]:focus {
  outline: none;
  border-color: #e0e1e2;
}
textarea {
  padding-top: 10px;
}
input[type="text"],
input[type="email"],
input[type="number"],
input[type="search"] {
  height: 40px;
  padding-top: 4px;
}
label.checkbox {
  position: relative;
  width: 20px;
  height: 20px;
  cursor: pointer;
  background-color: #ffffff;
}
label.checkbox .arrow {
  display: none;
  position: absolute;
  width: 20px;
  height: 20px;
  left: 0;
  top: 0;
  border: solid 1px #ea2c5a;
  border-radius: 2px;
}
label.checkbox .arrow::before {
  content: '';
  display: block;
  position: absolute;
  width: 12px;
  height: 8px;
  left: 3px;
  top: 3px;
  border-top: solid 2px #ea2c5a;
  border-right: solid 2px #ea2c5a;
  -webkit-transform: rotate(135deg);
  -moz-transform: rotate(135deg);
  -ms-transform: rotate(135deg);
  -o-transform: rotate(135deg);
}
label.checkbox input[type="checkbox"]:checked + .arrow {
  display: block;
}
label.checkbox input[type="checkbox"] {
  display: none;
}
label.clipboard {
  position: relative;
  width: 100%;
}
label.clipboard .btn-copy {
  position: absolute;
  display: block;
  width: 56px;
  height: 28px;
  padding-top: 5px;
  top: 50%;
  right: 6px;
  margin-top: -14px;
  border-radius: 2px;
  text-align: center;
  background-color: #eceff0;
  color: #7e7e7e;
  font-weight: normal;
  cursor: pointer;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -ms-transition: 0.3s;
  -o-transition: 0.3s;
}
label.clipboard:hover .btn-copy {
  background-color: #b5b5b5;
  color: white;
}
.login-window input {
  height: 46px;
  padding-top: 18px;
}
.login-window button {
  padding-top: 22px;
  padding-bottom: 16px;
}
input:focus,
select:focus,
textarea:focus {
  -webkit-box-shadow: none !important;
  moz-box-shadow: none !important;
  box-shadow: none !important;
  outline: none !important;
}
label.checkbox-text {
  position: relative;
  display: block;
  overflow: hidden;
  padding-left: 36px;
}
label.checkbox-text .checkbox {
  position: absolute;
  left: 0;
}
label.checkbox-text p {
  margin-top: 12px;
  margin-bottom: 6px;
  font-weight: normal;
}
.cv-percent {
  color: #28b47e;
  display: inline-block;
  position: relative;
  padding-left: 19px;
}
.cv-percent .cv-circle {
  border: solid 2px #28b47e;
  border-radius: 7px;
  width: 14px;
  height: 14px;
  display: inline-block;
  position: absolute;
  top: 1px;
  left: 0px;
}
ul.list-inline li a:not(.color-active) {
  color: #7e7e7e;
}
ul.list-inline li a:not(.color-active):hover {
  color: #2e2e2e;
}
ul.list-inline li a.color-active {
  color: #ea2c5a;
}

ul.list-inline li a:hover {
  background: radial-gradient(ellipse at top,#A53A35,#55160C 89%,#631609);
}
.social {
  overflow: hidden;
}
.social a {
  display: block;
  float: left;
  width: 30px;
  height: 30px;
  padding-top: 6px;
  margin-bottom: 8px;
  border-radius: 50%;
  color: white;
  text-align: center;
}
.social a:not(:last-child) {
  margin-right: 14px;
}
.social a:hover {
  transform: rotateY(360deg);
  -webkit-transition: 1s;
  -moz-transition: 1s;
  -ms-transition: 1s;
  -o-transition: 1s;
}
.social a.facebook {
  background-color: #3b5998;
  padding-top: 7px;
}
.social a.twitter {
  background-color: #55acee;
  padding-top: 7px;
}
.social a.google {
  background-color: #dd4b39;
  padding-top: 7px;
}
.social a.pinterest {
  background-color: #cb2027;
  padding-top: 7px;
}
.social a.btc {
  background-color: #ff6600;
}
.social a.tumblr {
  background-color: #32506d;
  padding-top: 7px;
}
.social a.vk {
  background-color: #45668e;
}
.social a.reddit {
  background-color: white;
  color: #5f99cf;
  font-size: 30px;
  padding-top: 0;
}
.social a.stumbleupon {
  background-color: #eb4924;
}
.social a.odnoklassniki {
  background-color: #ed812b;
}
.tags-type1,
.tags-type2 {
  fond-size: 0;
  display: table;
}
.tags-type1 a,
.tags-type2 a {
  display: inline-block;
  margin-bottom: 8px;
  color: #7e7e7e;
  background-color: white;
  border: solid 1px #e0e1e2;
  border-radius: 2px;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -ms-transition: 0.3s;
  -o-transition: 0.3s;
}
.tags-type1 a:hover,
.tags-type2 a:hover {
  background-color: #eceff0;
}
.tags-type1 a:not(:last-child),
.tags-type2 a:not(:last-child) {
  margin-right: 16px;
}
.tags-type1 a {
  height: 34px;
  padding: 8px 8px 8px;
  font-size: 16px;
}
.tags-type2 a {
  height: 46px;
  padding: 12px 16px 12px;
  font-size: 20px;
  font-weight: 500;
}
.tags-type2 a i {
  margin-right: 14px;
}
.block-list > div {
  min-height: 48px;
  padding: 14px 18px 10px;
  border: solid 1px #e0e1e2;
  cursor: pointer;
  overflow: hidden;
}
.block-list > div:hover:not(.active) {
  border-color: #b5b5b5;
}
.block-list > div:not(:last-child):not(.active) {
  margin-bottom: -1px;
}
.block-list > div span {
  display: block;
  color: #7e7e7e;
}
.block-list > div .name {
  float: left;
}
.block-list > div .time {
  float: right;
}
.block-list > div i {
  display: block;
  float: left;
  margin-top: -2px;
  color: #637076;
  font-size: 20px;
}
.block-list > div i:first-child {
  margin-left: -6px;
  margin-right: 10px;
}
.block-list > div i.cvicon-cv-plus {
  float: right;
}
.block-list > div.active {
  border-color: #ea2c5a;
}
.block-list > div.active span {
  font-weight: 500;
  color: black;
}
.block-list > div.active i {
  color: #ea2c5a;
}
/*video {*/
  /*display: block;*/
  /*width: 100%;*/
  /*object-fit: cover;*/
/*}*/
.sv-video {
  width: 100%;
}
.sv-video .sv-play {
  cursor: pointer;
}
.sv-video .mejs-container .mejs-inner .mejs-layers .mejs-poster {
  background-size: cover;
}
.sv-video .mejs-container .mejs-inner .mejs-controls .mejs-time-rail .mejs-time-total .mejs-time-loaded {
  background: #4d86fe;
  background: rgba(77, 134, 254, 0.8);
  background: -webkit-gradient(linear, 0 0, 0 100%, from(rgba(44, 124, 145, 0.8)), to(rgba(77, 134, 254, 0.8)));
  background: -webkit-linear-gradient(top, rgba(44, 124, 145, 0.8), rgba(77, 134, 254, 0.8));
  background: -moz-linear-gradient(top, rgba(44, 124, 145, 0.8), rgba(77, 134, 254, 0.8));
  background: -o-linear-gradient(top, rgba(44, 124, 145, 0.8), rgba(77, 134, 254, 0.8));
  background: -ms-linear-gradient(top, rgba(44, 124, 145, 0.8), rgba(77, 134, 254, 0.8));
  background: linear-gradient(rgba(44, 124, 145, 0.8), rgba(77, 134, 254, 0.8));
}
.mejs-overlay-button {
  background-image: none;
}
.mejs-overlay-button:after {
  top: 0;
  left: 0;
  content: '\e816';
  font-family: "circle-video";
  width: 66px;
  height: 66px;
  background-color: #343434;
  border-radius: 33px;
  opacity: 0.85;
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -33px;
  margin-left: -33px;
  color: #ffffff;
  padding-top: 18px;
  font-size: 20px;
  text-align: center;
}
.login-window div.checkbox > label {
  padding-left: 40px;
}
.login-window label.checkbox {
  position: absolute;
  margin-left: -40px;
}
.u-form div.checkbox label.checkbox {
  position: absolute;
  margin-left: -36px;
  margin-top: -3px;
  padding: 0 !important;
}
.u-form div.checkbox.checked label {
  color: #ea2c5a !important;
}
.form-group input,
.form-group select {
  height: 46px;
}
.video-responsive {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
}
.video-responsive iframe,
.video-responsive object,
.video-responsive embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
/*
* HEADER
*/
.btn-color-toggle {
  position: fixed;
  left: 30px;
  top: 24px;
  cursor: pointer;
  z-index: 100;
  display:none;
}
@media only screen and (max-width: 1080px) {
  .btn-color-toggle {
    left: inherit;
    right: 30px;
    top: 100px;
  }
}
@media only screen and (max-width: 767px) {
  .btn-color-toggle {
    left: inherit;
    right: 30px;
    top: 24px;
  }
}
@media only screen and (max-width: 356px) {
  .btn-color-toggle {
    left: inherit;
    right: 8px;
    top: 24px;
  }
}
.menu {
  margin-top: 25px;
}
ul.menu {
  margin-bottom: 0;
}
.topsearch {
  margin-top: 15px;
}
.topsearch .form-control {
  height: 40px;
  padding: 6px 12px;
  padding-top: 10px;
}
.topsearch .input-group-addon,
.topsearch .input-group-btn,
.topsearch input {
  border: none;
  background-color: #eceff0;
}
.topsearch .input-group-addon {
  border-top-left-radius: 20px;
  border-bottom-left-radius: 20px;
}
.topsearch .input-group-addon i {
  font-size: 18px;
  padding-left: 3px;
  padding-top: 3px;
  color: #637076;
}
.topsearch input {
  box-shadow: inset 0px 0px 0px 0px white;
  padding-top: 10px;
  width: 455px;
}
.topsearch .input-group-btn {
  border-top-right-radius: 20px;
  border-bottom-right-radius: 20px;
  padding-right: 10px;
}
.topsearch .input-group-btn .btn {
  padding: 8px 12px 4px 12px;
}
.topsearch .input-group-btn .btn-default {
  color: #637076;
  background-color: transparent;
  border: none;
}
.topsearch .input-group-btn .cvicon-cv-video-file {
  font-size: 20px;
}
.topsearch .input-group-btn .caret {
  margin-top: -5px;
}
.avatar {
  width: 70px;
  padding-top: 12px;
  margin-left: 14px;
  position: relative;
}
.avatar .status {
  position: absolute;
  top: 12px;
  left: 0px;
  background-color: #28b47e;
  display: block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.selectuser {
  padding-left: 0px;
  padding-top: 20px;
}
.selectuser .btn-default {
  background-color: transparent;
  border: none;
}
.selectuser .btn .caret {
  margin-left: 5px;
}
.loginsignup {
  text-align: right;
  margin-top: 25px;
}
.loginsignup a {
  color: #637076;
}
.loginsignup a:hover {
  text-decoration: underline;
}
.navbar-container {
  height: 70px;
  border-bottom: solid 1px #eceff0;
}
.navbar-container .navbar-brand {
  padding-top: 13px;
  padding-left: 0;
}
.navbar-container .input-group input.form-control {
  width: 455px;
}
.navbar-container .container {
  position: relative;
}
.navbar-container .container .upload-button {
  z-index: 10;
  position: absolute;
  width: 55px;
  height: 55px;
  border-radius: 50%;
  border: solid 1px #2cce8f;
  top: 40px;
  right: -100px;
  background-color: #2cce8f;
  color: #ffffff;
  text-align: center;
  -webkit-box-shadow: 2px 2px 10px 0px rgba(44, 206, 143, 0.56);
  -moz-box-shadow: 2px 2px 10px 0px rgba(44, 206, 143, 0.56);
  box-shadow: 2px 2px 10px 0px rgba(44, 206, 143, 0.56);
}
.navbar-container .container .upload-button:hover {
  background-color: #ffffff;
  color: #2cce8f;
}
.navbar-container .container .upload-button a {
  color: #ffffff;
}
.navbar-container .container .upload-button a:hover {
  color: #2cce8f;
}
.navbar-container .container .upload-button i {
  padding-top: 15px;
  font-size: 20px;
}
@media (min-width: 1024px) and (max-width: 1440px) {
  .navbar-container .container .upload-button {
    right: -50px;
  }
}
.navbar-container2 {
  height: 50px;
  border-bottom: solid 1px #eceff0;
  color: #637076;
}
.navbar-container2 a i {
  color: #637076;
}
.navbar-container2 a i:hover {
  color: #ea2c5a;
}
.navbar-container2 .goto {
  padding-top: 14px;
  color: #7e7e7e;
}
.navbar-container2 .h-icons {
  padding-top: 14px;
}
.navbar-container2 .h-icons i {
  margin-right: 18px;
  font-size: 20px;
}
.navbar-container2 .h-resume {
  position: relative;
  padding-left: 55px;
  padding-top: 15px;
}
.navbar-container2 .h-resume .play-icon {
  position: absolute;
  font-size: 22px;
  left: 8px;
  top: 13px;
}
.navbar-container2 .h-grid {
  padding-top: 14px;
  font-size: 20px;
}
.navbar-container2 .h-grid .cvicon-cv-grid-view {
  padding-right: 5px;
}
.pages ul.dropdown-menu li:nth-child(even) {
  background-color: #ffffff;
}
.pages a:focus {
  color: #ea2c5a;
  text-decoration: none;
}
@media (min-width: 768px) and (max-width: 1365px) {
  .navbar-container {
    height: auto;
    padding-bottom: 15px;
  }
  .navbar-container .input-group input.form-control {
    width: 100%;
  }
  .navbar-container .container .upload-button {
    top: 15px;
    right: 15px;
  }
  .navbar-container2 {
    height: auto;
    padding-bottom: 6px;
  }
}
@media (min-width: 100px) and (max-width: 767px) {
  .navbar-container {
    height: auto;
    padding-bottom: 15px;
  }
  .navbar-container .input-group input.form-control {
    width: 100%;
  }
  .navbar-container .container .upload-button {
    top: 165px;
    right: 15px;
  }
  .navbar-container2 {
    height: auto;
    padding-bottom: 15px;
  }
}
/*
* HEADER END
*/
/*
* Content Index
*/
.content-wrapper {
  background-color: #fbfdfe;
}
.content-block .cb-header {
  padding: 20px 0;
  color: #7e7e7e;
}
.content-block .cb-header .list-inline {
  margin: 0;
  margin-left: -5px;
  line-height: 34px;
}
.content-block .cb-content {
  margin-bottom: 25px;
}
.content-block.head-div {
  border-top: solid 1px #eceff0;
}
.avatars img {
  border-radius: 31px;
}
.avatars .col-lg-1 {
  position: relative;
}
.avatars .col-lg-1 .note {
  position: absolute;
  width: 70px;
  height: 62px;
  border-radius: 31px;
  left: 15px;
  top: 0px;
  background-color: #ea2c5a;
  opacity: 0.9;
  color: #ffffff;
  text-align: center;
  padding-top: 22px;
  font-size: 18px;
  font-weight: 500;
  display: none;
}
.b-video .v-img {
  border-radius: 2px;
  position: relative;
}
.b-video .v-img .time {
  position: absolute;
  bottom: 0;
  right: 0;
  background-color: #373933;
  border-bottom-right-radius: 2px;
  border-top-left-radius: 2px;
  color: #ffffff;
  font-size: 14px;
  padding: 6px 9px 1px 9px;
  line-height: 14px;
  font-weight: 500;
}
.b-video .v-img .watched {
  position: absolute;
  top: 5px;
  left: 5px;
  padding: 6px 6px 6px 6px;
  color: #ffffff;
  font-size: 13px;
  line-height: 13px;
  font-weight: 500;
  border-radius: 2px;
  background-color: #373933;
}
.b-video .v-img .watched-mask {
  background-color: #ababab;
  opacity: 0.6;
  border-radius: 2px;
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0px;
  left: 0px;
}
.b-video .v-img .plus {
  width: 24px;
  height: 24px;
  border-radius: 3px;
  background-color: #ffffff;
  opacity: 0.9;
  position: absolute;
  top: 5px;
  right: 5px;
  cursor: pointer;
  text-align: center;
}
.b-video .v-img .plus i {
  padding-top: 4px;
  display: inline-block;
}
.b-video .v-img .plus-details {
  position: absolute;
  top: 5px;
  right: 34px;
  border-radius: 3px;
  background-color: #ffffff;
  opacity: 0.9;
  text-align: left;
}
.b-video .v-img .plus-details ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
.b-video .v-img .plus-details ul li {
  padding: 14px 16px;
  border-bottom: solid 1px #eceff0;
}
.b-video .v-img .plus-details ul li:last-child {
  border: none;
}
.b-video .v-img .plus-details ul li i {
  padding-right: 10px;
}
.b-video .v-desc {
  color: #343434;
  font-weight: 500;
  padding-top: 25px;
  font-size: 13px;
}
.b-video .v-views {
  font-size: 15px;
  color: #7e7e7e;
  padding-bottom: 40px;
  padding-top: 5px;
}
.b-video .v-views .v-percent {
  color: #28b47e;
  display: inline-block;
  position: relative;
  padding-left: 19px;
}
.v-percent.vc{
  border: #ea2c5a;
}
.b-video .v-views .v-percent .v-circle {
  border: solid 2px #28b47e;
  border-radius: 7px;
  width: 14px;
  height: 14px;
  display: inline-block;
  position: absolute;
  top: 1px;
  left: 0px;
}
.b-video.last-row .v-views {
  padding-bottom: 0px;
}
.b-chanel {
  position: relative;
}
.b-chanel .hover {
  position: absolute;
  display: none;
  text-align: center;
  padding-top: 80px;
  width: 100%;
  height: 100%;
  border-radius: 2px;
  background-color: #30333b;
  opacity: 0.9;
  color: #ffffff;
  top: 0;
  left: 0;
}
.b-playlist .v-img {
  border-radius: 2px;
  position: relative;
}
.b-playlist .v-img img {
  border: solid 2px #fbfdfe;
  width: 100%;
}
.b-playlist .v-img a {
  display: inline-block;
  position: relative;
  z-index: 3;
  width: 100%;
}
.b-playlist .v-img .items {
  position: absolute;
  bottom: 15px;
  right: 15px;
  background-color: #373933;
  border-radius: 2px;
  color: #ffffff;
  font-size: 14px;
  padding: 6px 9px 1px 9px;
  line-height: 14px;
  font-weight: 500;
  z-index: 5;
}
.b-playlist .v-img .l-1 {
  z-index: 1;
  position: absolute;
  width: 92%;
  left: 4%;
}
.b-playlist .v-img .l-2 {
  z-index: 2;
  position: absolute;
  margin-top: 11px;
  width: 96%;
  left: 2%;
}
.b-playlist .v-img .l-3 {
  z-index: 3;
  margin-top: 22px;
}

.related{
  width: 158px;
  height: 227px;
  -webkit-transition: width 1s ease, height 1s ease;
}
.related:hover{
  width: 180px;
  height: 250px;
}
.b-playlist .v-desc {
  color: #343434;
  font-weight: 500;
  padding-top: 25px;
}
.b-playlist .v-views {
  font-size: 15px;
  color: #7e7e7e;
  padding-bottom: 0px;
  padding-top: 5px;
}
.b-playlist .v-views .v-percent {
  color: #28b47e;
  display: inline-block;
  position: relative;
  padding-left: 19px;
}
.b-playlist .v-views .v-percent .v-circle {
  border: solid 2px #28b47e;
  border-radius: 7px;
  width: 14px;
  height: 14px;
  display: inline-block;
  position: absolute;
  top: 1px;
  left: 0px;
}
.v-pagination {
  text-align: center;
  margin-top: 45px;
  margin-bottom: 45px;
}
.v-pagination .pages {
  width: 70px;
  height: 62px;
  border-radius: 31px;
  background-color: #eceff0;
  text-align: center;
  padding-top: 22px;
  padding-left: 30px;
  color: #2e2e2e;
  font-size: 18px;
  font-weight: 500;
}
.v-pagination .pages:last-child {
  padding-left: 0;
}
.v-pagination .pages:hover {
  color: #ffffff;
  background-color: #637076;
}
.v-pagination .pages.active {
  color: #ffffff;
  background-color: #637076;
}
.v-pagination .list-inline {
  margin-left: 0px;
  padding: 0;
  margin: 0;
}
@media (min-width: 768px) and (max-width: 1365px) {
  .avatars .col-sm-2 {
    padding-bottom: 10px;
  }
  .videolist .videoitem {
    min-height: 360px;
  }
  .videolist .videoitem img {
    width: 100%;
  }
  .b-playlist {
    margin-bottom: 15px;
  }
  .b-chanel {
    margin-bottom: 15px;
  }
  .b-chanel img {
    width: 100%;
  }
  .v-pagination .pages {
    width: 62px;
    height: 62px;
  }
}
@media (min-width: 100px) and (max-width: 767px) {
  .avatars .col-sm-2 {
    padding-bottom: 10px;
  }
  .videolist .videoitem {
    min-height: 100px;
  }
  .videolist .videoitem img {
    width: 100%;
  }
  .videolist .videoitem .v-views {
    padding-bottom: 30px;
  }
  .videolist .videoitem .last-row .v-views {
    padding-bottom: 30px;
  }
  .videolist .videoitem .b-video .v-desc {
    padding-top: 10px;
  }
  .b-playlist {
    margin-bottom: 15px;
  }
  .b-chanel {
    margin-bottom: 15px;
  }
  .b-chanel img {
    width: 100%;
  }
  .v-pagination .pages {
    width: 62px;
    height: 62px;
    margin-bottom: 10px;
  }
  .padding-def {
    padding: 15px 0;
  }
  .footer-logo {
    padding-bottom: 15px;
    text-align: center;
    display:none;
  }
  footer{
    border-top: solid 1px #eceff0;
  }
  footer .navbar-brand {
    float: none;
    display: none;
  }
  footer .navbar-brand img {
    display: inline-block;
  }
  footer .f-links {
    text-align: center;
  }
  footer .f-copy {
    text-align: center;
  }
}
/*
* Content Index END
*/
/*
* Content Search
*/
.v-search {
  color: #7e7e7e;
}
.v-search a {
  color: #7e7e7e;
}
.v-search a:hover {
  color: #ea2c5a;
}
.v-search a.active {
  color: #ea2c5a;
}
.v-search .s-title {
  margin-top: 25px;
  margin-bottom: 15px;
}
.v-search .s-title i {
  font-size: 12px;
}
.v-search .s-s-title {
  color: #2e2e2e;
  font-weight: 500;
}
.v-search .s-s-title i {
  font-size: 19px;
}
.v-search ul {
  list-style: none;
  margin: 0;
  padding: 0;
  margin-left: 30px;
  margin-top: 5px;
}
.v-search .features {
  margin-left: 30px;
  margin-top: 10px;
  margin-bottom: 10px;
}
.v-search .features .feature {
  width: 42px;
  border-radius: 3px;
  border: solid 1px #7e7e7e;
  margin-right: 15px;
  float: left;
  text-align: center;
  padding: 4px 7px 0px 7px;
}
.v-search .features .feature:hover {
  border: solid 1px #ea2c5a;
  color: #ea2c5a;
}
.v-search .features .feature.active {
  border: solid 1px #ea2c5a;
  color: #ea2c5a;
}
.v-search .clearsearch {
  margin-bottom: 25px;
}
.v-search .clearsearch i {
  font-size: 10px;
}
@media (min-width: 100px) and (max-width: 1365px) {
  .search-group {
    padding-bottom: 15px;
  }
}
/*
* Content Search END
*/
/*
* Content Upload
*/
.upload-page {
  text-align: center;
  color: #7e7e7e;
}
.upload-page .u-area {
  padding-top: 150px;
  padding-bottom: 150px;
}
.upload-page .u-area i {
  font-size: 144px;
  color: #637076;
}
.upload-page .u-area .u-text1 {
  display: block;
  margin-top: 60px;
  margin-bottom: 0;
  font-size: 20px;
  color: #2e2e2e;
}
.upload-page .u-area .u-btn {
  margin-top: 60px;
  background-color: #ea2c5a;
  color: white;
  padding: 15px 65px;
  border: solid 1px #ea2c5a;
  height: 48px;
  border-radius: 24px;
  font-weight: 500;
}
.upload-page .u-area .u-btn:hover {
  color: #ea2c5a;
  background-color: #ffffff;
}
.upload-page .u-terms {
  padding: 45px 0;
}
.upload-page .u-terms a {
  color: #ea2c5a;
}
.upload-page .u-terms a:hover {
  text-decoration: underline;
}
.upload-page .u-terms p {
  margin-bottom: 7px;
}
.edit-page {
  text-align: left;
}
.edit-page .u-details-wrap {
  padding-bottom: 30px;
  margin-bottom: 30px;
  border-bottom: solid 1px #eceff0;
}
.edit-page .u-details .ud-caption {
  font-family: 'Hind', sans-serif;
  font-weight: 500;
  padding-top: 25px;
  padding-bottom: 25px;
  color: #2e2e2e;
}
.edit-page .u-details .imgplace {
  background-color: #8781bd;
  border-radius: 3px;
  width: 100%;
  height: 113px;
}
.edit-page .u-details .u-title {
  color: #2e2e2e;
  font-family: 'Hind', sans-serif;
  font-weight: 500;
  padding-bottom: 4px;
}
.edit-page .u-details .u-progress {
  position: relative;
  padding-top: 20px;
  padding-bottom: 20px;
}
.edit-page .u-details .u-progress .u-close {
  position: absolute;
  top: 2px;
  right: 21px;
}
.edit-page .u-details .u-progress .u-close i {
  font-size: 20px;
}
.edit-page .u-details .u-progress .progress {
  width: 90%;
  margin-bottom: 0;
  height: 8px;
  background-color: #eceff0;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.edit-page .u-details .u-progress .progress .progress-bar {
  background-color: #28b47e;
  font-size: 8px;
  line-height: 8px;
  border-radius: 4px;
}
.edit-page .u-form label {
  color: #2e2e2e;
  font-weight: normal;
}
.edit-page .u-form .form-control {
  padding: 6px 12px;
}
.edit-page .u-form .u-category {
  color: #2e2e2e;
  padding-bottom: 6px;
}
.edit-page .u-form input[type=checkbox] {
  height: 19px;
  width: 19px;
  margin: 0;
  margin-left: -35px;
}
.edit-page .u-form .checkbox {
  margin-bottom: 17px;
}
.edit-page .u-form .checkbox label {
  padding-left: 35px;
  color: #7e7e7e;
}
.edit-page .u-area {
  text-align: center;
  padding-top: 65px;
  padding-bottom: 20px;
}
.edit-page .u-area .u-btn {
  margin-top: 0;
}
.edit-page .u-terms {
  text-align: center;
}
@media (min-width: 100px) and (max-width: 767px) {
  .upload-page .u-area {
    padding-top: 50px;
    padding-bottom: 50px;
  }
  .upload-page .u-area .u-text1 {
    margin-top: 30px;
  }
  .upload-page .u-area .u-btn {
    margin-top: 30px;
  }
  .upload-page .u-terms {
    padding: 30px 0;
  }
}
/*
* Content Upload END
*/
/*
* Content Account
*/
.bg-image {
  text-align: center;
}
.bg-image img {
  width: 100%;
}
.login-wraper {
  position: relative;
}
.login-wraper .login-window {
  position: absolute;
  width: 570px;
  top: 50%;
  left: 50%;
  margin-left: -2px;
  margin-top: -288px;
}
.login-wraper .login-window .l-head {
  background-color: #ffffff;
  padding: 40px;
  border-bottom: solid 1px #eceff0;
  font-weight: 500;
  font-size: 22px;
  color: #343434;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
}
.login-wraper .login-window .l-form {
  text-align: left;
  background-color: #fbfdfe;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  padding: 25px 70px 70px;
}
.login-wraper .login-window .l-form label {
  font-weight: 500;
}
.login-wraper .checkbox {
  font-weight: normal;
}
.login-wraper .checkbox p {
  margin-bottom: 4px;
}
.login-wraper .checkbox .text2 {
  display: block;
  font-size: 14px;
  color: #7e7e7e;
}
.login-wraper .ortext {
  padding-top: 25px;
  color: #7e7e7e;
}
.login-wraper .signuptext {
  padding-top: 25px;
  text-align: center;
  color: #343434;
  font-weight: 500;
}
.login-wraper .forgottext {
  margin-top: 25px;
}
.login-wraper .forgottext a {
  color: #7e7e7e;
}
.login-wraper .forgottext a:hover {
  text-decoration: underline;
}
.banner-text {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -50px;
  margin-left: -580px;
  width: 550px;
}
.banner-text .line {
  height: 1px;
  border-top: solid 1px #ea2c5a;
  padding-bottom: 50px;
  width: 280px;
}
.banner-text .b-text {
  color: #ffffff;
  font-size: 80px;
  text-align: left;
  line-height: 80px;
}
.banner-text .b-text .color-b1 {
  color: #b7135d;
}
.banner-text .b-text .color-b2 {
  color: #be154e;
}
.banner-text .b-text .color-b3 {
  color: #d71d52;
}
.banner-text .overtext {
  margin-top: 30px;
  color: #a1a1a1;
  text-align: left;
}
@media (min-width: 100px) and (max-width: 1365px) {
  .banner-text {
    position: relative;
    top: 0;
    left: 0;
    margin-top: 0;
    margin-left: 0;
    width: auto;
  }
  .banner-text .line {
    display: none;
  }
  .banner-text .b-text {
    color: #000000;
    font-size: 30px;
    text-align: center;
    line-height: 30px;
    padding-top: 30px;
  }
  .banner-text .overtext {
    margin: 15px 0;
    color: #a1a1a1;
    text-align: center;
  }
  .login-wraper .login-window {
    position: relative;
    width: auto;
    top: 0;
    left: 0;
    margin-left: 0;
    margin-top: 0;
  }
  .login-wraper .login-window .l-head {
    padding: 20px 10px;
  }
  .login-wraper .login-window .l-form {
    padding: 25px 20px;
  }
}
/*
* Content Account END
*/
/*
* Content Categories
*/
.v-categories .content-block .cb-header {
  padding: 15px 0;
  margin-bottom: 30px;
  color: #7e7e7e;
  border-bottom: solid 1px #eceff0;
}
.v-categories .content-block .cb-header .list-inline {
  margin: 0;
  margin-left: -5px;
  line-height: 34px;
}
.v-categories .content-block .cb-content {
  margin-bottom: 40px;
}
.v-categories .content-block .b-category {
  border-radius: 2px;
  margin-bottom: 38px;
  overflow: hidden;
}
.v-categories .content-block .b-category.last-row {
  margin-bottom: 0;
}
.v-categories .content-block .b-category .name {
  font-weight: 500;
  margin-top: 25px;
  display: block;
}
.v-categories .content-block .b-category .desc {
  color: #7e7e7e;
  display: block;
  font-size: 15px;
  margin-top: 5px;
}
@media (min-width: 100px) and (max-width: 767px) {
  .b-category img {
    width: 100%;
  }
}
@media (min-width: 768px) and (max-width: 1365px) {
  .b-category.last-row {
    margin-bottom: 45px !important;
  }
  .b-category img {
    width: 100%;
  }
}
/*
* Content Categories END
*/
/*
* Content History
*/
.v-history .h-clear {
  text-align: right;
  padding-top: 8px;
}
.v-history .h-clear i {
  font-size: 12px;
}
.v-history .h-clear-list {
  text-align: right;
  padding-top: 45px;
}
.v-history .h-clear-list a {
  color: #7e7e7e;
}
.v-history .h-clear-list a:hover {
  color: #ea2c5a;
}
.v-history .content-block .cb-header {
  padding: 15px 0;
  margin-bottom: 30px;
  color: #7e7e7e;
  border-bottom: solid 1px #eceff0;
}
.v-history .content-block .cb-header a {
  color: #7e7e7e;
}
.v-history .content-block .cb-header a:hover {
  color: #ea2c5a;
}
.v-history .content-block .cb-header a.active {
  color: #ea2c5a;
}
.v-history .content-block .cb-header .list-inline {
  margin: 0;
  margin-left: -5px;
  line-height: 34px;
}
.v-history .h-video .h-divider {
  height: 1px;
  border-bottom: solid 1px #eceff0;
  margin: 30px 15px;
}
.v-history .h-video .v-img {
  border-radius: 2px;
  position: relative;
}
.v-history .h-video .v-img img {
  width: 100%;
}
.v-history .h-video .v-img .time {
  position: absolute;
  bottom: 0;
  right: 0;
  background-color: #373933;
  border-bottom-right-radius: 2px;
  border-top-left-radius: 2px;
  color: #ffffff;
  font-size: 14px;
  padding: 6px 9px 1px 9px;
  line-height: 14px;
  font-weight: 500;
}
.v-history .h-video .v-desc {
  color: #343434;
  font-weight: 500;
}
.v-history .h-video .v-views {
  font-size: 15px;
  color: #7e7e7e;
  padding-bottom: 5px;
  padding-top: 5px;
}
.v-history .h-video .v-percent {
  color: #28b47e;
  display: inline-block;
  position: relative;
  padding-left: 19px;
}
.v-history .h-video .v-percent .v-circle {
  border: solid 2px #28b47e;
  border-radius: 7px;
  width: 14px;
  height: 14px;
  display: inline-block;
  position: absolute;
  top: 1px;
  left: 0px;
}
.v-history .h-video.last-row {
  padding-bottom: 0px;
}
.v-history .loadmore {
  margin: 45px 0;
  text-align: center;
}
.v-history .loadmore .h-btn {
  background-color: #eceff0;
  color: #2e2e2e;
  padding: 15px 65px;
  border: solid 1px #eceff0;
  height: 48px;
  border-radius: 24px;
  font-weight: normal;
}
.v-history .loadmore .h-btn:hover {
  color: #ea2c5a;
  background-color: #ffffff;
  border: solid 1px #ea2c5a;
}
@media (min-width: 100px) and (max-width: 767px) {
  .h-video .v-desc {
    padding-top: 15px;
  }
}
/*
* Content History END
*/
/*
* Content Channel
*/
.channel .h-grid {
  margin-top: 6px;
}
.channel .h-grid i {
  padding-left: 25px;
}
.channel .img {
  position: relative;
}
.channel .img .c-avatar {
  position: absolute;
  bottom: -80px;
  left: 50%;
  margin-left: -585px;
}
.channel .img .c-social {
  position: absolute;
  bottom: 0;
  left: 50%;
  margin-left: 380px;
  background-color: rgba(54, 54, 54, 0.7);
  color: #ffffff;
  padding: 15px;
}
.channel .img .c-social a {
  display: inline-block;
  padding-top: 8px;
  padding-left: 10px;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  color: #ffffff;
  font-size: 15px;
  margin-left: 11px;
}
.channel .img .c-social .fb {
  background-color: #3b5998;
}
.channel .img .c-social .tw {
  background-color: #55acee;
  padding-top: 7px;
  padding-left: 8px;
}
.channel .img .c-social .gp {
  background-color: #dd4b39;
  padding-top: 7px;
  padding-left: 5px;
}

.channel .img .c-banner
{
  width: 100%;
}

.channel .c-details {
  height: 75px;
  border-bottom: solid 1px #eceff0;
  padding-top: 23px;
}
.channel .c-details .c-name {
  width: 21%;
  float: left;
  position: relative;
  padding-top: 5px;
  font-weight: 500;
  font-size: 17px;
}
.channel .c-details .c-name .c-checkbox {
  position: absolute;
  top: 0;
  left: 100px;
}
.channel .c-details .c-name .c-checkbox input {
  height: 20px;
  width: 20px;
  margin-left: 16px;
  margin-top: 5px;
  background-color: red;
}
.channel .c-details .c-name .c-checkbox img {
  margin-left: 16px;
  margin-top: 5px;
}
.channel .c-details .c-nav {
  width: 59%;
  float: left;
  font-weight: 500;
  padding-top: 4px;
  font-family: 'Hind', sans-serif;
}
.channel .c-details .c-nav li {
  margin: 0;
  padding: 0;
  margin-right: 23px;
}
.channel .c-details .c-nav li a {
  position: relative;
}
.channel .c-details .c-nav li a:before {
  content: "";
  position: absolute;
  bottom: -25px;
  display: inline-block;
  background-color: #ea2c5a;
  height: 3px;
  width: 100%;
  left: 0;
  opacity: 0;
  -moz-transition: all 0.12s linear;
  -o-transition: all 0.12s linear;
  -webkit-transition: all 0.12s linear;
}
.channel .c-details .c-nav li a:hover:before {
  opacity: 1;
}
.channel .c-details .c-sub {
  float: left;
}
.channel .c-details .c-sub .c-f {
  float: left;
  width: 86px;
  padding: 5px 10px 0px 10px;
  border: solid 1px #ea2c5a;
  border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  background-color: #ea2c5a;
  color: #ffffff;
}
.channel .c-details .c-sub .c-s {
  float: left;
  width: 92px;
  padding: 5px 10px 0px 10px;
  border: solid 1px #eceff0;
  border-left: none;
  border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  color: #7e7e7e;
}
@media (min-width: 100px) and (max-width: 767px) {
  .channel .img .c-avatar {
    position: relative;
    margin: 0;
    left: 0;
    bottom: 0;
    text-align: center;
    padding: 10px 0;
  }
  .channel .img .c-social {
    position: relative;
    margin: 0;
    left: 0;
    bottom: 0;
  }
  .channel .c-details {
    height: auto;
    padding-bottom: 15px;
  }
  .channel .c-details .c-name {
    float: none;
    width: 100%;
  }
  .channel .c-details .c-nav {
    float: none;
    width: 100%;
  }
  .channel .c-details .c-nav .list-inline {
    margin-left: 0;
    padding: 10px 0;
  }
}
@media (min-width: 768px) and (max-width: 1365px) {
  .channel-details {
    margin-top: 40px;
  }
  .channel .img .c-avatar {
    bottom: -50px;
    left: 20px;
    margin-left: 0;
  }
  .channel .img .c-avatar img {
    width: 120px;
  }
  .channel .img .c-social {
    bottom: 0;
    left: auto;
    margin-left: 0;
    right: 0;
  }
  .channel .c-details {
    height: auto;
    padding-bottom: 15px;
  }
  .channel .c-details .c-name {
    width: 100%;
  }
  .channel .c-details .c-nav {
    width: 75%;
  }
  .channel .c-details .c-nav .list-inline {
    margin-left: 0;
    padding: 10px 0;
  }
  .channel .c-details .c-sub {
    width: 25%;
    padding: 10px 0;
  }
}
/*
* Content Channel END
*/
.channels h4 {
  font-size: 16px;
}
.channels .content-block .cb-header {
  padding: 15px 0;
  margin-bottom: 20px;
  color: #7e7e7e;
  border-bottom: solid 1px #eceff0;
}
.channels .content-block .cb-header .list-inline {
  margin: 0;
  margin-top: 4px;
  margin-left: -5px;
  line-height: 34px;
}
.channels .content-block .cb-header .list-inline a {
  color: #7e7e7e;
}
.channels .content-block .cb-header .list-inline a.color-active {
  color: #ea2c5a;
}
.channels .content-block .cb-header .list-inline a:not(.color-active):hover {
  color: #343434;
}
.channels .content-block .cb-header .cb-search {
  position: relative;
}
.channels .content-block .cb-header .cb-search label {
  display: block;
  margin: 0;
}
.channels .content-block .cb-header .cb-search input[type="search"] {
  border-radius: 20px;
  padding-left: 40px;
}
.channels .content-block .cb-header .cb-search i {
  position: absolute;
  left: 16px;
  top: 11px;
}
.channels .content-block .b-category {
  border-radius: 2px;
  margin-bottom: 45px;
}
.channels .content-block .b-category.last-row {
  margin-bottom: 0;
}
.channels .content-block .b-category .name {
  font-weight: 500;
  margin-top: 25px;
  display: block;
}
.channels .content-block .b-category .desc {
  color: #7e7e7e;
  display: block;
  font-size: 15px;
  margin-top: 5px;
}
.channels .content-block .channels-content {
  padding-bottom: 16px;
}
.channels .content-block .channels-content > h4 {
  float: left;
}
.channels .content-block .channels-content .btn-view-more {
  display: block;
  float: right;
  color: #7e7e7e;
  margin: 8px 0 11px;
}
.channels .content-block .channels-content .btn-view-more:hover {
  color: #343434;
}
.channels .content-block .channels-content .theme-section {
  padding-top: 10px;
}
.channels .content-block .channels-content .theme-section .cns-block {
  display: block;
  margin-bottom: 30px;
  border-right: 4px;
  overflow: hidden;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-image {
  position: relative;
  display: block;
  max-height: 116px;
  overflow: hidden;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-image > img {
  width: 100%;
  height: auto;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-img-small {
  position: relative;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-img-small .cns-small-wrapp {
  position: absolute;
  width: 78px;
  height: 70px;
  margin-left: -39px;
  left: 50%;
  bottom: -35px;
  background-color: white;
  border-radius: 36px;
  overflow: hidden;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-img-small .cns-small-wrapp > img {
  position: absolute;
  width: 70px;
  height: 62px;
  top: 4px;
  left: 4px;
  border-radius: 36px;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-info {
  text-align: center;
  padding: 42px 0 22px;
  margin-top: -4px;
  border: solid 1px #eceff0;
  border-top: none;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-info h5 {
  position: relative;
  display: inline-block;
  margin-top: 18px;
  margin-bottom: 6px;
  color: #343434;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-info h5 i {
  position: absolute;
  display: block;
  width: 20px;
  height: 20px;
  right: -34px;
  top: -3px;
  border-radius: 4px;
  background-color: #4d86fe;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-info h5 i::after {
  display: block;
  content: "";
  position: absolute;
  width: 11px;
  height: 7px;
  left: 4.5px;
  top: 5px;
  border-bottom: solid 3px white;
  border-left: solid 3px white;
  -webkit-transform: rotate(-45deg);
  -moz-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  -o-transform: rotate(-45deg);
}
.channels .content-block .channels-content .theme-section .cns-block .cns-info > span:not(.cv-percent) {
  display: block;
  color: #7e7e7e;
}
.channels .content-block .channels-content .theme-section .cns-block .cns-info > span {
  margin-bottom: 2px;
}
.channels .content-block .channels-content .theme-section:not(:last-child) {
  border-bottom: solid 1px #eceff0;
  margin-bottom: 16px;
}
@media only screen and (max-width: 414px) {
  .channels .content-block .channels-content .theme-section > .row > div {
    width: 100%;
  }
}
/*
* Content Single Video
*/
.single-video .h-clear {
  text-align: right;
  padding-top: 8px;
}
.single-video .h-clear i {
  font-size: 12px;
}
.single-video .h-clear-list {
  text-align: right;
  padding-top: 45px;
}
.single-video .h-clear-list a {
  color: #7e7e7e;
}
.single-video .h-clear-list a:hover {
  color: #ea2c5a;
}
.single-video .content-block .cb-header {
  padding: 15px 0;
  margin-bottom: 30px;
  color: #7e7e7e;
  border-bottom: solid 1px #eceff0;
}
.single-video .content-block .cb-header a {
  color: #7e7e7e;
}
.single-video .content-block .cb-header a:hover {
  color: #ea2c5a;
}
.single-video .content-block .cb-header a.active {
  color: #ea2c5a;
}
.single-video .content-block .cb-header .list-inline {
  margin: 0;
  margin-left: -5px;
  line-height: 34px;
}
.single-video .h-video {
  margin-bottom: 30px;
}
.single-video .h-video .v-img {
  border-radius: 2px;
  position: relative;
}
.single-video .h-video .v-img img {
  width: 100%;
}
.single-video .h-video .v-img .time {
  position: absolute;
  bottom: 0;
  right: 0;
  background-color: #373933;
  border-bottom-right-radius: 2px;
  border-top-left-radius: 2px;
  color: #ffffff;
  font-size: 14px;
  padding: 6px 9px 1px 9px;
  line-height: 14px;
  font-weight: 500;
}
.single-video .h-video .v-desc {
  color: #343434;
  font-weight: 500;
}
.single-video .h-video .v-views {
  font-size: 15px;
  color: #7e7e7e;
  padding-bottom: 5px;
  padding-top: 5px;
}
.single-video .h-video .v-percent {
  color: #28b47e;
  display: inline-block;
  position: relative;
  padding-left: 19px;
}
.single-video .h-video .v-percent .v-circle {
  border: solid 2px #28b47e;
  border-radius: 7px;
  width: 14px;
  height: 14px;
  display: inline-block;
  position: absolute;
  top: 1px;
  left: 0px;
}
.single-video .h-video.last-row {
  padding-bottom: 0px;
}
.single-video .content-wrapper {
  padding-top: 30px;
}
.single-video .caption {
  padding-bottom: 21px;
  margin-bottom: 30px;
  border-bottom: solid 1px #eceff0;
}
.single-video .caption .left {
  width: 50%;
  float: left;
}
.single-video .caption .right {
  width: 50%;
  float: right;
  text-align: right;
  padding-right: 10px;
  color: #7e7e7e;
}
.single-video .caption .right a {
  color: #7e7e7e;
}
.single-video .caption .right a:hover {
  color: #ea2c5a;
}
.single-video .list .h-video:last-child {
  margin-bottom: 0;
}
.single-video .adblock {
  padding: 30px 0;
}
.single-video .adblock .img {
  background-color: #eceff0;
  border-radius: 3px;
  width: 336px;
  height: 280px;
  color: #a1a1a1;
  text-align: center;
  padding-top: 120px;
}
.single-video .loadmore {
  padding: 30px 0;
  margin-top: 30px;
  border-top: solid 1px #eceff0;
  text-align: center;
}
.single-video .loadmore a {
  color: #7e7e7e;
}
.single-video .loadmore a:hover {
  color: #ea2c5a;
}
.single-video .sv-video {
  position: relative;
}
.single-video .sv-video .sv-play {
  width: 66px;
  height: 66px;
  background-color: #343434;
  border-radius: 33px;
  opacity: 0.85;
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -33px;
  margin-left: -33px;
  color: #ffffff;
  padding-top: 22px;
  padding-left: 21px;
  font-size: 20px;
}
.single-video .sv-video .sv-play i {
  opacity: 1;
}
.single-video h1 {
  margin: 0;
  padding: 30px 0;
  font-size: 22px;
}
.single-video .author {
  padding: 30px;
  background-color: #ffffff;
  border-radius: 5px;
  -webkit-box-shadow: 0px 2px 1px 1px #d6d7d8;
  -moz-box-shadow: 0px 2px 1px 1px #d6d7d8;
  box-shadow: 0px 2px 1px 1px #d6d7d8;
}
.single-video .author .sv-avatar {
  width: 72px;
  float: left;
}
.single-video .author .sv-name {
  width: 430px;
  padding-left: 30px;
  float: left;
  color: #7e7e7e;
}
.single-video .author .sv-name a {
  font-weight: 500;
  color: #2e2e2e;
}
.single-video .author .sv-name a:hover {
  color: #ea2c5a;
}
.single-video .author .sv-name .c-sub {
  padding-top: 13px;
  float: left;
}
.single-video .author .sv-name .c-sub .c-f {
  float: left;
  width: 86px;
  padding: 5px 10px 0px 10px;
  border: solid 1px #ea2c5a;
  border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  background-color: #ea2c5a;
  color: #ffffff;
}
.single-video .author .sv-name .c-sub .c-s {
  float: left;
  width: 92px;
  padding: 5px 10px 0px 10px;
  border: solid 1px #eceff0;
  border-left: none;
  border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  color: #7e7e7e;
}
.single-video .author .sv-views {
  float: right;
  width: 200px;
}
.single-video .author .sv-views .sv-views-count {
  font-size: 20px;
  text-align: right;
}
.single-video .author .sv-views .sv-views-progress {
  margin-top: 10px;
  margin-bottom: 10px;
  height: 3px;
  width: 100%;
  background-color: #eceff0;
}
.single-video .author .sv-views .sv-views-progress .sv-views-progress-bar {
  height: 3px;
  width: 80%;
  background-color: #28b47e;
}
.single-video .author .sv-views .sv-views-stats .percent {
  color: #ea2c5a;
  font-size: 15px;
  padding-right: 30px;
}
.single-video .author .sv-views .sv-views-stats .green {
  color: #28b47e;
  font-size: 15px;
  padding-right: 30px;
}
.single-video .author .sv-views .sv-views-stats .green .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #28b47e;
}
.single-video .author .sv-views .sv-views-stats .grey {
  color: #7e7e7e;
  font-size: 15px;
}
.single-video .author .sv-views .sv-views-stats .grey .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #7e7e7e;
}
.single-video .info {
  margin-top: 25px;
}
.single-video .info h4 {
  margin: 20px 0 3px 0;
  padding: 0;
  font-weight: 500;
  font-size: 16px;
}
.single-video .info p {
  color: #7e7e7e;
}
.single-video .info .sv-tags {
  margin-bottom: 0;
}
.single-video .info .sv-tags span {
  display: inline-block;
  padding: 5px 9px 1px 9px;
  background-color: #eceff0;
  border-radius: 3px;
  margin-right: 7px;
}
.single-video .info .date-lic h4 {
  display: inline-block;
}
.single-video .info .date-lic p {
  display: inline-block;
}
.single-video .showless {
  position: relative;
  border-bottom: solid 1px #eceff0;
  margin: 14px 0;
}
.single-video .showless a {
  display: block;
  position: absolute;
  top: -14px;
  left: 50%;
  margin-left: -50px;
  height: 28px;
  border: solid 1px #7e7e7e;
  border-radius: 14px;
  padding: 3px 12px 6px 12px;
  background-color: #fbfdfe;
}
.single-video .showless a:hover {
  color: #ea2c5a;
  border-color: #ea2c5a;
}
.single-video .adblock2 {
  padding: 30px 0;
  text-align: center;
}
.single-video .adblock2 .img {
  background-color: #eceff0;
  border-radius: 3px;
  width: 728px;
  height: 90px;
  color: #a1a1a1;
  text-align: center;
  padding-top: 26px;
  margin: 0 auto;
}
.single-video .similar-videos {
  padding-bottom: 30px;
  margin-bottom: 30px;
  border-bottom: solid 1px #eceff0;
}
.single-video .similar-videos .v-views {
  padding-bottom: 0;
}
.single-video .similar-videos .v-percent {
  display: block;
  margin-top: 3px;
}
.single-video .reply-comment {
  font-size: 17px;
  margin-bottom: 25px;
}
.single-video .reply-comment i {
  font-size: 20px;
}
.single-video .reply-comment .semibold {
  font-weight: 600;
  padding-left: 5px;
}
.single-video .reply-comment .rc-header {
  margin-bottom: 25px;
}
.single-video .reply-comment textarea {
  width: 100%;
  height: 108px;
  background-color: #ffffff;
  border: solid 1px #eceff0;
  border-radius: 3px;
  padding: 25px 30px;
  color: #7e7e7e;
}
.single-video .reply-comment .rc-ava {
  float: left;
  width: 70px;
  margin-right: 30px;
}
.single-video .reply-comment .rc-comment {
  float: left;
  position: relative;
  width: 670px;
}
.single-video .reply-comment .rc-comment button {
  position: absolute;
  bottom: 5px;
  right: 0px;
  background: none;
  border: none;
  box-shadow: none;
  padding: 15px;
}
.single-video .cl-header {
  padding-bottom: 25px;
  margin-bottom: 25px;
  border-bottom: solid 1px #eceff0;
}
.single-video .cl-header .list-inline {
  margin-left: 0;
  margin-bottom: 0;
}
.single-video .cl-header .c-nav {
  font-weight: 500;
  padding-top: 4px;
  font-family: 'Hind', sans-serif;
}
.single-video .cl-header .c-nav li {
  margin: 0;
  padding: 0;
  margin-right: 23px;
}
.single-video .cl-header .c-nav li a {
  position: relative;
  color: #7e7e7e;
}
.single-video .cl-header .c-nav li a:before {
  content: "";
  position: absolute;
  bottom: -25px;
  display: inline-block;
  background-color: #ea2c5a;
  height: 3px;
  width: 100%;
  left: 0;
  opacity: 0;
  -moz-transition: all 0.12s linear;
  -o-transition: all 0.12s linear;
  -webkit-transition: all 0.12s linear;
}
.single-video .cl-header .c-nav li a:hover {
  color: #2e2e2e;
}
.single-video .cl-header .c-nav li a:hover:before {
  opacity: 1;
}
.single-video .cl-header .c-nav li a.active {
  color: #2e2e2e;
}
.single-video .cl-header .c-nav li a.active:before {
  opacity: 1;
}
.single-video .cl-comment {
  margin-bottom: 45px;
}
.single-video .cl-comment .cl-avatar {
  float: left;
  width: 13%;
  padding-right: 30px;
}
.single-video .cl-comment .cl-comment-text {
  float: left;
  width: 87%;
}
.single-video .cl-comment-reply {
  margin-bottom: 45px;
  margin-left: 13%;
}
.single-video .cl-comment-reply .cl-avatar {
  float: left;
  width: 15%;
  padding-right: 30px;
}
.single-video .cl-comment-reply .cl-comment-text {
  float: left;
  width: 85%;
}
.single-video .cl-name-date {
  color: #8e9ea6;
  font-size: 15px;
}
.single-video .cl-name-date a {
  font-size: 16px;
  color: #ea2c5a;
}
.single-video .cl-name-date a:hover {
  text-decoration: underline;
}
.single-video .cl-text {
  padding: 6px 0;
}
.single-video .cl-meta {
  color: #8e9ea6;
}
.single-video .cl-meta a {
  color: #8e9ea6;
}
.single-video .cl-meta a:hover {
  text-decoration: underline;
}
.single-video .cl-meta .green {
  color: #28b47e;
  font-size: 15px;
  padding-right: 10px;
}
.single-video .cl-meta .green .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #28b47e;
}
.single-video .cl-meta .grey {
  color: #7e7e7e;
  font-size: 15px;
}
.single-video .cl-meta .grey .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #7e7e7e;
}
.single-video .cl-replies {
  color: #7e7e7e;
  padding-top: 6px;
}
.single-video .cl-replies a {
  color: #7e7e7e;
}
.single-video .cl-replies a:hover {
  text-decoration: underline;
}
.single-video .cl-replies i {
  font-size: 10px;
}
.single-video .cl-comment-text {
  position: relative;
}
.single-video .cl-comment-text .cl-flag {
  position: absolute;
  top: 0;
  right: 0;
  font-size: 20px;
}
.single-video .loadmore-comments {
  margin-bottom: 45px;
  text-align: center;
}
.single-video .loadmore-comments .h-btn {
  background-color: #eceff0;
  color: #2e2e2e;
  padding: 15px 65px;
  border: solid 1px #eceff0;
  height: 48px;
  border-radius: 24px;
  font-weight: normal;
}
.single-video .loadmore-comments .h-btn:hover {
  color: #ea2c5a;
  background-color: #ffffff;
  border: solid 1px #ea2c5a;
}
@media (min-width: 100px) and (max-width: 767px) {
  .sv-video img {
    width: 100%;
  }
  .single-video .adblock2 .img {
    width: 100%;
  }
  .single-video .adblock .img {
    width: 100%;
  }
  .single-video .reply-comment .rc-comment {
    width: 100%;
  }
  .single-video .author > a {
    width: 100%;
    text-align: center;
    padding-bottom: 15px;
    display: inline-block;
  }
  .single-video .author .sv-avatar {
    float: none;
    display: inline-block;
  }
  .single-video .author .sv-name {
    width: 100%;
    padding-left: 0;
    text-align: center;
    float: none;
  }
  .single-video .author .sv-name .c-sub {
    float: none;
    text-align: center;
    padding-bottom: 15px;
  }
  .single-video .author .sv-views {
    width: 100%;
    float: none;
  }
  .single-video .author .sv-views .sv-views-count {
    text-align: center;
  }
  .single-video .cl-comment .cl-avatar {
    width: 35%;
    padding-right: 15px;
  }
  .single-video .cl-comment .cl-comment-text {
    width: 65%;
  }
  .single-video .cl-comment .cl-comment-text .cl-flag {
    right: -10px;
  }
  .single-video .cl-comment-reply {
    margin-left: 5%;
  }
  .single-video .cl-comment-reply .cl-avatar {
    width: 35%;
    padding-right: 10px;
  }
  .single-video .cl-comment-reply .cl-comment-text {
    width: 65%;
  }
  .b-video {
    margin-bottom: 15px;
  }
  .b-video .v-img img {
    width: 100%;
  }
  .reply-comment .rc-ava {
    text-align: center;
    float: none;
    margin-bottom: 10px;
  }
}
@media (min-width: 768px) and (max-width: 1365px) {
  .sv-video img {
    width: 100%;
  }
  .similar-videos .videoitem {
    margin-bottom: 30px;
  }
  .similar-videos .videoitem img {
    width: 100%;
  }
  .single-video .reply-comment .rc-comment {
    width: 600px;
  }
  .single-video .adblock .img {
    width: 100%;
  }
  .single-video .adblock2 .img {
    width: 100%;
  }
}
/*
* Content Single Video END
*/
/*
* Content Single Video
*/
.single-video .h-clear {
  text-align: right;
  padding-top: 8px;
}
.single-video .h-clear i {
  font-size: 12px;
}
.single-video .h-clear-list {
  text-align: right;
  padding-top: 45px;
}
.single-video .h-clear-list a {
  color: #7e7e7e;
}
.single-video .h-clear-list a:hover {
  color: #ea2c5a;
}
.single-video .content-block .cb-header {
  padding: 15px 0;
  margin-bottom: 30px;
  color: #7e7e7e;
  border-bottom: solid 1px #eceff0;
}
.single-video .content-block .cb-header a {
  color: #7e7e7e;
}
.single-video .content-block .cb-header a:hover {
  color: #ea2c5a;
}
.single-video .content-block .cb-header a.active {
  color: #ea2c5a;
}
.single-video .content-block .cb-header .list-inline {
  margin: 0;
  margin-left: -5px;
  line-height: 34px;
}
.single-video .h-video {
  margin-bottom: 30px;
}
.single-video .h-video .v-img {
  border-radius: 2px;
  position: relative;
}
.single-video .h-video .v-img img {
  width: 100%;
}
.single-video .h-video .v-img .time {
  position: absolute;
  bottom: 0;
  right: 0;
  background-color: rgba(55, 57, 51, 0.8);
  border-bottom-right-radius: 2px;
  border-top-left-radius: 2px;
  color: #ffffff;
  font-size: 14px;
  padding: 6px 9px 1px 9px;
  line-height: 14px;
  font-weight: 500;
}
.single-video .h-video .v-desc {
  color: #343434;
  font-weight: 500;
  padding-top: 0;
}
.single-video .h-video .v-views {
  font-size: 15px;
  color: #7e7e7e;
  padding-bottom: 5px;
  padding-top: 5px;
}
.single-video .h-video .v-percent {
  color: #28b47e;
  display: inline-block;
  position: relative;
  padding-left: 19px;
}
.single-video .h-video .v-percent .v-circle {
  border: solid 2px #28b47e;
  border-radius: 7px;
  width: 14px;
  height: 14px;
  display: inline-block;
  position: absolute;
  top: 1px;
  left: 0px;
}
.single-video .h-video.last-row {
  padding-bottom: 0px;
}
.single-video .h-video.playlist {
  padding-bottom: 15px;
  margin-bottom: 15px;
}
.single-video .h-video.playlist:not(:last-child) {
  border-bottom: solid 1px #eceff0;
}
.single-video .h-video.playlist > div:first-child {
  padding-right: 0;
}
.single-video .h-video.playlist .v-number {
  display: block;
  width: 21%;
  height: 1px;
  float: left;
}
.single-video .h-video.playlist .v-number span {
  position: absolute;
  width: 22px;
  height: 22px;
  top: 50%;
  margin-top: -11px;
}
.single-video .h-video.playlist .v-number span i {
  color: #4d86fe;
}
.single-video .h-video.playlist .v-img {
  display: block;
  width: 79%;
  float: left;
}
.single-video .content-wrapper {
  padding-top: 30px;
}
.single-video .caption {
  padding-bottom: 21px;
  margin-bottom: 30px;
  border-bottom: solid 1px #eceff0;
}
.single-video .caption .left {
  width: 50%;
  float: left;
}
.single-video .caption .right {
  width: 50%;
  float: right;
  text-align: right;
  padding-right: 10px;
  color: #7e7e7e;
}
.single-video .caption .right a {
  color: #7e7e7e;
}
.single-video .caption .right a:hover {
  color: #ea2c5a;
}
.single-video .caption.playlist {
  margin-bottom: 15px;
}
.single-video .caption.playlist .left {
  width: 70%;
}
.single-video .caption.playlist .right {
  width: 30%;
}
.single-video .caption.playlist .right i {
  font-size: 20px;
  cursor: pointer;
}
.single-video .caption.playlist .right i:not(:first-child) {
  margin-left: 22px;
}
@media only screen and (max-width: 414px) {
  .single-video .caption.playlist .left,
  .single-video .caption.playlist .right {
    width: 50%;
  }
}
.single-video .list .h-video:last-child {
  margin-bottom: 0;
}
.single-video .adblock {
  padding: 30px 0;
}
.single-video .adblock .img {
  background-color: #eceff0;
  border-radius: 3px;
  width: 336px;
  height: 280px;
  color: #a1a1a1;
  text-align: center;
  padding-top: 120px;
}
.single-video .loadmore {
  padding: 30px 0;
  margin-top: 30px;
  border-top: solid 1px #eceff0;
  text-align: center;
}
.single-video .loadmore a {
  color: #7e7e7e;
}
.single-video .loadmore a:hover {
  color: #ea2c5a;
}
.single-video .sv-video {
  position: relative;
}
.single-video .sv-video .sv-play {
  width: 66px;
  height: 66px;
  background-color: #343434;
  border-radius: 33px;
  opacity: 0.85;
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -33px;
  margin-left: -33px;
  color: #ffffff;
  padding-top: 22px;
  padding-left: 21px;
  font-size: 20px;
}
.single-video .sv-video .sv-play i {
  opacity: 1;
}
.single-video h1 {
  margin: 0;
  padding: 30px 0;
  font-size: 22px;
}
.single-video .author {
  padding: 30px;
  background-color: #ffffff;
  border-radius: 5px;
  -webkit-box-shadow: 0px 2px 1px 1px #d6d7d8;
  -moz-box-shadow: 0px 2px 1px 1px #d6d7d8;
  box-shadow: 0px 2px 1px 1px #d6d7d8;
}
.single-video .author .sv-avatar {
  width: 72px;
  float: left;
}
.single-video .author .sv-name {
  width: 430px;
  padding-left: 30px;
  float: left;
  color: #7e7e7e;
}
.single-video .author .sv-name a {
  font-weight: 500;
  color: #2e2e2e;
}
.single-video .author .sv-name a:hover {
  color: #ea2c5a;
}
.single-video .author .sv-name .c-sub {
  padding-top: 13px;
  float: left;
}
.single-video .author .sv-name .c-sub .c-f {
  float: left;
  width: 86px;
  padding: 5px 10px 0px 10px;
  border: solid 1px #ea2c5a;
  border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  background-color: #ea2c5a;
  color: #ffffff;
}
.single-video .author .sv-name .c-sub .c-s {
  float: left;
  width: 92px;
  padding: 5px 10px 0px 10px;
  border: solid 1px #eceff0;
  border-left: none;
  border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
  color: #7e7e7e;
}
.single-video .author .sv-views {
  float: right;
  width: 200px;
}
.single-video .author .sv-views .sv-views-count {
  font-size: 20px;
  text-align: right;
}
.single-video .author .sv-views .sv-views-progress {
  margin-top: 10px;
  margin-bottom: 10px;
  height: 3px;
  width: 100%;
  background-color: #eceff0;
}
.single-video .author .sv-views .sv-views-progress .sv-views-progress-bar {
  height: 3px;
  width: 80%;
  background-color: #28b47e;
}
.single-video .author .sv-views .sv-views-stats .percent {
  color: #ea2c5a;
  font-size: 15px;
  padding-right: 30px;
}
.single-video .author .sv-views .sv-views-stats .green {
  color: #28b47e;
  font-size: 15px;
  padding-right: 30px;
}
.single-video .author .sv-views .sv-views-stats .green .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #28b47e;
}
.single-video .author .sv-views .sv-views-stats .grey {
  color: #7e7e7e;
  font-size: 15px;
}
.single-video .author .sv-views .sv-views-stats .grey .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #7e7e7e;
}
.single-video .info {
  margin-top: 3px;
}
.single-video .info h4 {
  margin: 20px 0 3px 0;
  padding: 0;
  font-weight: 500;
  font-size: 16px;
}
.single-video .info p {
  color: #7e7e7e;
}
.single-video .info .sv-tags {
  margin-bottom: 0;
}
.single-video .info .sv-tags span {
  display: inline-block;
  padding: 5px 9px 1px 9px;
  background-color: #eceff0;
  border-radius: 3px;
  margin-right: 7px;
}
.single-video .info .date-lic h4 {
  display: inline-block;
}
.single-video .info .date-lic p {
  display: inline-block;
}
.single-video .custom-tabs .tabs-panel {
  overflow: hidden;
  border-bottom: solid 1px #eceff0;
}
.single-video .custom-tabs .tabs-panel a {
  display: block;
  float: left;
}
.single-video .custom-tabs .tabs-panel a i,
.single-video .custom-tabs .tabs-panel a span {
  display: block;
  float: left;
}
.single-video .custom-tabs .tabs-panel a i {
  color: #637076;
  font-size: 20px;
}
.single-video .custom-tabs .tabs-panel a span {
  color: #7e7e7e;
}
.single-video .custom-tabs .tabs-panel a:hover i,
.single-video .custom-tabs .tabs-panel a:hover span {
  color: #ea2c5a;
}
.single-video .custom-tabs .tabs-panel > a,
.single-video .custom-tabs .tabs-panel > .acide-panel {
  height: 48px;
  padding-top: 13px;
}
.single-video .custom-tabs .tabs-panel > a {
  padding-left: 16px;
  padding-right: 16px;
}
.single-video .custom-tabs .tabs-panel > a i {
  width: 30px;
  margin-right: 8px;
}
.single-video .custom-tabs .tabs-panel > a i.cv.cvicon-cv-goto {
  font-size: 7px;
  line-height: 20px;
  margin-right: 14px;
}
.single-video .custom-tabs .tabs-panel > a span {
  line-height: 24px;
}
.single-video .custom-tabs .tabs-panel > a.active {
  background-color: #eceff0;
}
.single-video .custom-tabs .tabs-panel > a.active i,
.single-video .custom-tabs .tabs-panel > a.active span {
  color: #ea2c5a;
  font-weight: 500;
}
.single-video .custom-tabs .tabs-panel > .acide-panel {
  float: right;
}
.single-video .custom-tabs .tabs-panel > .acide-panel a:not(:last-child) {
  margin-right: 20px;
}
.single-video .custom-tabs .tabs-content > div {
  display: none;
  padding-top: 8px;
}
.single-video .custom-tabs .tabs-content > div.active {
  display: block !important;
}
.single-video .custom-tabs .tabs-content .tab-2 h4,
.single-video .custom-tabs .tabs-content .tab-3 h4,
.single-video .custom-tabs .tabs-content .tab-4 h4,
.single-video .custom-tabs .tabs-content .tab-5 h4 {
  margin-bottom: 10px;
}
.single-video .custom-tabs .tabs-content .tab-1 {
  overflow: hidden;
}
.single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(1) {
  float: left;
  width: 76.12%;
  padding-right: 18px;
  padding-bottom: 14px;
  border-right: solid 1px #eceff0;
}
.single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(2) {
  float: left;
  width: 23.88%;
  max-width: 170px;
  padding-left: 30px;
  padding-bottom: 28px;
}
.single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(2) img {
  width: 100%;
  height: auto;
  margin-bottom: 14px;
}
.single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(2) .btn {
  display: block;
  width: 100%;
  max-width: 140px;
  height: 28px;
  padding-top: 4px;
  margin: 0 auto;
  background-color: #447efa;
  color: white;
  borde: solid 1px #447efa;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -ms-transition: 0.3s;
  -o-transition: 0.3s;
  -webkit-box-shadow: 0px 0px 4px 1px rgba(0, 0, 0, 0.1);
  -moz-box-shadow: 0px 0px 4px 1px rgba(0, 0, 0, 0.1);
  box-shadow: 0px 0px 4px 1px rgba(0, 0, 0, 0.1);
}
.single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(2) .btn:hover {
  background-color: white;
  color: #447efa;
  border-color: #447efa;
}
@media only screen and (max-width: 568px) {
  .single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(1),
  .single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(2) {
    width: 100%;
    float: none;
  }
  .single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(1) {
    border: none;
  }
  .single-video .custom-tabs .tabs-content .tab-1 > div:nth-child(2) {
    padding-left: 0;
    padding-right: 0;
    max-width: inherit;
  }
}
.single-video .custom-tabs .tabs-content .tab-2 {
  padding-bottom: 16px;
  border-bottom: solid 1px #eceff0;
}
.single-video .custom-tabs .tabs-content .tab-2 .row > div:nth-child(2) {
  overflow: hidden;
}
.single-video .custom-tabs .tabs-content .tab-2 .row > div:nth-child(2) .checkbox {
  display: block;
  float: left;
  margin-right: 14px;
}
.single-video .custom-tabs .tabs-content .tab-2 .row > div:nth-child(2) > input {
  display: block;
  float: left;
  max-width: 136px;
}
.single-video .custom-tabs .tabs-content .tab-2 .row > div:nth-child(3) > textarea {
  height: auto;
  min-height: 62px;
  resize: none;
}
.single-video .custom-tabs .tabs-content .tab-2 .row > div:nth-child(4) .size-tags {
  margin-bottom: 10px;
}
@media only screen and (max-width: 568px) {
  .single-video .custom-tabs .tabs-content .tab-2 .row > div:nth-child(5) label.checkbox-text p {
    margin-bottom: 0px;
  }
}
.single-video .custom-tabs .tabs-content .tab-3 {
  padding-bottom: 14px;
  border-bottom: solid 1px #eceff0;
}
.single-video .showless {
  position: relative;
  border-bottom: solid 1px #eceff0;
  margin: 0px 0 14px;
}
.single-video .showless a {
  display: block;
  position: absolute;
  top: -14px;
  left: 50%;
  margin-left: -50px;
  height: 28px;
  border: solid 1px #7e7e7e;
  border-radius: 14px;
  padding: 3px 12px 6px 12px;
  background-color: #fbfdfe;
}
.single-video .showless a:hover {
  color: #ea2c5a;
  border-color: #ea2c5a;
}
.single-video .adblock2 {
  padding: 30px 0;
  text-align: center;
}
.single-video .adblock2 .img {
  background-color: #eceff0;
  border-radius: 3px;
  width: 728px;
  height: 90px;
  color: #a1a1a1;
  text-align: center;
  padding-top: 26px;
  margin: 0 auto;
}
.single-video .similar-videos {
  padding-bottom: 30px;
  margin-bottom: 30px;
  border-bottom: solid 1px #eceff0;
}
.single-video .similar-videos .v-views {
  padding-bottom: 0;
}
.single-video .similar-videos .v-percent {
  display: block;
  margin-top: 3px;
}
.single-video .reply-comment {
  font-size: 17px;
  margin-bottom: 25px;
}
.single-video .reply-comment i {
  font-size: 20px;
}
.single-video .reply-comment .semibold {
  font-weight: 600;
  padding-left: 5px;
}
.single-video .reply-comment .rc-header {
  margin-bottom: 25px;
}
.single-video .reply-comment textarea {
  width: 100%;
  height: 108px;
  background-color: #ffffff;
  border: solid 1px #eceff0;
  border-radius: 3px;
  padding: 25px 30px;
  color: #7e7e7e;
}
.single-video .reply-comment .rc-ava {
  float: left;
  width: 70px;
  margin-right: 30px;
}
.single-video .reply-comment .rc-comment {
  float: left;
  position: relative;
  width: 100%;
}
.single-video .reply-comment .rc-comment button {
  position: absolute;
  bottom: 5px;
  right: 0px;
  background: none;
  border: none;
  box-shadow: none;
  padding: 15px;
}
.single-video .cl-header {
  padding-bottom: 25px;
  margin-bottom: 25px;
  border-bottom: solid 1px #eceff0;
}
.single-video .cl-header .list-inline {
  margin-left: 0;
  margin-bottom: 0;
}
.single-video .cl-header .c-nav {
  font-weight: 500;
  padding-top: 4px;
  font-family: 'Hind', sans-serif;
}
.single-video .cl-header .c-nav li {
  margin: 0;
  padding: 0;
  margin-right: 23px;
}
.single-video .cl-header .c-nav li a {
  position: relative;
  color: #7e7e7e;
}
.single-video .cl-header .c-nav li a:before {
  content: "";
  position: absolute;
  bottom: -25px;
  display: inline-block;
  background-color: #ea2c5a;
  height: 3px;
  width: 100%;
  left: 0;
  opacity: 0;
  -moz-transition: all 0.12s linear;
  -o-transition: all 0.12s linear;
  -webkit-transition: all 0.12s linear;
}
.single-video .cl-header .c-nav li a:hover {
  color: #2e2e2e;
}
.single-video .cl-header .c-nav li a:hover:before {
  opacity: 1;
}
.single-video .cl-header .c-nav li a.active {
  color: #2e2e2e;
}
.single-video .cl-header .c-nav li a.active:before {
  opacity: 1;
}
.single-video .cl-comment {
  margin-bottom: 45px;
}
.single-video .cl-comment .cl-avatar {
  float: left;
  width: 13%;
  padding-right: 30px;
}
.single-video .cl-comment .cl-comment-text {
  float: left;
  width: 87%;
}
.single-video .cl-comment-reply {
  margin-bottom: 45px;
  margin-left: 13%;
}
.single-video .cl-comment-reply .cl-avatar {
  float: left;
  width: 15%;
  padding-right: 30px;
}
.single-video .cl-comment-reply .cl-comment-text {
  float: left;
  width: 85%;
}
.single-video .cl-name-date {
  color: #8e9ea6;
  font-size: 15px;
}
.single-video .cl-name-date a {
  font-size: 16px;
  color: #ea2c5a;
}
.single-video .cl-name-date a:hover {
  text-decoration: underline;
}
.single-video .cl-text {
  padding: 6px 0;
}
.single-video .cl-meta {
  color: #8e9ea6;
}
.single-video .cl-meta a {
  color: #8e9ea6;
}
.single-video .cl-meta a:hover {
  text-decoration: underline;
}
.single-video .cl-meta .green {
  color: #28b47e;
  font-size: 15px;
  padding-right: 10px;
}
.single-video .cl-meta .green .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #28b47e;
}
.single-video .cl-meta .grey {
  color: #7e7e7e;
  font-size: 15px;
}
.single-video .cl-meta .grey .circle {
  display: inline-block;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  border: solid 2px #7e7e7e;
}
.single-video .cl-replies {
  color: #7e7e7e;
  padding-top: 6px;
}
.single-video .cl-replies a {
  color: #7e7e7e;
}
.single-video .cl-replies a:hover {
  text-decoration: underline;
}
.single-video .cl-replies i {
  font-size: 10px;
}
.single-video .cl-comment-text {
  position: relative;
}
.single-video .cl-comment-text .cl-flag {
  position: absolute;
  top: 0;
  right: 0;
  font-size: 20px;
}
.single-video .loadmore-comments {
  margin-bottom: 45px;
  text-align: center;
}
.single-video .loadmore-comments .h-btn {
  background-color: #eceff0;
  color: #2e2e2e;
  padding: 15px 65px;
  border: solid 1px #eceff0;
  height: 48px;
  border-radius: 24px;
  font-weight: normal;
}
.single-video .loadmore-comments .h-btn:hover {
  color: #ea2c5a;
  background-color: #ffffff;
  border: solid 1px #ea2c5a;
}
@media (min-width: 100px) and (max-width: 767px) {
  .sv-video img {
    width: 100%;
  }
  .single-video .adblock2 .img {
    width: 100%;
  }
  .single-video .adblock .img {
    width: 100%;
  }
  .single-video .reply-comment .rc-comment {
    width: 100%;
  }
  .single-video .author > a {
    width: 100%;
    text-align: center;
    padding-bottom: 15px;
    display: inline-block;
  }
  .single-video .author .sv-avatar {
    float: none;
    display: inline-block;
  }
  .single-video .author .sv-name {
    width: 100%;
    padding-left: 0;
    text-align: center;
    float: none;
  }
  .single-video .author .sv-name .c-sub {
    float: none;
    text-align: center;
    padding-bottom: 15px;
  }
  .single-video .author .sv-views {
    width: 100%;
    float: none;
  }
  .single-video .author .sv-views .sv-views-count {
    text-align: center;
  }
  .single-video .cl-comment .cl-avatar {
    width: 35%;
    padding-right: 15px;
  }
  .single-video .cl-comment .cl-comment-text {
    width: 65%;
  }
  .single-video .cl-comment .cl-comment-text .cl-flag {
    right: -10px;
  }
  .single-video .cl-comment-reply {
    margin-left: 5%;
  }
  .single-video .cl-comment-reply .cl-avatar {
    width: 35%;
    padding-right: 10px;
  }
  .single-video .cl-comment-reply .cl-comment-text {
    width: 65%;
  }
  .b-video {
    margin-bottom: 15px;
  }
  .b-video .v-img img {
    width: 100%;
  }
  .reply-comment .rc-ava {
    text-align: center;
    float: none;
    margin-bottom: 10px;
  }
}
@media (min-width: 768px) and (max-width: 1365px) {
  .sv-video img {
    width: 100%;
  }
  .similar-videos .videoitem {
    margin-bottom: 30px;
  }
  .similar-videos .videoitem img {
    width: 100%;
  }
  .single-video .reply-comment .rc-comment {
    width: 600px;
  }
  .single-video .adblock .img {
    width: 100%;
  }
  .single-video .adblock2 .img {
    width: 100%;
  }
}
/*
* Content Single Video END
*/
/*
* Content Categories
*/
.v-categories.side-menu .bg-add {
  position: absolute;
  top: 0;
}
.v-categories.side-menu .content-block .cb-header {
  margin-bottom: 0;
}
.v-categories.side-menu .content-block .cb-content {
  margin-bottom: 0;
}
.v-categories.side-menu .content-block .cb-content > .row > div {
  padding-top: 30px;
  padding-bottom: 40px;
}
.v-categories.side-menu .content-block .cb-content > .row > div:first-child {
  border-right: solid 1px #eceff0;
}
.v-categories.side-menu .content-block .cb-content > .row > div:last-child {
  padding-left: 30px;
  left: -1px;
  border-left: solid 1px #eceff0;
}
.v-categories.side-menu .content-block .cb-content .sidebar-menu ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
.v-categories.side-menu .content-block .cb-content .sidebar-menu ul li a {
  color: #7e7e7e;
}
.v-categories.side-menu .content-block .cb-content .sidebar-menu ul li a:hover {
  color: #ea2c5a;
}
.v-categories.side-menu .content-block .cb-content .sidebar-menu ul li:not(:first-child) {
  margin-top: 16px;
}
@media only screen and (max-width: 414px) {
  .v-categories.side-menu .content-block .cb-content > .row > div:nth-child(2) > .row > div {
    width: 100%;
  }
}
.content-block .cb-header .pull-right .btn-arrow {
  display: block;
  width: 8px;
  height: 8px;
  margin-top: 14px;
  border-top: solid 2px #637076;
  border-right: solid 2px #637076;
  cursor: pointer;
  -webkit-transform: rotate(-45deg);
  -moz-transform: rotate(-45deg);
  -ms-transform: rotate(-45deg);
  -o-transform: rotate(-45deg);
}
.content-block.subscription {
  border: none;
}
.content-block.subscription .sscr-user-info {
  position: relative;
  width: 100%;
  display: table;
  font-size: 0;
  margin-bottom: 30px;
}
.content-block.subscription .sscr-user-info .sscr-image,
.content-block.subscription .sscr-user-info .sscr-name,
.content-block.subscription .sscr-user-info .sscr-time-active {
  display: inline-block;
}
.content-block.subscription .sscr-user-info .sscr-name,
.content-block.subscription .sscr-user-info .sscr-time-active {
  font-size: 16px;
  vertical-align: -4px;
}
.content-block.subscription .sscr-user-info .sscr-image {
  max-width: 72px;
  margin-right: 28px;
}
.content-block.subscription .sscr-user-info .sscr-name {
  color: #2e2e2e;
  font-weight: 500;
}
.content-block.subscription .sscr-user-info .sscr-name:after {
  content: '.';
  margin: 0 4px;
}
.content-block.subscription .sscr-user-info .sscr-time-active {
  color: #7e7e7e;
  padding-right: 22px;
  margin-top: 10px;
}
.content-block.subscription .sscr-user-info .btn-close {
  position: absolute;
  display: block;
  right: -6px;
  top: 21px;
}
.content-block.subscription .sscr-user-info .btn-close i {
  font-size: 20px;
}
.content-block.subscription .videolist .videoitem {
  min-height: auto;
  margin-bottom: 8px;
}
.content-block.subscription .videolist .videoitem .v-views {
  padding-bottom: 0;
}
.content-block.subscription .cb-content {
  margin-bottom: 18px;
}
.content-block.subscription .cb-content:not(:first-child) {
  border-top: solid 1px #eceff0;
  padding-top: 32px;
}
/*
* FOOTER
*/

footer .list-inline {
  margin: 0;
  padding: 0;
}
footer .f-copy {
  color: #7e7e7e;
}
footer .f-copy a {
  color: #7e7e7e;
}
footer .f-copy a:hover {
  color: #ea2c5a;
}
footer .f-icon {
  width: 140px;
  font-size: 22px;
  color: #637076;
  padding-left: 15px;
}
footer .f-icon a {
  padding-right: 14px;
  color: #637076;
}
footer .f-icon a:hover {
  color: #ea2c5a;
}
footer .f-lang {
  padding-top: 30px;
}
footer .f-lang .btn-default {
  color: #2e2e2e;
  background-color: transparent;
  border: none;
}
/*
* FOOTER END
*/
body.dark .navbar-container,
body.dark .navbar-container2,
body.dark .content-block.head-div,
body.dark .content-block .cb-header,
body.dark .v-categories.side-menu .content-block .cb-content > .row > div:last-child,
body.dark .v-categories.side-menu .content-block .cb-content > .row > div:first-child,
body.dark footer,
body.dark .delimiter,
body.dark .c-details,
body.dark .h-divider,
body.dark .content-wrapper.head-div,
body.dark .caption,
body.dark .showless,
body.dark .showless a,
body.dark .list.similar-videos,
body.dark .loadmore,
body.dark .comments-list .cl-header,
body.dark .tabs-panel,
body.dark .tabs-content .tab-1 div:first-child,
body.dark .tabs-content .tab-2,
body.dark .tabs-content .tab-3,
body.dark .h-video,
body.dark .cb-content.videolist,
body.dark .u-details-wrap,
body.dark .channels-content .theme-section {
  border-color: #424242 !important;
}
body.dark .block-list div {
  border-color: #242424 !important;
}
body.dark .v-categories.side-menu .content-block .cb-content > .row > div:first-child {
  background-color: #242424 !important;
}

body.dark .navbar-container2 .h-resume {
  color: #7e7e7e;
}
body.dark .navbar-container2 .color-default {
  color: #a9a9a9;
}
body.dark .list-inline li a {
  color: #7e7e7e;
}
body.dark .list-inline li a:not(.color-active):hover {
  color: #a2abaf !important;
}
body.dark .list-inline.menu li a {
  color: #a9a9a9;
}
body.dark .f-copy .list-inline li a {
  color: #7e7e7e;
}
body.dark .f-copy .list-inline li a:hover {
  color: #a9a9a9;
}
body.dark .topsearch .input-group input,
body.dark .topsearch .input-group .input-group-addon,
body.dark .topsearch .input-group .input-group-btn {
  background-color: #3c3d3e;
}
body.dark i.fa,
body.dark i.cv,
body.dark .caret {
  color: #a2abaf;
}
body.dark .btn-arrow {
  border-color: #a2abaf !important;
}
body.dark .selectuser .btn-default {
  color: #a2abaf;
}
body.dark .btn.btn-default {
  color: #a9a9a9 !important;
}
body.dark .b-video .v-desc,
body.dark .b-playlist .v-desc,
body.dark .b-category .v-desc,
body.dark .h-video .v-desc,
body.dark .b-video .name,
body.dark .b-playlist .name,
body.dark .b-category .name,
body.dark .h-video .name,
body.dark .b-video .v-desc a,
body.dark .b-playlist .v-desc a,
body.dark .b-category .v-desc a,
body.dark .h-video .v-desc a,
body.dark .b-video .name a,
body.dark .b-playlist .name a,
body.dark .b-category .name a,
body.dark .h-video .name a {
  color: #a9a9a9;
}
body.dark .b-video .v-desc:hover,
body.dark .b-playlist .v-desc:hover,
body.dark .b-category .v-desc:hover,
body.dark .h-video .v-desc:hover,
body.dark .b-video .name:hover,
body.dark .b-playlist .name:hover,
body.dark .b-category .name:hover,
body.dark .h-video .name:hover,
body.dark .b-video .v-desc a:hover,
body.dark .b-playlist .v-desc a:hover,
body.dark .b-category .v-desc a:hover,
body.dark .h-video .v-desc a:hover,
body.dark .b-video .name a:hover,
body.dark .b-playlist .name a:hover,
body.dark .b-category .name a:hover,
body.dark .h-video .name a:hover {
  color: #ea2c5a;
}
body.dark .v-pagination .pages {
  background-color: #424242;
  color: #7e7e7e;
}
body.dark .v-pagination .pages i.cv {
  color: #90989b;
}
body.dark .v-pagination .pages:hover,
body.dark .v-pagination .pages.active {
  background-color: #666666;
  color: #ffffff;
}
body.dark .c-details .c-name {
  color: #a9a9a9;
}
body.dark .c-details .c-sub-wrap .c-s {
  border-color: #343434 !important;
}
body.dark .cb-search input {
  background-color: #424242;
  border-color: #424242;
  color: #7e7e7e !important;
}
body.dark .cns-block .cns-info {
  border-color: #242424 !important;
  background-color: #242424;
}
body.dark .cns-block .cns-info h5 {
  color: #a9a9a9 !important;
}
body.dark .cns-block .cns-img-small .cns-small-wrapp {
  background-color: #242424 !important;
}
body.dark .loadmore .btn {
  background-color: #424242 !important;
  border-color: #424242;
}
body.dark .loadmore .btn:hover {
  color: #ea2c5a !important;
  border-color: #ea2c5a;
}
body.dark .login-window .l-head {
  background-color: #242424;
  border-color: #424242 !important;
  color: #a9a9a9;
}
body.dark .login-window .l-form {
  background-color: #343434;
}
body.dark .login-window label,
body.dark .login-window .signuptext a {
  color: #a9a9a9;
}
body.dark .login-window input {
  background-color: #424242;
  border-color: #424242;
}
body.dark .s-s-title {
  color: #a9a9a9;
}
body.dark .caption .left a {
  color: #a9a9a9;
}
body.dark .caption .left a:hover {
  color: #ea2c5a;
}
body.dark .caption .right:hover a,
body.dark .caption .right:hover a i {
  color: #ea2c5a;
}
body.dark h1 a {
  color: #a9a9a9;
}
body.dark h1 a:hover {
  color: #ea2c5a;
}
body.dark .author {
  background-color: #242424;
  -webkit-box-shadow: 0px 2px 1px 1px #242424;
  -moz-box-shadow: 0px 2px 1px 1px #242424;
  box-shadow: 0px 2px 1px 1px #242424;
}
body.dark .author .sv-name a {
  color: #a9a9a9;
}
body.dark .author .c-sub .c-s {
  border-color: #424242 !important;
  background-color: #343434;
}
body.dark .author .sv-views-count {
  color: #a9a9a9;
}
body.dark .info h4 {
  color: #a9a9a9;
}
body.dark .sv-tags span {
  background-color: #242424 !important;
}
body.dark .sv-tags span a {
  color: #a9a9a9;
}
body.dark .sv-tags span a:hover {
  color: #ea2c5a;
}
body.dark .adblock .img,
body.dark .adblock2 .img {
  background-color: #3c3d3e;
}
body.dark .showless a {
  background-color: #424242;
  color: #7e7e7e;
}
body.dark .comments .reply-comment .rc-header {
  color: #a9a9a9;
}
body.dark .comments .rc-comment textarea {
  background-color: #424242;
  border-color: #424242;
}
body.dark .comments .comments-list .cl-header .c-nav .list-inline li a.active {
  color: #a9a9a9;
}
body.dark .comments .comments-list .cl-header .c-nav .list-inline li a:hover {
  color: #a9a9a9;
}
body.dark .comments .comments-list .cl-text {
  color: #a9a9a9;
}
body.dark .loadmore-comments form .btn.btn-default.h-btn {
  background-color: #424242;
  border-color: #424242;
}
body.dark .loadmore-comments form .btn.btn-default.h-btn:hover {
  color: #ea2c5a !important;
  border-color: #ea2c5a;
}
body.dark .tabs-panel a.active {
  background-color: #424242 !important;
}
body.dark .tabs-panel a.active,
body.dark .tabs-panel a.active i {
  color: #ea2c5a !important;
}
body.dark .tabs-panel a:hover,
body.dark .tabs-panel a:hover i {
  color: #ea2c5a !important;
}
body.dark .tabs-panel a i {
  color: #a2abaf !important;
}
body.dark .tabs-content .tab-2 i.fa,
body.dark .tabs-content .tab-2 i.fa:hover {
  color: #ffffff !important;
}
body.dark .tabs-content .tab-2 i.fa.fa-reddit {
  color: #5f99cf !important;
}
body.dark .tabs-content input,
body.dark .tabs-content textarea {
  background-color: #424242;
  color: #7e7e7e;
  border-color: #424242;
}
body.dark .tabs-content .tags-type2 a,
body.dark .tabs-content .tags-type1 a {
  background-color: #242424;
  border-color: #242424;
}
body.dark .tabs-content .tags-type2 a,
body.dark .tabs-content .tags-type2 a i {
  color: #a9a9a9;
}
body.dark .tabs-content .tags-type2 a:hover {
  background-color: #3c3d3e;
}
body.dark label.checkbox {
  background-color: #424242;
  border-color: #424242;
}
body.dark .block-list div.active {
  border-color: #ea2c5a !important;
}
body.dark .block-list div.active span {
  color: #a9a9a9 !important;
}
body.dark .list .v-number {
  color: #666666;
}
body.dark .block-list > div:nth-child(odd) {
  background-color: #424242 !important;
}
body.dark .block-list > div.active i {
  color: #ea2c5a;
}
body.dark .sscr-user-info .sscr-name {
  color: #a9a9a9 !important;
}
body.dark .u-area .u-text1 {
  color: #a9a9a9 !important;
}
body.dark .cv.cvicon-cv-upload-video {
  color: #a2abaf !important;
}
body.dark .form-group label {
  color: #a9a9a9;
}
body.dark .form-group input,
body.dark .form-group textarea,
body.dark .form-group select {
  background: #424242;
  border-color: #424242;
  color: #7e7e7e;
}
body.dark .u-details .ud-caption {
  color: #a9a9a9;
}
body.dark .u-details .cvicon-cv-cancel {
  color: #a2abaf;
}
body.dark .u-details .cvicon-cv-cancel:hover {
  color: #ea2c5a;
}
body.dark .u-details .u-title {
  color: #a9a9a9;
}
body.dark .clipboard .btn-copy {
  background-color: #242424;
  color: #a9a9a9;
}
body.dark .clipboard .btn-copy:hover {
  background-color: #343434;
}
body.dark .loginsignup a {
  color: #a9a9a9;
}
body.dark .channels-content h4 {
  color: #a9a9a9;
}
body.dark .btn-view-more:hover {
  color: #a9a9a9 !important;
}
body.dark .c-sub-wrap .c-s {
  background-color: #424242;
  border-color: #424242;
}
body.dark .topsearch .input-group i.fa:hover,
body.dark .topsearch .input-group i.cv:hover {
  color: #a2abaf !important;
}
.u-form .u-category {
  color: #a9a9a9 !important;
}
i.fa:hover,
i.cv:hover {
  color: #ea2c5a !important;
}
.b-video .v-desc:hover,
.b-playlist .v-desc:hover,
.b-category .v-desc:hover,
.v-desc .v-desc:hover,
.b-video .name:hover,
.b-playlist .name:hover,
.b-category .name:hover,
.v-desc .name:hover,
.b-video .v-desc:hover a,
.b-playlist .v-desc:hover a,
.b-category .v-desc:hover a,
.v-desc .v-desc:hover a,
.b-video .name:hover a,
.b-playlist .name:hover a,
.b-category .name:hover a,
.v-desc .name:hover a {
  color: #ea2c5a !important;
}
.upload-button i.cv.cvicon-cv-upload-video {
  color: white !important;
}
.upload-button:hover i.cv.cvicon-cv-upload-video {
  color: #2cce8f !important;
}
.color-active {
  color: #ea2c5a !important;
}
.color-active > a {
  color: #ea2c5a !important;
}
.c-social i.fa {
  color: white !important;
}
.transform {
  -moz-transition: transform 1s;
  -webkit-transition: transform 1s;
  transition: transform 1s;
}
.flip{
  transform: rotate(180deg);
}

.img-hover{
  opacity: 0.8;
  filter: alpha(opacity=80); /* For IE8 and earlier */
  box-shadow: 0 1px 2px rgba(0,0,0,0.15);
  transition: box-shadow 0.3s ease-in-out;
  transition: 0.4s ease;
}

.img-hover:hover{
  opacity:1;
  filter: alpha(opacity=100);
  box-shadow: 0 8px 17px rgba(0,0,0,0.3);
  transition: 0.4s ease;
}

.blinking {
  color:darkred;
  animation: blinker 1s linear infinite;
}

@keyframes blinker {
  50% { opacity: 0; }
}


div.wrapper-details{
  float:left; /* important */
  position:relative; /* important(so we can absolutely position the description div */
}
div.description{
  position:absolute; /* absolute position (so we can position it where we want)*/
  bottom:0px; /* position will be on bottom */
  left:0px;
  paadding:10px;
  width:100%;
  /* styling bellow */
  background: -webkit-linear-gradient(bottom, rgba(0,0,0,0), rgba(0,0,0,1)); /* For Safari 5.1 to 6.0 */
  background: -o-linear-gradient(bottom, rgba(0,0,0,0), rgba(0,0,0,1)); /* For Opera 11.1 to 12.0 */
  background: -moz-linear-gradient(bottom, rgba(0,0,0,0), rgba(0,0,0,1)); /* For Firefox 3.6 to 15 */
  background: linear-gradient(to bottom, rgba(0,0,0,0), rgba(0,0,0,1)); /* Standard syntax (must be last) */
  color:white;
  filter:alpha(opacity=80); /* IE transparency */
}
p.description_content{
  padding-top:17px;
  padding-left:5px;
  margin:0px;
  font-size: 15px;
  color:white;
  font-weight: bold;
}
.big{
  font-size: 20px;
}
.fa-star{
 color:yellow;
}



.titleSection{
  font-size: 23px;
  background: radial-gradient(ellipse at top,#DD3335,#720101 89%,#8F0707);
  padding: 8px 12px;
  border-radius: 6px;
  box-shadow: 0px 1px 4px #000;
  position: relative;
  font-weight: normal;
  bottom: 3px;
  overflow: hidden;
  color: #fff;

}#titleMovie{
   font-size: 11px;
   background: radial-gradient(ellipse at top,#DD3335,#720101 89%,#8F0707);
   padding: 8px 12px;
   border-radius: 6px;
   box-shadow: 0px 1px 4px #000;
   position: relative;
   font-weight: normal;
   bottom: 3px;
   overflow: hidden;
   color: #fff;
}


.img__wrap{

  position: relative;
}

.img__description_layer {
  font-size: 13px;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;

  color: #fff;
  visibility: hidden;
  opacity: 0;
  display: flex;
  align-items: center;
  justify-content: center;

  /* transition effect. not necessary */
  transition: opacity .2s, visibility .2s;
}

.img__wrap:hover .img__description_layer {
  visibility: visible;
  opacity: 1;
}

.img__description {
  transition: .2s;
  transform: translateY(1em);
}

.img__wrap:hover .img__description {
  transform: translateY(0);
}


#movetitle{
  font-size:30px;
  margin-bottom: 53px;
  margin-left: 23px;
}


#menuList {
  overflow: scroll;
  width: 267px;
  height: 692px;
  margin-top: 69px;
  border-radius: 17px;
  font-size: 16px;
  text-align: center;

}

.sectionTop{
padding-top: 22px;
}
.sectionTop .filmBlock {
  list-style: none;
  height: 355px;
  width: 100%;
  border: 1px solid #ddd;
  float: left;
  position: relative;
  transition: .3s height ease,.3s margin-top ease;
  margin-left: 8px;
  overflow: hidden;
}


.sectionTop .filmBlock img {
  width: 100%;
  height: 100%;
  transition: .3s all ease;
  position: relative;
  z-index: 2;
}

.sectionTop .filmBlock span {
  background-color: #cc0000!important;
}
.sectionTop .filmBlock .views {
  background-color: #ffffff!important;
}

.moviefilm .movief a {
  color: #fefafa!important;
}


.videoitem{
  margin-bottom: 12px;
  margin-left: 4px;
  /*box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.49);*/
  direction: rtl;
  position: relative;
  width: 225px;
  height: 350px;
  display: inline-block;
}

#movieImage
{
  width: 225px;
  height: 350px;
  margin-right: -13px;
}

.slideEffect{
  position: absolute;
  z-index: 9999;
  margin-top: -96px;
  background: #262b36;
  height: 96px;
  width: 225px;
  margin-right: -13px;
  display: none;
}

.slideEffect-Cat{
  position: absolute;
  z-index: 9999;
  display: none;
}

.rating{
  position: absolute;
  bottom: 10px;
  transition: .3s all cubic-bezier(0.56, 0.28, 0.34, 1.34);
  left: 10px;
  font-size: 16px;
  background: #3A4150;
  color: #BDBDBD;
  padding: 4px 8px;
  border-radius: 2px;
}

.watched{
  position: absolute;
  padding: 6px 6px 6px 6px;
  color: #ffffff;
  font-size: 13px;
  line-height: 13px;
  font-weight: 500;
  border-radius: 2px;
  background-color: #373933;
}
