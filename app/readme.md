## Example app about navigate between windows

This APP is an example about how to navigate between windows using only Jetpack Compose.
On the other hand, it's important to understand the rol of the "navigation compose" library imported in the build.gradle

First, we need to init a variable with the value of "rememberNavController()". This is important because
it allow us to navigate between windows like a "React navigate" component.

In Second place, we need to use the Composable function "NavHost", defining the navController and the
startDestination parameters.

To define a route, we only have to write: "composable(route=/*routeName*/){Composable function}"

To give parameters to the function, we need to pass them through the URI. Remember to define the function to navigate inside the Composable function.
