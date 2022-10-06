/* INFO */
/* This CSS was made by irrvlo */
/* Works only in fullscreen, preferably in 1080p */
/* This CSS is VERY sloppy, I recommened to not edit this */
/* Version: 1.0.0 */
/* Last Updated 8:07 PM CST | 9/21/2022 */
/* Log: Finished CSS, Uploaded. */
/* Custom Font */
@font-face {
    font-family: customFont;
    src: url(https://rawcdn.githack.com/irrvlo/irrvlo.github.io/1cb7fdc534cb3cc9ca4ab69c2522ec1392aa8629/CSS/irrvlo/Fonts/TruenoRg.otf)
}

* {
    font-family: customFont !important;
}

/* AD Block */
#ad-bottom,
#ad-left {
    width: 0px !important;
}


/* General */
.crosshair-static {
    visibility: visible !important;
    position: absolute;
    display: flex !important;
}

.alert-default {
    background: linear-gradient(262.54deg, #252526eb 9.46%, #0f0f0f 100.16%) !important;
    border: transparent !important;
    backdrop-filter: blur(5px);
    border-radius: 10px !important;
}

.bottom,
.center,
.top {
    background: transparent !important;
}

.searching-game {
    position: absolute;
    top: -4vh !important;
    width: 100vw !important;
    z-index: -0 !important;
    padding-right: 50px;
    padding-left: 50px;
    padding-top: 475px;
    padding-bottom: 500px;
    backdrop-filter: blur(15px);
    background: #ffffff2b !important;
}

#app > div.game-interface > div.container-pre-end > div.bg {
    z-index: -0 !important;
    backdrop-filter: blur(15px);
    background: #ffffff2b !important;
}

.button {
    font-family: customFont !important;
    text-shadow: 0 0 0 #0000 !important;
    -webkit-text-stroke: 0px white !important;
}

::-webkit-scrollbar-thumb {
    background-color: #51515126 !important;
}

.nav.active {
    background-color: transparent !important;
}


.tab.active,
.active-tab,
.active {
    background-color: #5353534a !important;
    color: #ffffff !important;
    border: transparent !important;
}

.tab.end,
.tab,
.tabs {
    color: #fff9 !important;
}

.friend,
.exit,
.exit:after,
.item-content,
.item,
.background {
    background-color: transparent !important;
    --hover-color: transparent !important;
    --top: transparent !important;
    --bottom: transparent !important;
    border-bottom: transparent !important;
    border: transparent !important;
    box-shadow: 0 0 0 transparent !important;
}

.tab-bar,
.tab:hover,
.top-bar {
    background: transparent !important;
    background-color: transparent !important;
    border: transparent !important;
    color: #ffffff !important;
    box-shadow: 0 0 0 transparent !important;
}

.avatar {
    border: solid 4px rgb(43, 53, 78) !important;
}

hr,
#app > div.end-modal > div.bottom,
#app > div.end-modal > div.content > div.chat > div.chat.chat-position > div.messages.messages-cont,
.card-cont,
.left-cont,
#app > div.game-interface > div.container-pre-end > div.left-cont > div,
.center-cont,
#app > div.game-interface > div.container-pre-end > div.center-cont > div,
.right-cont,
#app > div.game-interface > div.container-pre-end > div.right-cont > div,
.kill-bar-item,
.user-card,
.timer.bg.text-1,
.kill.bg.text-1,
.death.bg.text-1,
#app > div.game-interface > div.desktop-game-interface > div.chat.chat-position > div.messages.messages-cont,
.bg-level,
.description,
.select-regions-cont,
.select-mods-cont,
.container-card,
.tab,
#view > div > div > div.content > div > div.left > div.bottom,
.limit,
.delete,
.head-text,
.add-friends,
.time-left,
.rewards,
.left.active,
.join,
.server,
.messages-cont.small,
.box,
.live-streams,
.card-list,
.loader,
.list-container,
#view > div > div > div.content > div > div.clans > div.my-clan > div.card-cont,
.reset-time,
.card,
.clans,
.tabs,
.close,
.name-page,
.home,
.container {
    background: linear-gradient(103.28deg, #1a1a1aa1 7.06%, #3737374a 90.75%) !important;
    background-color: transparent !important;
    border: transparent !important;
    box-shadow: 0 0 0 transparent !important;
    backdrop-filter: blur(10px)
}

/* Chat */
.name,
.lvl {
    color: #ffffff!important;
}


/* Main Menu */

#clientJoinButton {
left: -85px !important;
top: -60px !important;
background-color: #ffb91400 !important;
--hover-color: #fcd37300 !important;
--top: #fcd37300 !important;
--bottom: #b6830e00 !important;
-webkit-text-stroke: 1px #0000 !important;
box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px !important;
}

