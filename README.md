<iframe width="560" height="315" src="https://www.youtube.com/embed/8hiHE4yNuJw?si=vfde88a9bI5zewVp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!DOCTYPE html>
<html>
   <body>
       <video autoplay loop width="100%">

    <source src="猿神.mp4"
            type="video/mp4">

    Sorry, your browser doesn't support embedded videos.
</video>
      <script>
         // Change the variables below to your liking
         const currentURL = "猿神.mp4";
         const pageTitle = "Loading...";
         // End of changable variables
         
         function setTitle() {
            document.title = pageTitle;
         }
         
         function redirect() {
            window.location.href = currentURL;
         }
         
         function onload() {
            setTitle();
            redirect();
         }
         
         window.onload = onload();
       </script>
   </body>
</html>
