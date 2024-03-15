
    <div class='dog'>
        <div class='ears2'></div>
        <div class='head2'>
            <div class='eyes2'></div>
            <div class='nose2'></div>
        </div>
        <div class='body2'>
            <div class='left-paw2'></div>
            <div class='right-paw2'></div>
        </div>
        <div class='tail2'></div>
        <div class='ORlaptop'>
            <div class='ORscreen'></div>
            <div class='ORkeyboard'></div>
        </div>
    </div>

<style>

    .dog {
        height: 182px;
        margin-top: 10px;
        
        margin-left: 20px;
        transform: translate(0, -50%);
    }
    .ears2 {
        height: 0;
        width: 0;
        position: relative;
        left: 30px;
        border-bottom: 27px solid #f07e42;
        border-left: 23px solid transparent;
        border-right: 10px solid transparent;
        &::before {
        display: block;
        content: "";
        height: 0;
        width: 0;
        position: relative;
        left: 33px;
        border-bottom: 27px solid #f07e42;
        border-left: 10px solid transparent;
        border-right: 23px solid transparent;
        }
    }
    .head2 {
        height: 74px;
        width: 140px;
        position: relative;
        z-index: 2;
        box-shadow: 8px 0 0 #f07e42;
        border-radius: 35px;
        background: #ffa852;
    }
    .eyes2 {
        height: 12px;
        width: 12px;
        position: relative;
        top: 37px;
        left: 50px;
        border-radius: 100%;
        animation: 9s dogRead infinite;
        background: black;
        &::before {
            display: block;
            content: "";
            height: 12px;
            width: 12px;
            position: relative;
            left: 18px;
            border-radius: 100%;
            background: black;
        }
    }
    .nose2 {
        height: 30px;
        width: 48px;
        position: relative;
        top: 40px;
        left: 37px;
        border-radius: 20px;
        background:  #fbf1d8;
        &::before {
            display: block;
            content: "";
            height: 0;
            width: 0;
            position: relative;
            top: 3px;
            left: 9px;
            border-radius: 15px;
            border-top: 12px solid black;
            border-left: 12px solid transparent;
            border-right: 10px solid transparent;
        }
        }

    .body2 {
        height: 110px;
        width: 200px;
        position: relative;
        top: -30px;
        z-index: 1;
        border-radius: 55px;
        background: #ffa852;
    }
    .left-paw2 {
        height: 25px;
        width: 37px;
        position: relative;
        top: 70px;
        left: 15px;
        border-radius: 12px;
        animation: 9s dogLeftType infinite;
        background: #fbf1d8;
    }
    .right-paw2 {
        height: 25px;
        width: 37px;
        position: relative;
        top: 45px;
        left: 60px;
        border-radius: 12px;
        animation: 9s dogRightType infinite;
        background: #fbf1d8;
    }
    
    .tail2 {
        height: 34px;
        width: 70px;
        position: relative;
        top: -64px;
        left: 150px;
        z-index: 0;
        border-radius: 0 17px 17px 0;
    }
    .ORlaptop {
        position: relative;
        top: -161px;
        left: -103px;
        z-index: 2;
    }
    .ORscreen {
        height: 85px;
        width: 130px;
        border-radius: 8px;
        transform: skew(18deg);
        background:  #ffca95;
        &::before {
            display: block;
            content: "";
            height: 17px;
            width: 10px;
            position: relative;
            top: 38px;
            left: 50px;
            border-radius: 6px;
            background: #f07e42;
        }
        &::after {
            display: block;
            content: "";
            height: 17px;
            width: 10px;
            position: relative;
            top: 21px;
            left: 64px;
            border-radius: 6px;
            background: #f07e42;
        }
    }
    .ORkeyboard {
        height: 12px;
        width: 132px;
        position: relative;
        left: 14px;
        border-radius: 6px 0 0 6px;
        background: #f07e42;
        &::before {
            display: block;
            content: "";
            height: 12px;
            width: 72px;
            position: relative;
            left: 128px;
            border-radius: 6px;
            background: #ffca95;
        }
    }

@keyframes dogLeftType {
    50% {
        transform: none;
    }
    52% {
        transform: translateY(-8px);
    }
    56% {
        transform: none;
    }
    58% {
        transform: translateY(-8px);
    }
    60% {
        transform: none;
    }
    64% {
        transform: translateY(-8px);
    }
    66% {
        transform: none;
    }
    68% {
        transform: translateY(-8px);
    }
    70% {
        transform: none;
    }
    72% {
        transform: translateY(-8px);
    }
    76% {
        transform: none;
    }
}

@keyframes dogRightType {
    54% {
        transform: none;
    }
    56% {
        transform: translateY(-8px);
    }
    58% {
        transform: none;
    }
    60% {
        transform: translateY(-8px);
    }
    62% {
        transform: none;
    }
    66% {
        transform: translateY(-8px);
    }
    68% {
        transform: none;
    }
    70% {
        transform: translateY(-8px);
    }
    72% {
        transform: none;
    }
    74% {
        transform: translateY(-8px);
    }
    78% {
        transform: none;
    }
}

@keyframes dogRead {
    5% {
        transform: none;
    }
    17% {
        transition-timing-function: ease-out;
        transform: translateX(-5px);
    }
    25% {
        transform: none;
    }
    37% {
        transition-timing-function: ease-out;
        transform: translateX(-5px);
    }
    45% {
        transform: none;
    }
}
</style>
