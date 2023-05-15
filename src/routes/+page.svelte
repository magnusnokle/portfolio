
<body>

<div class="">
    <img alt="s" src={bilde}>
</div>


<div>
    <div class="  mt-48 flex flex-col items-center ">
            <div class="flex flex-rows w-11/12 place-content-evenly ">
                    <div class="text-3xl  flex flex-col h-min" style="width:600px;" >
                        <div class="flex flex-row font-black mt-4 "> 
                            <img src={overskrift} id="overskrift" alt="">   
                        </div>
                            <br>
                            <!-- kort info om meg -->
                        <p>
                            I am a it student at Elvebakken vgs,
                            my main fields is svelte with javascript,
                            But I also use react, tailwind, sanity, python, 
                            html And css. read more about me and my projects here.
                        </p>
                        <a href="#linker" on:click={smooth} class="border-4 border-purple-400 rounded-3xl relative right-48">Who am i </a>
                    </div>
                    <div class=" max h-max purple-500 flex flex-col font-light border relative bottom-6"  >
                           <img src={magnus} alt="" id="meg">
                    </div>
            </div>
            <!-- linker for sosiale medier, må legge til linkene -->
            <div class="w-max flex flex-row ml-auto mr-auto " id="linker">
                <img src={insta} id="icon" alt="">
                <img src={discord} id="icon" alt="">
                <img src={spotify} id="icon" alt="">
            </div>
                <div class="flex flex-row">made with <div class="text-purple-600 ml-1 mr-1">svelte</div>and<div class="text-blue-600 ml-1">tailwind</div></div>   
    </div>
    <!-- om meg, må ordne stylingen i xd først. -->
    <div class="border flex flex-row">
        <div class="h-7/12 ml-auto mr-auto flex   mt-36 bg-gray-900 " id="boks">
            <div class=" w-max h-96 flex flex-col  items-start border ml-auto mr-auto mt-12" >  

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
        
        </div>
        <!-- må jobbe med stylingen, ikke fornøyd med hvordan det ser ut per nå -->
        <div class="h-48 flex flex-col m-auto">
            <a href="https://github.com/magnusnokle" class="border-4 border-purple-400">Github</a>
            <a on:click={windowAlert} href="" class="border-4 border-purple-400">CV/Søknad</a>
            <a on:click={windowAlert} href="" class="border-4 border-purple-400">Kontakt meg</a>
        </div>
    </div>
    <div class=" mt-10 text-center" style="width: 100%; height:100px;">
        <p class="ml-auto mr-auto">(this website is still a work in process)</p>

    </div>
    </div>

 
</body>

<style>
    #boks{
        width: 50%;
    }
    #meg{
        width: 250px;
        border: 1px red solid;
    }
    #overskrift3{
       margin-right: 300px;
       border: 1px red solid;
       width: 300px;
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
        width: 600px;
        height: max-content;
    }
    
   
   body{
    color: white;
    width: 100%;
    height: 100%;
    background-color: black;
   }
   img{
    width: 60%;
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
    console.log("hei")
    import bilde from '../logo.png'
    import overksift3 from '../dette.er.meg.png'
    import pil from '../pil.png'
    import insta from '../insta.png'
    import spotify from '../spotify.png'
    import overskrift from '../Screenshot 2023-04-27 at 19.12.54.png'
    import discord from '../discord.png'
    import magnus from '../magnus.png'

    function smooth(){
                        document.documentElement.style.scrollBehavior = "smooth"

      }

    function windowAlert(){
            alert("denne funksjonen er ikke lagt inn enda :(");
    }
</script>