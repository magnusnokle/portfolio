
<body>

<div class="font">
    <img alt="s" src={bilde}>
</div>
<div>
    <div class="  mt-48 flex flex-col items-center ">
            <div class="flex flex-rows w-11/12 place-content-evenly ">
                    <div class="text-3xl  flex flex-col h-min" style="width:600px;" >
                        <div class="flex flex-row text-4xl font-black mt-4 "> 
                            <img src={overskrift} id="overskrift" alt="">   
                        </div>
                            <br>
                        <p>
                            I am a it student at Elvebakken vgs,
                            my main fields is svelte with javascript,
                            But I also use react, tailwind, sanity, python, 
                            html And css. read more about me and my projects here.
                        </p>
                        <a href="#linker" on:click={smooth} class="border-4 border-purple-400 rounded-3xl flex flex-row items-center text-center"><p class="border-2">Who am i </p><img src={pil} id="pil"></a>
                    </div>
                    <div class=" max h-64 purple-500 flex flex-col font-light "  >
                            <a href="https://github.com/magnusnokle/it_eksamen" class="border-4 border-purple-400">Github</a>
                            <a href="/port" class="border-4 border-purple-400">CV/Søknad</a>
                            <a href="" class="border-4 border-purple-400">Kontakt meg</a>
                    </div>
            </div>
            <div class="w-max flex flex-row ml-auto mr-auto mt-20" id="linker">
                <img src={insta} id="icon" alt="">
                <img src={discord} id="icon" alt="">
                <img src={spotify} id="icon" alt="">
            </div>
                <div class="flex flex-row">made with <div class="text-purple-600 ml-1 mr-1">svelte</div>and<div class="text-blue-600 ml-1">tailwind</div></div>   
    </div>
    <div class="h-max w-9/12 ml-auto mr-auto flex items-center flex-row-reverse mt-48 bg-gray-900 ">
        <div class=" w-6/12 flex items-start flex-col mr-20 " >  

            <img src={overksift3} alt="" id="overskrift3"/>
                <br>
            <div id="text">
                <h3>About me:</h3>
                I like being active. In my spare time i like skateboarding combat sports and playing music intruments. I am a person who likes
                helping out collueges and enjoy being in a social enviroment.
            </div>
            <div id="text">
                <h3>My tools</h3>
                My main projects have been around web development. My main projects have included frameworks such as sanity, react, svelte, tailwind but i 
                also have been wprking on projects using javascript and basic terminal hacking.
            </div>
        </div>
        <img src="" alt="" id="profil-bilde">
    </div>

    </div>

 
</body>

<style>
    #pil{
        width: 30px;
        border: 1px red solid;
        rotate: 180deg;
    }

    #overskrift3{
        margin-right:400px;
    }

    #profil-bilde{
        width: 30%;
        height: 400px;
        border: 1px red solid;
    }
    h1{
        
    }
    h3{
        font-weight:600 ;
        font-size: 25px;
    }
    #text{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-weight: 400;
        margin-top: 10px;
        width: 100%;
        height: max-content;
    }
    
   
   body{
    color: white;
    width: 100%;
    height: 100%;
    background-color: black;
   }
   img{
    width: 50%;
    margin-left: auto;
    margin-right: auto;
   }
   #overskrift{
    width: 600px;
   }
   a{
    font-size: 25px;
    width: 200px; 
    height: 40px;
    background-color: black;
    margin: auto;
    text-align: center;
    transition: all 1s;
   }

   a:hover{
    background-color: white;
    color: black;
    color: rgb(192, 132, 252);
   }
   p{
    font-weight: 300;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
   }
 
   #icon{
    width: 70px; 
   }
</style>

<script>
    import bilde from '../logo.png'
    import overksift3 from '../dette.er.meg.png'
    import pil from '../pil.png'
    import insta from '../insta.png'
    import spotify from '../spotify.png'
    import overskrift from '../Screenshot 2023-04-27 at 19.12.54.png'
    import discord from '../discord.png'

    function smooth(){
                        document.documentElement.style.scrollBehavior = "smooth"

      }
</script>