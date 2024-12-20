<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keerthika's profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<style>
    .grid{
        display: grid;
        grid-template-columns: auto auto;
    }
    @media screen and (max-width: 768px) {
    .grid {
        grid-template-columns: auto; 
    
    }
   
   
}

</style>
<body class="bg-gray-200  max-w-4xl mx-auto shadow-lg ">
    <header class="bg-blue-900 text-white text-center p-5">
        <h1 class="text-4xl font-bold">KEERTHIKA M</h1>
        <p class="mt-3 text-2xl">Full-Stack Developer | Web Designer</p>
    </header>
    <main class="p-5 bg-white">
        <!-- About Section -->
        <section class="">
            <h2 class="text-2xl text-blue-900 border-b-2 border-blue-900 pb-2 font-semibold">About Me</h2>
            <p class="mt-4 text-gray-700 text-xl">
                Hi! I'm Keerthika, a passionate full-stack developer specializing in python core language. 
                I have completed my bachelor's degree in Computer Science and am currently pursuing my master's degree. 
                My journey into web design and development has fueled my interest in creating intuitive and visually appealing web applications.
            </p>
        </section>

         <!-- Skills Section -->
          <section class="mt-3">
            <h2 class="text-2xl text-blue-900 border-b-2 border-blue-900 pb-2 font-semibold">Skills</h2>
            <ul class="mt-4 text-gray-700  list-disc list-inside text-xl">
                <li>Python Core Language</li>
                <li>HTML, CSS</li>
                <li>JavaScript, Jquery</li>
                <li>Bootstrap</li>
                <li>Web Design</li>
                <li>Database Management</li>
            </ul>
          </section>

          <!--Contact Section-->
          <section class="mt-3">
             <h2 class="text-2xl text-blue-900 border-b-2 border-blue-900 pb-2 font-semibold">Contact</h2>
             <div class="grid">
             <p class="mt-4 text-gray-700 text-xl">Email : <a href="mailto:keerthikamurugesan7@gmail.com" class="text-blue-500 underline">keerthikamurugesan7@gmail.com</a></p>
             <p class="mt-4 text-gray-700 text-xl">Blog : <a href="https://Keerthika.blogspot.com/" class="text-blue-500 underline">Keerthika.blogspot.com</a></p>
             <p class="mt-4 text-gray-700 text-xl">GitHub : <a href="https://github.com/Keerthika" class="text-blue-500 underline">github.com/Keerthika</a></p>
            
             </div>
          </section>
    </main>

    <footer class="bg-blue-900 text-white p-4 mt-5 text-center text-l">
        <p>© 2024 Keerthika. All rights reserved.</p>
    </footer>
    
</body>
</html>