.level-progress {
    background: #3535359c !important;
}

#app > div.end-modal,
#app > div.interface.text-2 > div.background {
    background: url(https://media.discordapp.net/attachments/962475357750042655/1021403006215929907/Untitled.png?width=1920&height=1080) no-repeat center center fixed;
    background-size: cover;
}

.join-using-link,
.circle,
.instruction,
.list-weapons,
.info-key-cont,
.border,
.borders,
#app > div.interface.text-2 > div.background > div.bg-radial,
#app > div.interface.text-2 > div.background > div.pattern-bg,
#play-btn > div.triangle,
#left-icons > div.icon-btn.text-1.HUB > div > svg,
#icon-store > div > svg,
#left-icons > div.icon-btn.text-1.SERVERS > div > svg,
#left-icons > div.icon-btn.text-1.QUESTS > div > svg,
#left-icons > div.icon-btn.text-1.FRIENDS > div > svg,
#left-icons > div.icon-btn.text-1.INVENTORY > div > svg,
#left-icons > div.icon-btn.text-1.MAP > div > svg,
.bg-light,
.background-leaders,
.triangle,
.rules,
.rules-label,
.rules-icon,
.top-logo,
.bottom-logo,
#logo {
    display: none !important;
}

#view > div > div > div.content > div > div > div.preview.text-2 > div > div.bottom > div > div.description {
    background: transparent !important;
}


.rules-icon {
    color: transparent !important;
    background: transparent !important;
}


#left-icons {
    top: 61rem !important;
    flex-direction: row;
    backdrop-filter: blur(5px);
    background: #00000061 !important;
}


#left-icons > div.icon-btn.text-1.FRIENDS,
#left-icons > div.icon-btn.text-1.INVENTORY,
#left-icons > div.icon-btn.text-1.HUB,
#icon-store,
#left-icons > div.icon-btn.text-1.SERVERS,
#left-icons > div.icon-btn.text-1.QUESTS,
#left-icons > div.icon-btn.text-1.MAP {
    padding: 35px;
    padding-bottom: 47px;
    width: 274.3px;
    border: none;
    border-bottom: none;
    border-top: none;
    background: #00000061 !important;
    backdrop-filter: blur(5px);
}

#play-btn {
    transform: none;
    left: -660px;
    top: -86px;
    height: 95px;
    width: 548.6px;
    background-color: #0a0a0abd !important;
    --hover-color: #0a0a0abd !important;
    --top: #0a0a0abd !important;
    --bottom: #0a0a0abd !important;
}

#play-btn > div.borders {
    display: none;
}

#play > div > div.play-content-up > label > span::before,
#play-btn::before {
    display: none;
}

#play > div > div.play-content-up {
    left: -790px !important;
    position: absolute;
}

#play > div > div.play-content-up > div {
    left: 310px;
    position: absolute;
    top: -120px;
    width: 264px;
}

#play > div > div.select-region {
    left: -78px !important;
    top: -25px;
    position: absolute;
}

#play > div > div.play-content-up > label > span {
    position: absolute;
    top: -21px;
    right: 455px;
}

#auth-user > div > div.card-cont.avatar-info {
    padding-left: 1870px;
    padding-right: 50px;
    background: #00000061;
    backdrop-filter: blur(5px);
    border: transparent;
}

#auth-user > div > div.card-cont.user-info {
    right: 104px;
    position: absolute;
    background: transparent;
    backdrop-filter: blur(5px);
    border: transparent;
}

#left-interface > div.moneys {
    position: absolute;
    left: -65px;
    top: 20px;
}

#left-interface > div.moneys > div:nth-child(1),
#left-interface > div.moneys > div.card-cont.money.diamonds {
    background: #00000061;
    backdrop-filter: blur(5px);
    border: transparent;
}

#auth-user {
    z-index: 0;
}

#right-interface {
    z-index: 5;
}

