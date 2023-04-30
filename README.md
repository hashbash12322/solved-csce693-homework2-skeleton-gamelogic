Download Link: https://assignmentchef.com/product/solved-csce693-homework2-skeleton-game_logic
<br>
<ol>

 <li>Complete the skeleton “game_config” project so that it enhances the provided game_loop example by reading the provided Lua script “config.lua” which defines initial SDL2 window dimensions (x, y, width, and height). Use the Lua API to access this file – do not use the sol2 templates.</li>

 <li> Complete the skeleton “game_logic” project so that it enhances the provided</li>

</ol>

“game_loop” example by reading the Lua script “logic.lua” which defines a function called “update()”. The C++-based update() function should call the Lua update() function which increments a counter variable and returns it. Print this value (in the C++ code) to the console, just like the original “game_loop” example. Expected output should be the current value of the counter that the Lua interpreter is incrementing (e.g., 1, 2, 3, 4…).