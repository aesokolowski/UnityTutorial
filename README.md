# UnityTutorial

tutorial URL: https://www.youtube.com/watch?v=p8FSaMlDbVM&list=PLytjVIyAOStrTBXBuuMR0HjXGIk4DtJrv

puzzle sprites source: https://www.kenney.nl/assets/puzzle-pack



###run instructions:

start new 2D project in Unity Project editor, overwrite directories with the
ones in this repository, build for Android

###changelog

v 0.1.1: features: made larger png to use for icon; moved boundaries inward;
         changed font

         issues (resolved): learned the hard way to never delete the .meta for          Unity-generated sprites, spent way too long resizing both the
         borders, which shrunk down to nothing, and then resizing the
         collision detection, which blew up

v 0.0.1: completed tutorial.

         features: ball bounces against wall, against paddle; game resets when
         ball leaves camera through bottom of screen; counter keeps track
         of how many times ball makes contacts with paddle; ball is "pushed"
         in random direction upon start; touching right side of screen moves
         paddle to the left and touching left side of screen moves paddle
         to the right

         issues: ugly font; left and right boundaries are too far over to
         show on my phone (find better way to scale?); should move so-far
         unused sprites into a separate folder outside the root so that
         they don't take up random space in the build (or in the repository)