#settings-and-socicons {
    position: absolute;
    left: -750px;
    top: 20px;
}

#dailyQuests {
    position: absolute;
    top: 114px;
    height: 1080px;
    background: #00000061;
    backdrop-filter: blur(5px);
    border: transparent;
    width: 350px;
}

#team-section {
    background: #00000061;
    backdrop-filter: blur(5px);
    top: 143px;
    left: -784.5px;
    padding-top: 150px;
    padding-bottom: 500px;
}

#team-section > div.player {
    width: 350px;
}

.nickname,
.lvl,
.level-label,
.level-cont,
.reward,
.lvl-leader,
.level-value,
.level,
.levels {
    color: #ffffff !important;
    background: transparent !important;
    border: transparent !important;
}

#play > div > div.select-region,
#play > div > div.play-content-up > div {
    background: transparent;
    border: transparent;
}

#view > div > div > div.content > div > div.content > div.bg-progress > div.levels > div > div.progress > div,
#view > div > div > div.content > div > div.content > div.bg-progress > div.levels > div > div.progress,
.progress-helper {
    background: #fff !important;
    box-shadow: inset 0 0 0.612rem 0.25rem #0000004f !important;
}

.progress,
.quest,
.tip {
    background-color: #181818 !important;
}

.progress-line {
    background-color: #323232a1 !important;
}

.nickname {
    color: white !important;
}

.clan,
.label,
.label-primary,
.clan-tag {
    color: #d0cfcf !important;
}

.input .items div:hover {
    background-color: #c3c3c336 !important;
}

.input,
.items,
.card-cont.settings.card-1,
.card-cont.soc-group {
    background: transparent !important;
    border: transparent !important;
}

#view > div > div > div.content > div > div.quests > div.subjects > .subject {
    width: 1000px !important;
}


#dailyQuests > div.subjects > .subject {
    width: 350px !important;
}

/* MODE SELECTION */
.custom-checkbox > span:before {
    background-color: transparent !important;
    border: transparent !important;
}

.select-mods-cont {
    right: -173px !important;
    width: 621px !important;
    top: -607px !important;
    height: 552px !important;
}

.select-mods-maps {
    height: 360px!important;
}

.select-regions-cont {
    right: 305px !important;
    top: -119px !important;
}

/* HUB */
.awards-span,
.number-player {
    color: #ffff !important;
}

.subjects,
.info-awards {
    background-color: #00000036 !important;
    border: transparent !important;
}

.list,
.champions-list,
.top-items,
.list-cont.list-players {
    background-color: #1e1e1e59 !important;
}

.subject {
    width: 277px !important;
    backdrop-filter: blur(5px) !important;
    background: linear-gradient(103.28deg, #393838a1 7.06%, #37373724 90.75%) !important;
}

.rar-skin {
    position: absolute !important;
    top: 52px !important;
    left: 135px !important;
    height: 100% !important;
    border-radius: 5px !important;
    transform: rotate(90deg) !important;
    width: 0.4499999999999993rem;
}

.title,
.changelog-item,
.head {
    background: transparent !important;
    border: transparent !important;
}

#view > div > div > div.content > div > div > div.preview.text-2 > div > div.bottom > button,
.btn-invite,
.right-btn,
#view > div > div > div.content > div > div.content > div.subjects > div > button,
button.join-my-game-btn.rectangle,
.btn,
.button.buy-skin-weapon,
.button.buy-skin-weapon:after,
div.hover-btns-group > button:after,
div.hover-btns-group > button {
    background-color: #4242422e !important;
    --top: transparent !important;
    --bottom: transparent !important;
    border-bottom: transparent !important;
    border: transparent !important;
    box-shadow: 0 0 0 transparent !important;
    border-radius: 2px !important;
}

.hover-btns-group:hover {
    z-index: 3 !important;
}

#view > div > div > div.content > div > div > div.preview.text-2 > div > div.bottom > button,
.btn-invite,
.right-btn,
#view > div > div > div.content > div > div.content > div.subjects > div > button,
button.join-my-game-btn.rectangle,
.btn,
.button.buy-skin-weapon,
.button.buy-skin-weapon:hover,
.hover-btns-group:hover,
.hover-btns-group > button:hover {
    background: #ffffff2e !important;
    backdrop-filter: blur(10px) !important;
    --hover-color: #ffffff1f !important;
}

/* STORE */
#carousel {
    width: 116% !important;
}

