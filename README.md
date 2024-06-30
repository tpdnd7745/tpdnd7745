
<html>
	
	<script src="http://code.jquery.com/jquery-latest.js"></script>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<style>



		body{margin: 0;
            background: white;
        }
    
        
       

		
        @media screen and (max-width:1300px) {
			.main-poto-1{ 
                scale: 0.8;
                
            }
		}
        @media screen and (max-width:900px) {
			
            .main-text{
                float: left;
                margin-left: 70px;
            }
            
		}
        @media screen and (max-width:500px) {
			
            .main-2-center{
                font-size: 30px;
                 margin-left: -40px;
            }
            
		}
     

        .loding{
            width: 100%;
            height: 100%;
            position: fixed;
            left: 0px;
            top: 0px;
            background: white;
            z-index: 10000;
            text-align: center;
            font-size: 35px;
            font-family: 'DeogonPrincess';
            padding-top: 20%;
            transition: 1.0s;
        }
        /* ----------------------------------로딩화면------------------------------------ */
       
         
        .main-main{
            width: 100%;
            height: 100%;
            

        }
       .main{
            width: 20%;
            height: 500px;
            background: #d2d2d2;
            border-radius: 30px;
            transition: 0.5s;
            margin: 5%;
            float: left;
            transform: rotateX(0deg) rotateY(0deg);
        }
        
        &:hover { transform: scale3d(1.05, 1.05, 1.05) ;}

        #frame {
            width: 450px;
            height: 300px;
            transition: transform 200ms;
            margin: 0 auto;
         
        }

        #card {
            width: 100%;
            height: 100%;
            border-radius: 9px;
            background-image: url("https://media.discordapp.net/attachments/357810988550062081/1029980426791571526/unknown.png?width=1238&height=629");
            background-position: center;
            background-size: cover;
            background-repeat: no-repeat;
            box-shadow: 0 0 10px 2px rgba(0, 0, 0, 0.1);
            position: relative;
            transition-duration: 250ms;
            transition-property: transform, box-shadow;
            transition-timing-function: ease-out;
        }

        #light {
            position: absolute;
            width: 100%;
            height: 100%;
            border-radius: 9px;
        }
        .main-menu .on{
            margin-left: 300px;
        }
        /* ---------------------------메뉴-----------------------------------  */


        
        
        /* ---------------------------메인1-----------------------------------  */
        .main-1{
            width: 100%;
            height: 2000px;
            border-bottom: 3px solid white;
            background: white;
        }
        .main-1-1{
            background: #fff;
            width: 100%;
            height: 110%;
            opacity: 0.9;
            
        }
        .logo{
            color: black;
            font-size: 22px;
            opacity: 1;
            font-family: cursive;
            font-weight: bold;
            padding: 30px;
            position: fixed;
        }
        .logo2{
            color: #0000003d;
            font-size: 22px;
            position: absolute;
            font-family: cursive;
            font-weight: bold;
            padding: 7px;
            margin: -28px 0px 0 -3px;
        }
        .main-1-center{
            width: 250px;
            height: 140px;
            border: 4px solid black;
            border-radius: 5%;
            margin: 300px auto;
            text-align: center;
            font-weight: bold;
            opacity: 1;
            transition: 0.1s;
            transform: scale(1);
            
        }
        .center-1{
            color: #000;
            margin: 18px;
            font-size: 21px;
            
        }
        .center-2{
            color: #000;
            margin: 10px;
            font-size: 35px;
            font-family: 'DeogonPrincess';
            font-weight: normal;
            font-style: normal;
        
        }
        .main-center{
            position: fixed;
            width: 100%;
            transition: 0.6s;
        }
        .main-2-center{
            width: 600px;
            height: 140px;
            border-radius: 5%;
            margin: -300px auto;
            text-align: center;
            opacity: 0;
            font-size: 40px;
            transition: 0.5s;

        }
        .main-1-scroll{
            width: 100%;
            height: 115px;
            position: fixed;
            bottom: 0;
            margin: 0 auto;
            

        }
        .scroll{
            width: 1px;
            height: 50px;
            margin: 0 auto;
            background: #d2d2d2;
        }
        .scroll-text{
            text-align: center;
        }
        @font-face {
            font-family: 'DeogonPrincess';
            src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2205@1.0/DeogonPrincess.woff2') format('woff2');
            font-weight: normal;
            font-style: normal;
        }


        /* ---------------------------메인2-----------------------------------  */
        .main-2{
            width: 100%;
            height: 100%;
            background: black;
        }
        .main-poto-1{
            width: 500px;
            height: 500px;
            float: left;
            border-radius: 50%;
            shape-outside: circle();
            margin: 4vw;
            background: url("https://cdn.discordapp.com/attachments/357810988550062081/1028953034681757736/unknown.png");
            background-size: 100%;
            border: 2px solid #8cffab;
            background-position: center;
            transition: 1.0s;
            display: block;

        }
        
        .main-text{
            color: white;
            padding-top: 50px;   
            width: auto;
            height: auto;

        }
        .main-text1{
            font-size: 25px;
            margin-top: 10px;
            
        }
       
        .main-poto-2{
            width: 200px;
            height: 200px;
            background:  white;
            
            border-radius: 10%;
            float: right;
            margin: 30px;
        }
        

        
        /* ---------------------------메인3-----------------------------------  */

        .main-3-text{
            color: white;
            font-size: 30px;
            
        }
        .main-3{
            width: 100%;
            height: 100%;
            background: black;
        }
        .main-3-skill{
            width: 1400px;
            height: 600px;
            background: black;
            margin: 0 auto;
        }
        .main-3-skill-1{
            background: white;
            width: 10%;
            height: 70%;
            margin: 5%;
            float: left;

        }
        /* ---------------------------메인4-----------------------------------  */

        .main-4{
            width: 100%;
            height: 100%;
            background: white;
            margin-top: 100px;
        }
        .main-4-4{
            width: 450px;
            height: 300px;
            margin: 0 auto;
        }
        .main-4-por{
            width: 450px;
            height: auto;
            margin: 50px auto;
            
        }
        .main-4-text{
            float: left;
            font-weight: bold;
             color: #ff4444;
        }
        .main-4-text-back{
            margin-left: 200px;
        }
        .skillNum{
            font-size: 60px;
            text-align: center;
        }


	</style>
	
	<body>
            <div class="loding">L&nbsp;o&nbsp;a&nbsp;d&nbsp;i&nbsp;n&nbsp;g&nbsp;~&nbsp;P&nbsp;l&nbsp;a&nbsp;y&nbsp;~&nbsp;A&nbsp;n&nbsp;i&nbsp;m&nbsp;a&nbsp;t&nbsp;i&nbsp;o&nbsp;n</div>
            <div class="main-1-1" id="main-1-1">
                <div class="logo" id="logo"> Portfolio 
                    <div class="logo2" id="logo2"> Portfolio</div>
                </div>
                <!-- <li></li> -->
                <div class="main-center">
                        <div class="main-1-center" id="main-1-center"> 
                            <div class="center-1">"스며드는"</div>
                            <div class="center-2">Programmer</div>
                        </div>
                       

                        <div class="main-2-center" id="main-2-center"> 
                            <div class="center-3">안녕하세요!</div>
                            <div class="center-4">생후276개월 서세웅입니다.</div>
                        </div>
                        <div class="main-1-scroll" id="main-1-scroll">
                            <div class="scroll"></div>
                            <div class="scroll-text" id="scroll-text">Scroll</div>
                        </div>
                </div>
               
            </div>
        <div class="main-1">
            
        </div>
            
    <!--   ---------------------------메인2-----------------------------------   -->
        <div class="main-2">
            <div>
                <div class="main-poto-1"  id="main-poto-1"><div class="main-poto-1-1"> </div> </div>
                <div class="main-text">
                    <div class="main-text1"> 18.10 ~ 20.05 ㅣ 육군 조교로 복무</div>
                    <div class="main-text1"> 18.03 ~ 23.03 ㅣ 수성대학교 VR콘텐츠과 졸업 예정</div>
                    <div class="main-text1"> 22.07 ~ 22.08 ㅣ 네오컬쳐 인턴실습</div>
                    
                </div>
            </div>
        </div>
    
     <!--   ---------------------------메인3-----------------------------------   -->


        <div class="main-3">
            <div class="main-3-text">Skill</div>
            <div class="main-3-skill">
                 <div class="main-3-skill-1" id="main-3-skill-1"><div class="skillNum" id="skillNum">0%</div></div>
                 <div class="main-3-skill-1"></div>
                 <div class="main-3-skill-1"></div>
                 <div class="main-3-skill-1"></div>
                 <div class="main-3-skill-1"></div>
            </div>
        </div>
        

        
     <!--   ---------------------------메인4-----------------------------------   -->
     <div class="main-4">
        <div class="main-4-4">
       
            <a id="frame" href="https://www.hanbyuloptical.com/bbs/board.php?bo_table=notice">
                <div id="card">
                    <div id="light"></div>
                </div>
             </a>

            <div class="main-4-por">
                <div class="main-4-text"> 프로젝트</div>
                <div class="main-4-text-back">웹 유지보수(반응형/게시판제작)</div>
                <div class="main-4-text"> 프로젝트 참여도</div>
                <div class="main-4-text-back">유지보수(100%)</div>
                <div class="main-4-text"> Tool </div>
                <div class="main-4-text-back">Html/css/javascript</div>
            </div>
        </div>
    </div>    
            

	</body>
	<script>
        

                
                var logo1 =  document.getElementById('logo');
                var logo2 =  document.getElementById('logo2');
                var center =  document.getElementById('main-1-center');
                var main1 =  document.getElementById('main-1-1');
                var main2 =  document.getElementById('main-2-center');
                var main1scroll =  document.getElementById('main-1-scroll');
                var sctext =  document.getElementById('scroll-text'); 
                

                window.addEventListener('scroll',function(){
                    let value = window.scrollY;
                    var nVScroll = document.documentElement.scrollTop || document.body.scrollTop;
                   

                    if(nVScroll > 500){
                        main2.style.opacity = value * 0.0005;
                        $(".main-2-center").css("margin-top","-400");
                    }     
                    else{
                        main2.style.opacity = 0;
                        $(".main-2-center").css("margin-top","-300");
                    }

                    if(nVScroll > 2000){
                       $(".main-center").css("opacity", "0");
                        
                    }    
                    else{
                        $(".main-center").css("opacity", "1");
                    }
                    
                    main1.style.opacity = 0.85 + (value * 0.001);

                    center.style.opacity = 1 - (value * 0.003);
                    center.style.scale = 1 - (value * 0.0006);

                    logo1.style.scale = 1 + (value * 0.001);
                    logo1.style.left = value * 0.1 + "px";
                    logo1.style.opacity = 1 - (value * 0.0005);

                    main1scroll.style.opacity = 1 - (value * 0.0005);
                    
                   

                    sctext.style.rotate = value * 0.1 + 'deg';

                    /* main2.style.opacity =  value * 0.0005;
                    main2.style.translate = value * 0.01 +"px" ; */
                    
                   
                    /* main1.style.background = value */

                });

                $(window).on("load",function(){
                    $(".loding").hide();
                });
                /* $(window).scroll(function(){
                    var nVScroll = document.documentElement.scrollTop || document.body.scrollTop;		
                   
                    if(nVScroll > 350){
                        $("#main-2-center").attr("id","as");
                    }
                })		 */
               
                /* ---------------------마우스 온 이벤트----------------- */
				

                

                const frame = document.getElementById('frame')
                const card = document.getElementById('card')
                const light = document.getElementById('light')
                
                
               
                /* let { x, y, width, height } = {342, 302.5, 450, 300}; */
                let  y = 300;
                let  x = 700;
                let  width = 450;
                let  height = 300;
                

                console.log(frame.getBoundingClientRect())
                function mouseMove(e) {
                    
                
                const left = e.clientX - x
                const top = e.clientY - y
                const centerX = left - width / 2
                const centerY = top - height / 2
                const d = Math.sqrt(centerX**2 + centerY**2)

                card.style.boxShadow = `
                    ${-centerX / 5}px ${-centerY / 10}px 10px rgba(0, 0, 0, 0.2)
                `
                
                card.style.transform = `
                    rotate3d(${-centerY / 100}, ${centerX / 100}, 0, ${d / 8}deg)
                `

                light.style.backgroundImage = `
                    radial-gradient(circle at ${left}px ${top}px, #00000040, #ffffff00, #ffffff99)
                    `
                }

                frame.addEventListener('mouseenter', () => {
                frame.addEventListener('mousemove', mouseMove)
                })
                
                frame.addEventListener('mouseleave', () => {
                frame.removeEventListener('mousemove', mouseMove)
                card.style.boxShadow = ''
                card.style.transform = ''
                light.style.backgroundImage = ''
                })

                window.addEventListener('resize', () => {
                rect = frame.getBoundingClientRect()
                x = rect.x
                y = rect.y
                width = rect.width
                height = rect.height
                })
	/* -----------------------------------------숫자 애니메이션--------------------------------------		 */	

                
                

               
                const skill = document.getElementById('main-3-skill-1');
                const skillNum = document.getElementById('skillNum');

                skill.addEventListener('mousemove',(event) => {
                    
                    const counter = ($counter, max) => {
                    let now = max;
                    
                    
                    const handle = setInterval(() => {
                        $counter.innerHTML = Math.ceil(max - now);
                    
                        // 목표수치에 도달하면 정지
                        if (now < 1) {
                        clearInterval(handle);
                        }
                        
                        // 증가되는 값이 계속하여 작아짐
                        const step = now / 10;
                        
                        // 값을 적용시키면서 다음 차례에 영향을 끼침
                        now -= step;
                        }, 50);
                    }

                    window.onload = () => {
                    // 카운트를 적용시킬 요소
                    const $counter = document.querySelector(".skillNum");
                    
                    // 목표 수치
                    const max = 80;
                    
                    setTimeout(() => counter($counter, max), 500);
                    }
            });

               
                
	</script>
</html>
<!--

		<script>
     
    </script>
	-->
	
	<!-- -->


















<!--
**tpdnd7745/tpdnd7745** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