#carouselUniques {
    width: 200% !important;
}

.price {
    background-color: transparent !important;
    border: transparent !important;
}

#carouselUniques > div.slider-container.swiper-container-horizontal > div.slider-touch > div > div > div > div.store-skins > div.weapons > .weapon {
    background: radial-gradient(39.78% 145.24% at 54.34% 55.56%, #171717 0, #202020 100%) !important;
    border: transparent !important;
}

.grad-weapon.epic {
    z-index: 2 !important;
}

.grad-weapon {
    width: 0.938rem !important;
    transform: rotate(90deg) !important;
    top: 60px !important;
    position: absolute !important;
    left: 165px !important;
    height: 100% !important;
    border-radius: 20px !important;
}

/* SERVERS */
button.join-my-game-btn.rectangle,
button.join {
    --hover-color: transparent !important;
    --top: transparent !important;
    --bottom: transparent !important;
}

.available-rooms,
.online,
.mod-name {
    color: #fff !important;
}

/* QUESTS */
#dailyQuests div.quest > div.left {
    width: 10px !important;
    height: 142px !important;
    right: 166px !important;
    border-radius: 20px !important;
    top: -63px !important;
    position: absolute !important;
    transform: rotate(90deg) !important;
    display: flex;
}

div.quest > .left {
    width: 15px !important;
    min-height: 100% !important;
    right: 450px !important;
    height: 770px !important;
    border-radius: 20px !important;
    top: -376px !important;
    position: absolute !important;
    transform: rotate(90deg) !important;
    display: flex;
}

/* FRIENDS */
.no-requests {
    color: #bfbfbf !important;
}

/* INVENTORY */
.gun {
    background: linear-gradient(251.44deg, #242424cc 1.13%, #95959508) !important;
}

#view > div > div > div.content > div > div.left {
    background: linear-gradient(103.28deg, #22222224 7.06%, #cecece26 90.75%) !important;
}

#view > div > div > div.content > div.inventory {
    display: flex;
    height: 94vh !important;
    max-height: 61rem !important;
    width: 119rem !important;
}


#view > div > div > div.content > div > div.left,
#view > div > div > div.content > div > div.left > div.bottom {
    width: 38% !important;
}

#view > div > div > div.content > div > div.content {
    width: 60.75% !important;
}

#view > div > div > div.content > div > div.content > div.subjects > div > button {
    z-index: 3 !important;
}

/* LOADING */
#app > div.loading-scene > div.content.team > div.players.text-1.players-2 {
    right: 525px !important;
}

.logo {
    left: 700px !important;
}

.loading {
    right: 50px !important;
}

.player {
    background: #0f0f0f6b !important;
    border-radius: 10px !important;
}

/* PAUSE MENU */
.right-container {
    background: #00000082 !important;
    backdrop-filter: blur(5px) !important;
    border-radius: 50px !important;
}

.red,
.blue {
    border-radius: 5px !important;
}

.gun {
    border: transparent !important;
}

/* HUD */
.hp {
    position: absolute !important;
    top: -30px !important;
    right: -720px !important;
}

.cont-endurance {
    top: -50px !important;
    width: 100% !important;
    position: absolute !important;
    right: -720px !important;
}

.endurance-progress {
    background: #fff !important;
}

.cont-endurance,
.cont-hp,
.hp-title {
    background: rgba(0, 0, 0, .34) !important;
}

#app > div.game-interface > div.desktop-game-interface > div.chat.chat-position {
    left: 0;
    bottom: -0.6999999999999993rem;
}

.JOIN {
    color: #5b8c40 !important;
}

.LEAVE {
    color: #b52f2f !important;
}

.tab-info {
    background: #00000075 !important;
}

#app > div.game-interface > div.desktop-game-interface > div.tab-info > div.players > div.list,
#app > div.game-interface > div.desktop-game-interface > div.tab-info > div.players > div > div.player-list.player-left-cont > div.list,
#app > div.game-interface > div.desktop-game-interface > div.tab-info > div.players > div > div.player-list.player-right-cont > div {
    background: transparent !important;
}

.list {
    color: white !important;
}

.user-card {
    border-radius: 25px !important;
}

/* End Screen */
